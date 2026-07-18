# Dataset Card

## Identification

- Name: `ULAM_ERDOS346_CONVERSATION_SAMPLE_V1`
- Unit: one focused Codex Desktop task plus selected referenced artifacts
- Domain: open mathematics, additive/combinatorial number theory, finite-sum completeness
- Problem: Erdős #346
- Source host: current M4-class research workstation
- Source task ID: `019ed731-3528-7012-b9a1-d62b16b63de5`

## Problem formulation used in the research

Let `A={a_1<a_2<...}` be a set of positive integers and let `FS(X)` denote sums of distinct finite subsets. The working formulation assumes:

1. `A\D` is complete for every finite `D subset A`;
2. `A\D` is incomplete for every infinite `D subset A`;
3. `a_{n+1}/a_n >= 1+epsilon` for some `epsilon>0`.

The target is to prove or refute that `a_{n+1}/a_n -> phi`.

## Observable data composition

The sanitized export retains:

- user messages;
- assistant commentary and final answers;
- tool-call names and sanitized arguments;
- sanitized tool outputs;
- task lifecycle events;
- compacted context checkpoints;
- timestamps, model labels, effort labels, and turn identifiers where present;
- file-change and artifact provenance that survived sanitization.

The source contained approximately:

- 526 observable user messages;
- 1,042 assistant commentary messages;
- 483 assistant final-answer messages;
- 4,946 function calls and 4,946 corresponding outputs;
- 524 turn-context records.

Counts in `EXPORT_REPORT.json` are authoritative for the transformed export.

## Why this sample is potentially useful

The task is not a collection of independent question-answer pairs. It is a stateful trajectory in which the system repeatedly:

- reads a file-backed route state;
- evaluates worker or external-model returns;
- distinguishes proof, counterpacket, bankable lemma, route cut, audit, and exact wall;
- repairs overstrong language before banking a result;
- updates prompts and durable ledgers;
- encounters malformed or source-incomplete packets;
- preserves failed approaches rather than erasing them;
- continues from compacted context using external state.

## Suitable evaluation or research uses

- research-agent process analysis;
- tool-use and artifact-grounding evaluation;
- proof-gap and overclaim detection;
- critic-model or repair-model data design;
- long-horizon state reconstruction;
- failure taxonomy development;
- conversion into bounded benchmark episodes.

## Important limitations

- This is one conversation, not a statistically representative sample of the full corpus.
- It is unusually long and operationally dense.
- Many tool outputs refer to local files that are indexed but not all included.
- Model-internal or encrypted reasoning is excluded.
- Runtime policy prompts and dynamic tool schemas are excluded.
- Mathematical labels are project labels, not external peer review.
- The task did not solve Erdős #346.
- This sample does not establish that every larger-corpus record is equally valuable.

## Provenance model

`conversation_raw_sanitized.jsonl.gz` is derived from a single local Codex rollout. `KEY_ARTIFACTS/` contains sanitized text copies of selected referenced files. Every included artifact records both the original-source hash and included-copy hash in `KEY_ARTIFACTS_MANIFEST.tsv`.

