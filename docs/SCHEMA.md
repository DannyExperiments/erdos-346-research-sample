# Sanitized JSONL Schema

Each line of `conversation_raw_sanitized.jsonl.gz` is one JSON object with:

```json
{
  "timestamp": "ISO-8601 timestamp when available",
  "type": "record type",
  "payload": {}
}
```

## Retained record types

### `session_meta`

Contains non-secret task identity and provenance fields such as thread ID, timestamp, pseudonymized working directory, CLI version, provider label, source, and originator.

### `turn_context`

Contains turn ID, date, timezone, pseudonymized working directory, model, effort, personality label, and compacted summary when present.

### `response_item`

Observable interaction records:

- `message`: user or assistant content;
- `function_call`: tool name and sanitized arguments;
- `function_call_output`: sanitized tool output;
- `custom_tool_call` and `custom_tool_call_output`;
- `tool_search_call` and `tool_search_output`;
- `web_search_call`.

Internal/encrypted `reasoning` records are excluded.

### `event_msg`

Selected observable task lifecycle, tool completion, patch, web-search, compaction, and abort events. Token counters, internal reasoning events, and runtime settings telemetry are excluded.

## Path handling

The source machine's personal home prefix is replaced by `$USER_HOME`. `REFERENCED_PATHS.tsv` is an occurrence/index aid, not a guarantee that every referenced path exists or is included.

## Joining calls and outputs

Use `payload.call_id` to join tool calls with outputs where available. Use `turn_context.payload.turn_id` and event turn identifiers for turn-level grouping.
