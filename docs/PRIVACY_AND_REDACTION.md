# Privacy and Redaction Boundary

## Removed record classes

- model-internal or encrypted reasoning payloads;
- developer/system message records;
- runtime base instructions;
- dynamic tool schemas;
- token-count and rate-limit telemetry;
- world-state/runtime-policy records;
- unrelated browser, wallet, cookie, keychain, and terminal-ad transcript artifacts.

## Text substitutions

- the personal home-directory prefix is replaced with `$USER_HOME`;
- credential-shaped API keys, access tokens, authorization headers, JWTs, and private-key blocks are replaced with typed redaction markers;
- credential assignments are replaced with `[REDACTED]`;
- email addresses and IP addresses are removed;
- credential-bearing URL parameters are removed.

`EXPORT_REPORT.json` reports the number of substitutions by category. Counts indicate pattern matches, not confirmed live credentials.

## Artifact handling

Only small text artifacts with research-relevant names were eligible. Browser/profile, wallet, credential, cookie, keychain, and terminal-ad paths were excluded. Included files were re-written as sanitized text copies; the original files were not modified.

## Residual-risk audit

Automated pattern checks are followed by a second scan of the shareable tree. No package should be uploaded until that audit passes.

