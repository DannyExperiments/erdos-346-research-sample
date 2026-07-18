# Ulam Review Guide

This sample is meant to answer one question: is the larger corpus worth a serious ingestion pilot?

## Fit with Ulam's published data model

Strong direct matches:

- human-in-the-loop, long-horizon mathematical research traces;
- partial progress with explicit gaps and nonclaims;
- negative routes, first-bad-step evidence, repairs, and adversarial audits;
- source transcripts plus file-backed research state;
- tool calls and outputs that can support agent-environment evaluation.

Work still required before this resembles a canonical Ulam research-trajectory record:

- segment the long task into bounded, judgeable episodes;
- normalize the research problem and dependency graph;
- label Proof Verification Units, golden or partial-golden steps, negative traces, and preference pairs;
- assign review tiers and have mathematical claims independently checked;
- add formal or executable verification where available.

Therefore this package should be judged as candidate source material for curation, not as a finished RLVR dataset or a hidden evaluation set.

## Suggested first review

1. Read the first and last several sections of `conversation_messages.md`.
2. Search for `significant`, `bankable`, `route cut`, `exact wall`, `not a proof`, and `counterpacket`.
3. Inspect several tool-call/output pairs in `conversation_readable.html`.
4. Compare conversational claims against `KEY_ARTIFACTS/*BANKED_LEMMAS.md`, `*CUTS_AND_FALSE_ROUTES.md`, and `*FULL_SOURCE_RECOVERY_AUDIT.md`.
5. Parse the compressed JSONL and test whether call/output joins and turn grouping are usable.

## Questions for Ulam

- Are the observable commentary/final/tool trajectories useful without model-internal reasoning?
- Which record classes would Ulam keep, normalize, or discard?
- Are the project labels sufficiently informative for an initial failure taxonomy?
- Would Ulam prefer complete long tasks or bounded episodes cut around one claim/audit/repair sequence?
- Are file-change events and external artifact hashes useful as grounding signals?
- What additional labeling would materially increase value?
- Does Ulam want raw operational noise, or only high-signal theorem episodes?

## Decision rule

If Ulam finds this useful, the next stage should be a deliberately stratified sample rather than the entire corpus:

- one Erdős #346 long-horizon trajectory;
- one Erdős #361 multi-agent/director trajectory;
- one RS-MCA verifier/audit/publication trajectory;
- one negative-control conversation with little mathematical value.

That second pilot would measure corpus heterogeneity before committing to the full transfer.
