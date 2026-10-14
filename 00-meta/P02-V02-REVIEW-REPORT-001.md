# P02 v0.2 — Rapport de revue éditoriale et factuelle

**Document ID :** `P02-V02-REVIEW-REPORT-001`
**Date :** 2026-10-14
**Cible :** `01-source-en/P02_ONTOLOGY.md`
**Statut :** `REVIEW_ATTENTION_REQUIRED`
**Mode :** diagnostic addition-only ; aucune correction du module dans ce rapport

## Verdict

```text
EDITORIAL_COHERENCE = PASS_WITH_TARGETED_REVISIONS
CONCEPTUAL_COHERENCE = PASS_WITH_2_INTERFACE_REVISIONS
FACTUAL_POSTURE = CONDITIONALLY_PASS / NO_EXTERNAL_CLAIM_VALIDATION_IN_P02
PROVENANCE_VISIBILITY = INSUFFICIENT_FOR_PRODUCTION
P02_v0.2_PROMOTION = NOT_YET_RECOMMENDED
```

La décision de séparation des couches est correctement intégrée. Le module est cohérent comme draft interne, mais quatre ajustements sont nécessaires avant de le qualifier de version de production review-ready.

## Finding P02-V02-001 — INTERFACE CONCEPTUELLE

### Localisation

Section 6, paragraphe présentant Taxonomy A :

> “Taxonomy A — Metabolic provides the Book's primary architecture: scales, foundations, facets and the twelve-step analytical sequence.”

### Problème

Après la décision Founder de séparation, cette formulation au singulier peut être lue comme si A possédait une seule séquence opérationnelle. Le module vient pourtant d’établir :

- la **couche conceptuelle A** de `ontology-map.md` ;
- la **couche éditoriale dérivée E** des matrices pilotes.

### Correction requise

Remplacer par une formulation précisant que Taxonomy A fournit la matrice conceptuelle de référence, tandis que E organise les dérivés éditoriaux. Ne pas fusionner les deux séquences.

**Sévérité :** moyenne — correction de précision, pas changement d’architecture.

## Finding P02-V02-002 — PROVENANCE DE PRODUCTION

### Problème

P02 affirme que la couche `FACET_MATRICES_DERIVED_V03_REVISED` possède des hashes, citations et receipts, mais ne donne pas encore dans le module :

- les trois identifiants de facettes pilotes ;
- les hashes des parents et dérivés ;
- la référence au receipt MVS‑1 ;
- la distinction entre citation validée et réserve encore ouverte.

La dépendance vers le dépôt Ontology ne suffit pas à rendre la provenance lisible pour un lecteur du Book.

### Correction requise

Ajouter un bloc court “Provenance de la baseline de travail” ou une référence vers un manifeste versionné, sans transformer P02 en registre technique. Les hashes complets doivent rester dans le registre de provenance ; P02 peut les référencer par identifiants et liens.

**Sévérité :** haute — exigence explicite du brief, critère de sortie n°5.

## Finding P02-V02-003 — MÉTADONNÉES HÉRITÉES

Deux éléments restent hérités du brief v0.1 :

1. Le brief `P02-ONTOLOGY-DIAGNOSTIC-BRIEF-001.md` conserve `PROSE_NOT_STARTED` alors que P02 v0.2 existe et est fusionné.
2. P02 section 8 parle encore de “this first prose draft”, alors que le module est désormais la version contrôlée `0.2` avec séparation des couches approuvée.

### Correction requise

- Conserver le brief historique comme trace de l’état initial, mais ajouter une note de supersession ou un statut `BRIEF_SUPERSEDED_BY_CONTROLLED_PROSE` dans une modification séparée.
- Remplacer “this first prose draft” par “this controlled draft” dans P02.

**Sévérité :** moyenne — drift documentaire, sans impact sur les sources.

## Finding P02-V02-004 — REVUE FACTUELLE

### Résultat

Aucun claim externe chiffré ou scientifique nouveau n’est introduit directement dans P02 v0.2. Les formulations concernant les trois matrices pilotes, les claims réservés, l’ETF et les états `Source / Derived / Framework / Review / Founder decision` sont des assertions de gouvernance ou de cadrage interne.

En revanche, P02 renvoie indirectement à des éléments externes dans la description des matrices :

- pertes économiques en points de PIB ;
- zoonoses ;
- Natural Capital Protocol ;
- extinction contemporaine ;
- limites planétaires.

Ces éléments sont correctement présentés comme réserves ou sujets nécessitant qualification, mais aucune validation bibliographique externe n’est effectuée dans P02 lui-même.

### Verdict factuel

```text
NO_UNQUALIFIED_EXTERNAL_CLAIM_DETECTED = PASS
EXTERNAL_SOURCE_VALIDATION = DEFERRED_TO_PILOT_MATRIX_REGISTERS
```

P02 peut rester un cadrage ontologique non bibliographique, à condition de ne pas développer ces claims dans une prochaine version sans liens de preuve.

## Contrôles validés

- Version front matter : `0.2`.
- Statut : `draft / editorial_review`.
- Compteur : `1 930` déclaré et mesuré.
- Une seule balise H1.
- Architecture `3 × 7 × 38 × 12` visible.
- Taxonomies A et B explicitement coexistantes.
- ETF non présenté comme synonymie ou fusion.
- Crosswalk présent et non canonique.
- Aucun dérivé présenté comme source originale.
- Compilation désactivée.
- Registre manuscrit aligné sur `DRAFT / III-1A`.

## Parcours recommandé vers v0.3

```text
1. Corriger la phrase d’interface Taxonomy A / couches 12 étapes.
2. Ajouter la provenance visible de la baseline pilote.
3. Actualiser les deux métadonnées héritées du brief.
4. Rejouer diff-check, word-count et provenance QA.
5. Soumettre P02 v0.3 à la revue Founder finale.
```

Aucune promotion `CANONICAL` n’est recommandée avant ces quatre opérations.
