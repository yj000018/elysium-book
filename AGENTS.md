# Agent operating contract — ELYSIUM — book manifestation

Read [PROJECT.md](PROJECT.md), [documentation map](docs/README.md) and [CURRENT](docs/status/CURRENT.md) before editing. Repository role: `MANIFESTATION`.

## Authority and safe edits

A single consolidated ELYSIUM repository has not been selected or created by Wave A. Both existing manifestation histories remain independent.

Preserve source provenance, creative text, licenses, source manifests, hashes and immutable receipts. This normalization scope covers navigation/metadata only, with no physical merge, repository rename, archival, runtime activation or external publication. Keep existing payload paths; do not infer ownership or completion from a folder name. Read more specific module instructions before code work.

## Validation

Validate source/translation correspondence and publication manifests; no root software build is tracked.

For documentation, check local links, metadata against the YOS crosswalk, changed-path scope, and the remote commit/default branch after publication. For code, run the relevant module checks; a commit or passing local test does not prove deployment.

## Durable documentation

Use the map in docs/README.md. Accepted canon, accepted decisions, architecture/specs, current status, handoffs, research, evidence and history remain separate. A research draft, chat or handoff is never implicitly canon. Structural/hard-to-reverse decisions need an ADR; smaller durable decisions belong in the ledger. Create semantic directories only when they have material.

## Secrets

Never commit credentials, access tokens, cookies, private runtime configuration or newly acquired private raw exports. Use ignored local configuration and an approved secret store. Do not print secrets in validation receipts.
