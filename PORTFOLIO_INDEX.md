# Portfolio Index

Index global des projets du portfolio, avec leur positionnement, leur niveau de ROI, leur langage principal recommandé, et leur angle de différenciation.

## Objectif

Éviter les doublons, garder une couverture maximale des domaines de l’informatique, et faire en sorte que chaque dépôt raconte une histoire différente en entretien.

---

## Projets existants ou déjà définis

| Projet | Domaine | Langage recommandé | Signal principal | Risque de doublon |
|---|---|---|---|---|
| adversary-forge | AI security, LLM evaluation | TypeScript + Python | sécurité IA, benchmarks, évaluateurs | Faible |
| sentinel-fabric | security platform | Go + TypeScript | control plane sécurité, graph posture | Faible |
| orchestra-mesh | workflow engine | Rust ou Go | systèmes distribués, durabilité | Faible |
| atlas-delta | data platform | Python + TypeScript | lineage, qualité, serving | Faible |
| quantum-ledger | fintech systems | Rust | cohérence transactionnelle, ledger | Faible |
| kernel-sentinel | low-level systems security | Rust + C | tracing runtime, observabilité OS | Très faible |
| pixel-pipeline | media systems | C++ ou Rust | perf, scheduling, processing | Très faible |
| compiler-garden | compilers | Rust ou OCaml | parsing, IR, VM, type systems | Très faible |
| graph-atelier | graph infra | Java ou Rust | graph analytics, reasoning | Faible |
| cloud-shipyard | cloud platform | Go | IaC orchestration, policy gates | Faible |
| bio-signal-lab | scientific computing | Python + Rust | signal processing, streaming | Très faible |
| formal-foundry | formal methods | Haskell/OCaml/Rust | invariants, verification | Très faible |
| meridian-db | storage engine | Rust ou C++ | indexation, MVCC, recovery | Très faible |
| packet-weaver | networking | Rust, C, ou Go | protocoles, transport, congestion | Très faible |
| servo-grid | robotics / edge | C++ ou Rust | temps réel soft, coordination edge | Très faible |
| model-foundry | ML systems | Python | training, eval, registry, serving | Faible |
| interface-weave | front-end architecture | TypeScript | design systems, rendering, state graph | Faible |

---

## Top 8 recommandé pour un GitHub ultra sélectif

Si le but est d’impressionner fortement sans diluer le signal, la meilleure sélection est:

1. `adversary-forge`
2. `orchestra-mesh`
3. `compiler-garden`
4. `kernel-sentinel`
5. `quantum-ledger`
6. `sentinel-fabric`
7. `meridian-db`
8. `atlas-delta`

### Pourquoi ce top 8 est fort

- couvre sécurité, systèmes distribués, compilos, bas niveau, fintech, stockage, data platform
- très peu de redondance
- très bon équilibre entre sujets à la mode et sujets fondamentaux
- énorme matière pour des entretiens staff/principal-level

---

## Si tu veux maximiser la diversité par langage

- **TypeScript:** adversary-forge, interface-weave
- **Go:** sentinel-fabric, cloud-shipyard
- **Rust:** orchestra-mesh, quantum-ledger, kernel-sentinel, meridian-db, packet-weaver
- **Python:** atlas-delta, bio-signal-lab, model-foundry
- **C++:** pixel-pipeline, servo-grid
- **OCaml / Haskell:** compiler-garden ou formal-foundry
- **Java:** graph-atelier

---

## Grands domaines couverts

### Sécurité
- adversary-forge
- sentinel-fabric
- kernel-sentinel

### Systèmes distribués et backend critique
- orchestra-mesh
- quantum-ledger
- meridian-db
- packet-weaver

### Data, ML, scientific computing
- atlas-delta
- model-foundry
- bio-signal-lab
- graph-atelier

### Langages, outils, vérification
- compiler-garden
- formal-foundry

### Cloud, infra, edge, interfaces
- cloud-shipyard
- servo-grid
- interface-weave
- pixel-pipeline

---

## Règle d’or avant de créer un nouveau dépôt

Ne créer un nouveau repo que s’il ajoute au moins une de ces choses:

- un domaine fondamental non encore représenté
- un paradigme d’architecture non encore représenté
- un langage où tu veux explicitement montrer de la profondeur
- une difficulté technique qui n’est pas déjà démontrée ailleurs

Sinon, mieux vaut renforcer un repo existant.

---

## Recommandation honnête

Le vrai ROI n’est pas dans la quantité maximale. Il est dans:

- la qualité perçue
- la profondeur technique
- la diversité intelligente
- la cohérence d’ensemble
- la capacité à transformer chaque repo en preuve de niveau senior à principal

Un portfolio de 6 à 10 dépôts exceptionnels vaut largement mieux que 25 dépôts qui se recouvrent.
