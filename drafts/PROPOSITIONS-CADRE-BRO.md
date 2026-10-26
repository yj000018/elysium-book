# Propositions de cadre ELYSIUM, par Bro

**Statut :** `PROPOSAL / NON_CANONICAL`. Tout est à valider par Yannick.
**Date :** 2026-10-26
**Origine :** test P05 (`drafts/P05-draft-BRO.md`, verdict « presque »). Il manquait trois pièces au cadre : un brief P05, un format de chapitre tranché et une thèse du fondateur.
**Portée :** ce fichier ne modifie aucun autre fichier. Les changements proposés plus bas pour le gabarit, la roadmap et la spine sont des propositions de texte, pas des éditions.

---

## A. Brief diagnostique P05, Agency (proposé)

**Document ID :** `P05-AGENCY-DIAGNOSTIC-BRIEF-001` (proposé)
**Position dans la spine :** `SP-05`, Agency
**Statut proposé :** `DIAGNOSTIC_BRIEF_PROPOSED / PROSE_TEST_ONLY`
**Autorité de cadrage :** P02 v0.3, `ACCEPTED_AS_CONTROLLED_WORKING_DRAFT`
**Continuité :** P03 v0.1 et P04 v0.1, tous deux en `DRAFT / EDITORIAL_REVIEW`

### 1. Fonction du brief
P05 doit développer la troisième fondation de Taxonomy A, **Agency** : la capacité humaine d'agir, de créer de la valeur et de coordonner l'action productive.

P05 doit :
1. définir Agency comme le champ de mobilisation du potentiel humain, et pas seulement comme « l'économie » ;
2. situer ses six facettes sans en faire six chapitres autonomes prématurés ;
3. appliquer les deux couches de douze étapes de P02 ;
4. expliciter les couplages avec les six autres fondations ;
5. préserver ETF-0007 sans fusionner A et B ;
6. garder ETF-S-003 (vers B.Knowledge) comme relation différée ;
7. distinguer les faits sourcés, les dérivés, le cadre ELYSIUM, les hypothèses de transition et les claims en revue.

P05 ne doit pas encore :
- présenter une « économie régénérative » comme si elle existait déjà ;
- réduire Agency au PIB, à l'emploi ou au marché ;
- prendre position de manière doctrinale pour ou contre une école économique ;
- fermer les claims sur la financiarisation, l'automatisation par l'IA ou l'emploi ;
- promouvoir quoi que ce soit au statut `CANONICAL`.

### 2. Définition de référence A.F03
D'après `ontology-map.md`, la définition est : *the mechanisms of value creation, work, innovation, and economic exchange*.
- **Fonction :** mobiliser le potentiel humain.
- **Pathologie :** financiarisation, aliénation du travail, économie extractive.
- **Direction :** entreprise orientée par le sens, finance régénérative, production distribuée.

Ce sont des repères, pas une définition scientifique.

### 3. Facettes A.F03 à couvrir
| ID | Facette | Cadrage P05 |
|---|---|---|
| `F03_01` | Economy | Échange et allocation, avec un périmètre explicite (marché, communs, don) |
| `F03_02` | Work | Travail rémunéré et non rémunéré, care, sens, aliénation |
| `F03_03` | Finance | Crédit, capital, monnaie ; financiarisation comme claim en revue |
| `F03_04` | Entrepreneurship | Initiative, prise de risque, création d'organisations |
| `F03_05` | Innovation | Nouveauté technique et sociale ; frontière avec Vision et B.Knowledge |
| `F03_06` | Production | Transformation de matière et d'énergie en biens, distribuée ou centralisée |

### 4. Relation fédérative avec Taxonomy B
```text
ETF-0007   A.F03 Agency ↔ B.F03 Economy   PRIMARY_CORRESPONDENCE   confidence = high
ETF-S-003  A.F03 ↔ B.F01 Knowledge        SECONDARY_CORRESPONDENCE status = deferred
```
Réserve obligatoire : A met au premier plan le potentiel humain et la capacité d'agir, B la structure économique et l'inclusion. Ce n'est pas une synonymie. Pour Innovation, il faut comparer avec des notes de portée, sans normalisation silencieuse.

### 5. Architecture des douze étapes
On reprend à l'identique la couche conceptuelle A (Definition à Metrics / Signals of Health) et la couche éditoriale E, comme dans P04 et `12-STEP-LAYER-CROSSWALK-001`.

### 6. Couplages inter-fondations
- **Material Base :** énergie, matériaux, infrastructures de production.
- **Vitality :** santé au travail, agriculture, économie du care.
- **Cohesion :** inégalités, appartenance par le travail, communs.
- **Governance :** droit économique, régulation financière, fiscalité.
- **Vision :** recherche, éducation, IA et technologie comme facteurs de production.
- **Consciousness :** sens du travail, valeurs, ce que « valeur » veut dire.

Ce sont des axes d'analyse, pas des claims.

### 7. Réserves probatoires obligatoires
- financiarisation (définitions, mesures, périodes) ;
- effets de l'IA et de l'automatisation sur l'emploi : scénarios et non faits ;
- inégalités en agrégats mondiaux ;
- efficacité réelle de la « finance régénérative », des B-Corps et de l'ESG ;
- revenu de base et monnaies alternatives : expériences locales, pas de généralisation ;
- métriques ELYSIUM qui ne sont pas des indicateurs validés.

### 8. Structure rédactionnelle proposée (format B, 8 sections)
1. **P05.1 L'action comme condition de civilisation.** Définition et thèse du fondateur.
2. **P05.2 Six facettes, un champ d'action.**
3. **P05.3 Pathologies de l'agency.** Extraction, aliénation, financiarisation, posées comme diagnostics à sourcer.
4. **P05.4 Boucles et dépendances.**
5. **P05.5 Couplages inter-fondations.**
6. **P05.6 A.Agency et B.Economy** (ETF-0007, et ETF-S-003 différé).
7. **P05.7 De l'extraction à l'agency régénérative.** Leviers et chemins testables.
8. **P05.8 Signaux de santé et passage aux matrices de facettes.**

### 9. Corpus autorisé
- `ontology-map.md`, `EDITORIAL-SPINE-001.md`, `RELATION-REGISTRY.yaml` (ETF-0007, ETF-S-003) et `CANONICAL_FACET_ID_MAP` ;
- les matrices F03_01 à F03_06 (`RECOVERED_DRAFT_QA_PENDING`), seulement comme exemples qualifiés ;
- des sources à acquérir : économie du travail, histoire de la finance, littérature sur les communs.

Aucun import silencieux depuis les dépôts sources.

### 10. Critères de sortie
Le brief est prêt pour une gate de rédaction si les facettes sont bornées, ETF-0007 et ETF-S-003 sont distingués, les couches A et E sont visibles, les réserves sont écrites et la thèse du fondateur P05 est validée. Il faut aussi que Yannick autorise la prose.

### 11. Interdictions héritées
Ne pas modifier `P05_FOUNDATION_03_AGENCY.md`, l'ontologie, les taxonomies ni les matrices. Ne pas fermer ETF-S-003. Ne pas promouvoir au statut `CANONICAL`.

---

## B. Format canonique d'un chapitre de fondation (recommandation)

**Recommandation : 8 sections, environ 2 500 mots (fourchette de 2 000 à 3 500).**

Pourquoi :
- P03 et P04, qui sont déjà écrits, suivent ce format. Le garder évite de les réécrire.
- Les 12 étapes restent la **matrice conceptuelle** (couche A), sans devenir 12 titres. Une section peut couvrir plusieurs étapes, et le crosswalk le documente.
- La profondeur (de 8 000 à 15 000 mots) viendra en Phase 3 avec l'expansion des facettes, et pas dans le chapitre de fondation.
- Ton rythme d'écriture : un chapitre de 2 500 mots par semaine, assisté par IA, c'est faisable.

### Édition proposée pour `07-prompts/chapter-writing-template.md`
Remplacer le bloc final des fourchettes de mots par :
```
---
*Canonical foundation chapter format (decision YJ, à valider):*
- *8 editorial sections, ~2,500 words (range 2,000–3,500)*
- *The 12 sections above are the conceptual checklist (layer A), not mandatory headings;
  each must be covered or explicitly marked "deferred to facet matrix".*
- *Every chapter opens from its Founder Thesis (3–5 sentences, validated by YJ).*
- *Facet expansion modules (Phase 3): 1,500–2,500 words each.*
- *Long-form (8,000–15,000) reserved for P02 Ontology and P10 Synthesis only.*
```

### Édition proposée pour `00-meta/production-roadmap.md` (Phase 1)
```
## Phase 1 — Ontology Stabilization
- [x] Confirm 3 scales  (P02 v0.3, 2026-10-14)
- [x] Confirm 7 foundations  (P02 v0.3)
- [ ] Confirm exact 38 facets  → working list accepted for drafting; final lock at Phase 3
- [x] Confirm 12-step matrix  (12-STEP-LAYER-CROSSWALK-001)
- [ ] Founder theses P05–P09 validated
```

### Édition proposée pour `EDITORIAL-SPINE-001.md` (règle « No premature prose »)
Remplacer la ligne actuelle par :
```
| Gated prose | Foundation prose may start once (1) its diagnostic brief exists, (2) its Founder
Thesis is validated by Yannick, and (3) Phase 1 items scales/foundations/12-step are
checked. The 38-facet list may remain a working list. Drafts stay non_canonical until review. |
```
Et dans les interdictions des briefs, remplacer « ne pas lancer P05–P09 » par « ne pas lancer un chapitre sans brief et sans thèse validée ».

---

## C. Thèses du fondateur proposées (toutes à valider par Yannick)

Elles s'appuient sur ta quête et ta vision : comprendre la nature de la réalité par la science et par l'esprit, avec un regard non-duel ; transmettre et être un phare pour le monde nouveau ; ne pas viser une réforme, mais une maturation de la civilisation.

### P05 Agency (à valider par Yannick)
> Agency is not the economy; the economy is one channel through which human agency flows. Today that channel is captured by extraction: value is measured by what can be taken, not by what is made possible. A mature civilization measures wealth by the regenerated capacity of people and living systems to act. Work becomes the expression of a person's gift, finance becomes the circulatory system of that gift, and innovation serves life rather than capture. The transition does not start with a new ideology but with redirecting where value is recognized.

*Glose FR : l'agir humain précède l'économie. Aujourd'hui, la valeur se mesure à ce qu'on prélève. Demain, elle se mesurera à la capacité d'agir qu'on régénère, et le travail redeviendra l'expression d'un don.*

### P06 Cohesion (à valider par Yannick)
> Fragmentation is not primarily a social problem but a perceptual one: we experience ourselves as separate, and our societies mirror that belief. Polarization feeds on identity defended against others. Cohesion cannot be engineered by consensus alone; it grows where people recognize a shared ground beneath their differences. Culture and art are the organs through which a civilization remembers that ground. A regenerative society cultivates belonging without uniformity.

*Glose FR : la séparation sociale reflète une séparation intérieure. On ne fabrique pas la cohésion, on la laisse émerger du fond commun reconnu. L'art et la culture servent de mémoire de ce fond.*

### P07 Governance (à valider par Yannick)
> Our institutions were designed for a slower, smaller, more predictable world; their sclerosis is a mismatch of time-scales, not only of morals. Governance must learn to steer complex systems it cannot control. That requires anticipation, transparency and distributed responsibility rather than more central command. Legitimacy will come from serving the long-term flourishing of life, not from the next electoral cycle. Good governance is collective wisdom made operational.

*Glose FR : nos institutions sont lentes face à un monde rapide et complexe. Il faut piloter sans contrôler, en anticipant, de façon transparente et distribuée, au service du long terme.*

### P08 Vision (à valider par Yannick)
> Science has given us extraordinary power to describe matter, but a reductionist reading of it has left us without a map of meaning. The next step is not to abandon science but to complete it: to include the knower in the known, systems in place of parts, and consciousness as a legitimate field of inquiry. Education must form wise beings, not only useful workers. Technology, including AI, must be oriented by a vision of life worth living. Seeing clearly is the first act of transformation.

*Glose FR : ta quête scientifique. Il ne s'agit pas de rejeter la science mais de la compléter en y incluant celui qui observe, la vision systémique et la conscience. L'éducation doit former des sages, et l'IA doit servir la vie.*

### P09 Consciousness (à valider par Yannick)
> Every civilization rests on an answer to the question "what is real, and who are we?" Ours has answered "matter, and separate selves", and the meaning crisis is the logical consequence. The deepest leverage point is therefore a shift in worldview: recognizing awareness as the ground in which all experience, and all foundations, appear. This is not a new religion but a maturation, open to direct inquiry by anyone. When consciousness changes its self-understanding, every other foundation reorganizes around it.

*Glose FR : c'est ton cœur non-duel. La crise de sens découle d'une vision matérialiste et séparée. Le levier le plus profond est de reconnaître la conscience comme fond de toute chose : une maturation et non une religion, et le reste de la civilisation se réorganise autour.*

---

## D. Statut proposé pour ETF-S-003

**Proposition : `DEFERRED → SCOPED_DEFERRED`.** On garde la relation ouverte, avec une note de portée explicite :
```text
ETF-S-003  A.F03 Agency ↔ B.F01 Knowledge
relation_type = SECONDARY_CORRESPONDENCE
status = deferred (scoped)
scope_note = "Ground limited to A.F03_05 Innovation ↔ B.F01 (R&D, knowledge production).
             Education/science remain A.F06 Vision. Re-examine at P08 brief, close at Phase 3."
```
Pourquoi : P05 n'a besoin que de nommer la frontière avec Innovation, et la vraie décision dépend de P08 (Vision). Fermer la relation maintenant serait prématuré, alors que la laisser sans portée laisserait une ambiguïté.

---

## Décisions demandées à Yannick (oui ou non)
1. Brief P05 (A) : accepter tel quel ou l'ajuster.
2. Format de 8 sections et environ 2 500 mots (B), plus les trois éditions de texte.
3. Thèses P05 à P09 (C) : valider, réécrire ou dicter ta version.
4. ETF-S-003 en `SCOPED_DEFERRED` (D).
