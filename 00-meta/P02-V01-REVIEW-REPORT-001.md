# P02 v0.1 — Rapport de revue contrôlée

**Document ID :** `P02-V01-REVIEW-REPORT-001`
**Date :** 2026-10-14
**Cible :** `01-source-en/P02_ONTOLOGY.md`
**Statut de la revue :** `REVIEW_ATTENTION_REQUIRED`
**Mode :** addition-only ; aucune correction appliquée

## Verdict synthétique

```text
EDITORIAL_COHERENCE = PASS_WITH_REVISIONS
CONCEPTUAL_COHERENCE = BLOCKED_PENDING_12_STEP_DECISION
FACTUAL_POSTURE = PASS_WITH_RESERVATIONS
PROVENANCE_VISIBILITY = PARTIAL
P02_v0.1_PROMOTION = NOT_RECOMMENDED
```

La prose est structurée et respecte l’intention générale du brief, mais elle ne doit pas passer en `v0.2` avant résolution de la nomenclature des 12 étapes et réconciliation des statuts éditoriaux.

## Finding P02-REV-001 — BLOQUANT CONCEPTUEL

### Divergence

Trois formulations concurrentes des 12 étapes coexistent :

1. `00-meta/ontology-map.md` du Book décrit :
   - Definition
   - Function
   - Current State
   - Historical Evolution
   - Core Pathologies
   - Feedback Loops
   - Dependencies
   - Cross-Foundation Couplings
   - Leverage Points
   - Regenerative Alternatives
   - Transition Pathways
   - Metrics / Signals of Health

2. Le brief P02 diagnostique décrit une autre séquence :
   - Definition / ontology
   - Function / teleology
   - Current paradigm
   - Current crisis
   - Transitions in progress
   - Technological and AI catalyst
   - Cultural and inner transition
   - Future paradigm
   - Transition pathways
   - Projects and experiments
   - Risks and blind spots
   - Resources and library

3. Les matrices pilotes dérivées utilisent effectivement la seconde famille d’intitulés, avec des variantes éditoriales en français.

### Impact

P02 affirme que l’ordre de travail est confirmé, mais la base documentaire accessible ne permet pas d’affirmer que les deux vocabulaires sont équivalents étape par étape. Une harmonisation silencieuse créerait une dérive de modèle.

### Décision requise

Choisir et versionner explicitement l’une des options :

- **Option A — séparation des couches :** conserver `ontology-map.md` comme matrice conceptuelle A et les 12 étapes des matrices comme protocole éditorial dérivé, avec table de correspondance explicite ;
- **Option B — convergence contrôlée :** produire une nouvelle spécification v0.2 des 12 étapes, validée Founder, puis dériver les matrices concernées ;
- **Option C — maintien prudent :** laisser les deux séquences coexistantes comme instruments différents, sans prétendre qu’elles sont identiques.

Aucune option ne doit être appliquée par réécriture silencieuse.

## Finding P02-REV-002 — GOUVERNANCE MÉTADONNÉES

`P02_ONTOLOGY.md` est désormais `draft / editorial_review`, alors que `00-meta/manuscript-status.md` le conserve en `NOT_STARTED / TBD`.

Ce n’est pas une contradiction de contenu, mais un drift de registre éditorial. Il faut créer une mise à jour addition-only du statut du manuscrit ou documenter que le fichier de statut reste historique.

## Finding P02-REV-003 — PROVENANCE PARTIELLEMENT VISIBLE

Le texte indique que l’usage de `v0.3-revised` doit conserver les hashes, mais n’expose pas encore dans le module P02 :

- les trois hashes des dérivés utilisés ;
- les hashes des parents directs ;
- le lien entre chaque exemple et sa source distante ;
- le receipt MVS‑1 exact.

Recommandation : ajouter un bloc de provenance éditoriale en v0.2, sans transformer P02 en registre technique.

## Finding P02-REV-004 — RÉVISION ÉDITORIALE

Le guide de style demande une progression : diagnostic, exemple systémique, principe, implication architecturale, transition. P02 suit bien la logique architecturale, mais plusieurs sections restent principalement déclaratives. La v0.2 devrait ajouter au moins :

- un exemple de propagation Micro → Meso → Macro ;
- un exemple de lecture d’une facette avec une matrice pilote ;
- un exemple concret de différence de portée entre A et B.

## Points validés

- Une seule balise H1 dans le module.
- Neuf sections principales conformes au brief.
- Statut `draft` et version `0.1` correctement déclarés.
- Aucun passage ne présente les matrices dérivées comme des sources récupérées.
- La coexistence A/B est explicitement préservée.
- ETF est présenté comme relation non équivalente.
- Les quatre claims bloqués sont maintenus comme réserves.
- Le module ne modifie aucune matrice ni registre Ontology.
- Le compteur de mots déclaré et mesuré est cohérent : 1 705.

## Recommandation de passage

```text
v0.1 → revue Founder ciblée sur la nomenclature des 12 étapes
      → décision de couche / correspondance
      → mise à jour metadata + provenance
      → rédaction P02 v0.2
```

Jusqu’à cette décision, P02 reste un **draft contrôlé utilisable pour lecture interne**, mais pas une version éditorialement stabilisée.
