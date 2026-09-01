# EDITORIAL-SPINE-001 — Decision Log

This log is append-only. A later decision may supersede a previous decision only by referencing the prior ID and retaining its original record.

| ID | Date | Authority | Decision | Alternatives retained | Scope |
|---|---|---|---|---|---|
| `EDT-DEC-001` | 2026-09-01 | Yannick | Treat Book Brief, Manuscript Status, and Production Roadmap as the active production reference. | Book Canon, 2023 roadmap, V1, and V2 remain preserved. | ELYSIUM only. |
| `EDT-DEC-002` | 2026-09-01 | Yannick | Treat Book Canon and 2023–2028 roadmap as preserved historical strategic references. | Their narrative, audience, and dissemination value remains available. | ELYSIUM only. |
| `EDT-DEC-003` | 2026-09-01 | Yannick | Treat TOC v1 and TOC v2 as candidate structures. | Neither is selected as a canonical manuscript structure. | ELYSIUM only. |
| `EDT-DEC-004` | 2026-09-01 | Yannick | Use the ELYSIUM Taxonomy Federation as the translation layer between Taxonomy A and Taxonomy B. | Source taxonomies remain autonomous. | ELYSIUM only. |
| `SPINE-DEC-001` | 2026-09-01 | Yannick | Adopt the hybrid federative structure as `EDITORIAL-SPINE-001`, under `PROPOSED_DERIVED_VIEW`. | V1, V2, Book Canon, and active Book sources retain their own status. | `elysium-book/00-meta/`. |
| `SPINE-DEC-002` | 2026-09-01 | Yannick | Host the spine in `elysium-book/00-meta/`. | A neutral cross-repository support layer remains possible if editorial federation grows. | `elysium-book` only. |
| `SPINE-DEC-003` | 2026-09-01 | Yannick | Preserve V1 and V2 as `CANDIDATE_STRUCTURE`. | Future selection may choose V1, V2, or revise the hybrid with an explicit decision. | ELYSIUM only. |
| `SPINE-DEC-004` | 2026-09-01 | Yannick | Preserve Z-Axis as `DEFERRED_CANDIDATE`. | A dedicated decision may later include, redefine, or exclude it. | No active module. |
| `SPINE-DEC-005` | 2026-09-01 | Yannick | Prioritize stabilization of 3×7×38×12 before a P02 writing brief or any foundation drafting. | Preparatory research and proof collection remain allowed. | ELYSIUM only. |

## Standing constraints

- This decision log does not modify any source, taxonomy, TOC, manuscript module, or roadmap.
- `P01_OPENING` remains the only active draft according to `manuscript-status.md` at the recorded observation time.
- Any source-content change requires a separate approved pull request.
