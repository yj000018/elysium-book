# ELYSIUM — Crosswalk des deux couches de 12 étapes

**Document ID :** `12-STEP-LAYER-CROSSWALK-001`
**Date :** 2026-10-14
**Statut :** `APPROVED_LAYER_SEPARATION / NON_CANONICAL_CROSSWALK`
**Décision Founder :** séparation des couches avec correspondance explicite

## Principe

Deux séquences de 12 étapes sont conservées :

- **Couche conceptuelle A** : matrice ontologique de référence du Book, telle qu’elle apparaît dans `00-meta/ontology-map.md` ;
- **Couche éditoriale dérivée E** : protocole opérationnel observé dans les matrices pilotes dérivées et utilisé pour organiser les exemples P02.

La table ci-dessous décrit des relations de lecture, pas une identité terme à terme. Les écarts sont conservés comme information de modèle.

## Table de correspondance

| # | Couche conceptuelle A | Couche éditoriale dérivée E | Relation | Réserve |
|---:|---|---|---|---|
| 1 | Definition | Definition / ontology | Correspondance forte | E ajoute une entrée ontologique explicite. |
| 2 | Function | Function / teleology | Correspondance forte | E rend la finalité plus visible. |
| 3 | Current State | Current paradigm | Correspondance partielle | E lit l’état comme arrangement dominant ; A reste plus large. |
| 4 | Historical Evolution | Current crisis | Non-équivalence | E ne couvre pas l’histoire ; elle introduit directement la crise. |
| 5 | Core Pathologies | Transitions in progress | Non-équivalence | E saute de la crise aux transitions ; la pathologie A doit rester visible. |
| 6 | Feedback Loops | Technological and AI catalyst | Non-équivalence | E ajoute un catalyseur absent comme étape autonome dans A. |
| 7 | Dependencies | Cultural and inner transition | Non-équivalence | E traite une transition culturelle, pas les dépendances structurelles A. |
| 8 | Cross-Foundation Couplings | Future paradigm | Non-équivalence | E décrit une architecture cible ; A décrit les couplages. |
| 9 | Leverage Points | Transition pathways | Correspondance fonctionnelle partielle | Les chemins E peuvent contenir des leviers, sans les épuiser. |
| 10 | Regenerative Alternatives | Projects and experiments | Correspondance fonctionnelle partielle | E descend vers des cas et projets ; A reste au niveau des alternatives. |
| 11 | Transition Pathways | Risks and blind spots | Non-équivalence | E ajoute une couche de prudence absente comme étape dédiée dans A. |
| 12 | Metrics / Signals of Health | Resources and library | Non-équivalence | E documente les ressources ; A demande des signaux de mesure. |

## Éléments propres à chaque couche

### Propriétés propres à A

- évolution historique ;
- pathologies fondamentales ;
- boucles de rétroaction ;
- dépendances ;
- couplages inter-fondations ;
- leviers ;
- métriques et signaux de santé.

### Propriétés propres à E

- paradigme actuel comme forme lisible de l’état ;
- transitions déjà en cours ;
- catalyseur technologique et IA ;
- mutation culturelle et intérieure ;
- projets et expériences ;
- risques et angles morts ;
- ressources et bibliothèque.

## Règle d’usage dans P02

- P02 présente **A comme matrice conceptuelle de référence**.
- P02 présente **E comme protocole éditorial dérivé pour organiser les matrices pilotes**.
- Une matrice E ne doit pas être décrite comme une implémentation complète de A.
- Une absence dans E ne doit pas être interprétée comme une absence du modèle A.
- Une étape propre à E ne doit pas être ajoutée silencieusement à A.
- Les futures matrices peuvent documenter les deux couches ou produire une version explicitement alignée.

## Verdict

```text
LAYER_SEPARATION = APPROVED
CROSSWALK = EXPLICIT
TERM_EQUIVALENCE = NOT_ASSERTED
SOURCE_MUTATION = NONE
CANONICAL_PROMOTION = NONE
```
