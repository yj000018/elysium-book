# EDITORIAL-SPINE-001 — ELYSIUM Federative Editorial Spine

**Status:** `PROPOSED_DERIVED_VIEW`
**Decision authority:** Yannick
**Scope:** ELYSIUM Book only
**Rule:** This document is a navigational manifest. It does not replace, alter, or silently promote any source TOC, module, taxonomy, strategy, or roadmap.

## Purpose

`EDITORIAL-SPINE-001` is the working editorial view for ELYSIUM. It combines the active modular production flow in this repository with two preserved candidate tables of contents, the historical Book Canon, and the ELYSIUM Taxonomy Federation. Its role is to make a faithful path from the current manuscript state to a coherent public book possible without erasing valid prior work.

> The active production spine is `P01 → P02 → P03…P09 → P10`. Everything else in this manifest is a declared source, a candidate, a historical reference, or a federative relation.

## Authority and source hierarchy

| ID | Source | Authority in this spine | Status preserved |
|---|---|---|---|
| `ED-ACTIVE-IDENTITY` | [`book-brief.md`](book-brief.md) | Active identity, methodology, tone, and 3×7×38×12 architecture. | Active reference. |
| `ED-ACTIVE-PRODUCTION` | [`manuscript-status.md`](manuscript-status.md) | Current factual production state and module IDs. | Active source of status. |
| `ED-ACTIVE-ROADMAP` | [`production-roadmap.md`](production-roadmap.md) | Active production sequence and gating dependencies. | Active execution reference. |
| `ED-CANDIDATE-TOC-V1` | [`16_ELYSIUM_BOOK_TOC.md`](https://github.com/yj000018/elysium-civilizational-ontology/blob/main/05_RESEARCH_CORPUS/RAW_RESEARCH/16_ELYSIUM_BOOK_TOC.md) | Foundation chapter mapping and 12-step matrix bridge. | Candidate structure. |
| `ED-CANDIDATE-TOC-V2` | [`16_ELYSIUM_BOOK_TOC_V2.md`](https://github.com/yj000018/elysium-civilizational-ontology/blob/main/05_RESEARCH_CORPUS/RAW_RESEARCH/16_ELYSIUM_BOOK_TOC_V2.md) | Front/back matter, enhanced praxis, and optional Z-Axis. | Candidate structure. |
| `ED-LEGACY-CANON` | [`16_BOOK_CANON.md`](https://github.com/yj000018/elysium-civilizational-ontology/blob/main/03_BOOK_AND_PUBLICATION/16_BOOK_CANON.md) | Historical public arc, audience, and dissemination strategy. | Preserved strategic reference. |
| `ED-FEDERATION` | [`ELYSIUM_TAXONOMY_FEDERATION`](https://github.com/yj000018/elysium-civilizational-ontology/tree/main/00_PROGRAM_OFFICE/ELYSIUM_TAXONOMY_FEDERATION) | Typed, non-destructive relations between the two valid taxonomies. | Active relational reference. |

## Spine map

| Slot | Working role | Active production anchor | Candidate or historic contributions | Federation boundary | Status |
|---|---|---|---|---|---|
| `SP-00` | Front matter and introduction. | None. | V2 front matter and introduction. | None. | `CANDIDATE_PACKAGING`. |
| `SP-01` | Opening — *The Map Before the Territory*. | `P01_OPENING` EN/FR/IT. | V1/V2 Ch. 1; Book Canon Ch. 1. | Scales as contextual framing. | `ACTIVE_DRAFT`. |
| `SP-02` | Map — methodology and fractal architecture. | `P02_ONTOLOGY`. | V1/V2 Ch. 2–3; Book Canon Ch. 2–3. | 3 scales, Taxonomy A 12-step matrix, Taxonomy B interlocking. | `NOT_STARTED`. |
| `SP-03` | Material Base. | `P03_FOUNDATION_01_MATERIAL_BASE`. | V1 Ch. 4; V2 Ch. 5. | `A.F01 ↔ B.F04`; environment remains a deferred secondary relation. | `NOT_STARTED`. |
| `SP-04` | Vitality. | `P04_FOUNDATION_02_VITALITY`. | V1 Ch. 5; V2 Ch. 6. | `A.F02 ↔ B.F07`; environment remains autonomous in B. | `NOT_STARTED`. |
| `SP-05` | Agency. | `P05_FOUNDATION_03_AGENCY`. | V1 Ch. 6; V2 Ch. 7. | `A.F03 ↔ B.F03`. | `NOT_STARTED`. |
| `SP-06` | Cohesion. | `P06_FOUNDATION_04_COHESION`. | V1 Ch. 7; V2 Ch. 8. | `A.F04 ↔ B.F05`. | `NOT_STARTED`. |
| `SP-07` | Governance. | `P07_FOUNDATION_05_GOVERNANCE`. | V1 Ch. 8; V2 Ch. 9; Book Canon Ch. 4. | `A.F05 ↔ B.F02`. | `NOT_STARTED`. |
| `SP-08` | Vision. | `P08_FOUNDATION_06_VISION`. | V1 Ch. 9; V2 Ch. 10; Book Canon Ch. 5–6. | `A.F06 ↔ B.F01`. | `NOT_STARTED`. |
| `SP-09` | Consciousness. | `P09_FOUNDATION_07_CONSCIOUSNESS`. | V1 Ch. 10; V2 Ch. 11; Book Canon Ch. 3. | `A.F07` is transversal and has no strict B equivalent. | `NOT_STARTED`. |
| `SP-10` | Praxis — matrix, cases, design, transition. | `P10_SYNTHESIS_TRANSITION`. | V1 Ch. 11–13; V2 Ch. 12–15; Book Canon Ch. 8–10. | Inter-scale and inter-foundational relations. | `NOT_STARTED`. |
| `SP-11` | Z-Axis Dynamics. | None. | V2 Ch. 4. | No ETF relation defined. | `DEFERRED_CANDIDATE`. |
| `SP-12` | Back matter — methodology, model inventory, glossary, index. | Existing glossary is an input; scope remains to be verified. | V2 appendices and back matter. | Provenance and model registry require a dedicated future review. | `DEFERRED_CANDIDATE`. |

## Derivation rules

| Rule | Requirement |
|---|---|
| Source-first | Every future brief or view names its source and state. |
| State separation | `DRAFT`, `NOT_STARTED`, `INTEGRATED`, `historical`, and `candidate` cannot be inferred from one another. |
| No silent canon | A candidate never becomes canonical through inclusion in this spine. |
| Federated semantics | A↔B relations are read from ETF; source definitions are not merged. |
| No premature prose | The active roadmap’s stabilization gate for 3 scales, 7 foundations, 38 facets, and the 12-step matrix precedes foundation drafting. |
| Reversibility | This manifest can be reverted without affecting existing content, sources, or the ETF layer. |

## Explicit exclusions

This manifest does not decide a final table of contents; create a Z-Axis module; rewrite the Book Brief, Production Roadmap, or Manuscript Status; modify any P-module; import source text from Ontology; or migrate ELYSIUM into Y-OS Core.
