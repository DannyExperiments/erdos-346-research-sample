# Erdős #346 Research Conversation Sample

This temporary public repository is an evaluation sample for Ulam. It preserves one long-horizon, human-in-the-loop Codex research trajectory concerning Erdős Problem #346 together with selected theorem-state artifacts. A sanitized machine-readable export exists separately and is described by the included reports and schema.

## Start here

1. Read the [mathematical status and nonclaims](docs/MATHEMATICAL_STATUS.md).
2. Browse the [conversation chapters](conversation/README.md).
3. Inspect [banked lemmas](KEY_ARTIFACTS/11_1b935df337_BANKED_LEMMAS.md), [cuts and false routes](KEY_ARTIFACTS/12_8abc88698b_CUTS_AND_FALSE_ROUTES.md), and the [full source-recovery audit](KEY_ARTIFACTS/24_70df7772b7_FULL_SOURCE_RECOVERY_AUDIT.md).
4. Read the [dataset card](docs/DATASET_CARD.md) and [Ulam review guide](docs/ULAM_REVIEW_GUIDE.md).
5. For format details, read the [schema guide](docs/SCHEMA.md). The compressed machine-readable export can be supplied separately if Ulam wants to test ingestion.

## What this demonstrates

- iterative mathematical exploration with human direction;
- tool-using agent trajectories and file-backed state;
- proposed claims followed by audits, repairs, retractions, and route cuts;
- explicit gaps, negative results, and anti-overclaim discipline;
- enough provenance to reconstruct how the project state evolved.

## Mathematical status

**This is not a solution or refutation of Erdős #346.** It contains partial reductions, local lemmas, rejected approaches, source repairs, and residual walls. Intermediate labels are project-level judgments rather than independent peer review or formal verification.

## Repository map

| Path | Contents |
|---|---|
| [`conversation/`](conversation/README.md) | GitHub-readable chronological transcript chapters |
| [`KEY_ARTIFACTS/`](KEY_ARTIFACTS/) | 24 selected theorem-state, prompt, response, and audit artifacts |
| [`docs/`](docs/) | Dataset card, status, schema, privacy boundary, and review guide |
| [`data/`](data/) | Audit and export reports for the sanitized source package |
| [`KEY_ARTIFACTS_MANIFEST.tsv`](KEY_ARTIFACTS_MANIFEST.tsv) | Source and included hashes for selected artifacts |
| [`CHECKSUMS.sha256`](CHECKSUMS.sha256) | Repository-file integrity hashes |

## Privacy and transformation boundary

The original local Codex source was not modified. Internal/encrypted reasoning, runtime instructions, dynamic tool schemas, telemetry, credential-shaped strings, direct identifiers, and sensitive browser/wallet/keychain paths were excluded or redacted. See the [privacy report](docs/PRIVACY_AND_REDACTION.md) and [`data/AUDIT_REPORT.json`](data/AUDIT_REPORT.json).

## Temporary-public notice

This repository is being published temporarily for technical evaluation. Public availability means anyone can clone, fork, or cache it before the repository is removed. No license is granted for commercial training, redistribution, or publication of mathematical claims merely by making this inspection sample public.
