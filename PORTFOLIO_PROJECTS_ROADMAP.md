# Portfolio Projects Roadmap

Ce document sert de plan d’ensemble pour éviter les doublons sur GitHub et maximiser le signal envoyé aux recruteurs très sélectifs.

## Principes de sélection

Chaque projet doit remplir au moins trois critères:

- démontrer une compétence technique difficile à faker
- se différencier nettement des autres dépôts
- ouvrir une conversation forte en entretien système, architecture, sécurité, perf, ou produit technique
- pouvoir être présenté avec une architecture crédible, une roadmap, des trade-offs, et des cas d’usage réels

## Projets déjà positionnés

### 1. adversary-forge
**Domaine:** AI security, LLM red-teaming, evaluation systems

**Signal principal:** sécurité appliquée aux systèmes IA, méthodologie d’évaluation, architecture d’outillage.

### 2. sentinel-fabric
**Domaine:** security platform engineering, exposure management, graph reasoning

**Signal principal:** architecture de plateforme sécurité, modèles de données riches, workflows opérateurs.

### 3. orchestra-mesh
**Domaine:** distributed systems, workflow engines, durability

**Signal principal:** orchestration fiable, event sourcing, failure handling.

### 4. atlas-delta
**Domaine:** data engineering, lineage, serving, quality

**Signal principal:** plateforme data opérationnelle, fiabilité, gouvernance des datasets.

## Nouveaux projets recommandés, sans doublon

### 5. quantum-ledger
**Domaine:** fintech infrastructure, distributed consistency, settlement

**Pourquoi il est différent:** focus sur les invariants financiers, les journaux append-only, le rapprochement et la correction comptable.

### 6. kernel-sentinel
**Domaine:** systems security, kernel-adjacent observability, runtime telemetry

**Pourquoi il est différent:** va beaucoup plus bas niveau, proche OS, eBPF, syscall tracing, forensic pipelines.

### 7. pixel-pipeline
**Domaine:** media systems, distributed compute, performance engineering

**Pourquoi il est différent:** centré sur les pipelines lourds, scheduling, GPU, coûts et qualité média.

### 8. compiler-garden
**Domaine:** compiler and language tooling

**Pourquoi il est différent:** profondeur algorithmique, AST, IR, optimisation, diagnostics, VM ou backend.

### 9. graph-atelier
**Domaine:** graph infrastructure, analytics, knowledge systems

**Pourquoi il est différent:** projet graph générique, utile pour search, fraud, reco, knowledge graphs.

### 10. cloud-shipyard
**Domaine:** platform engineering, IaC, deployment control planes

**Pourquoi il est différent:** montre la maîtrise de l’infra moderne, des environnements et des politiques de changement.

### 11. bio-signal-lab
**Domaine:** signal processing, scientific computing, streaming analytics

**Pourquoi il est différent:** ajoute du calcul scientifique et temps réel, rare dans un portfolio classique.

### 12. formal-foundry
**Domaine:** formal methods, correctness, verification

**Pourquoi il est différent:** très rare, très sélectif, énorme signal de rigueur.

## Répartition recommandée par langage

Pour éviter l’effet “je fais toujours la même chose”, la vitrine GitHub doit montrer une distribution crédible:

- **TypeScript:** interfaces, control planes, SDK, web consoles
- **Go:** services cloud, workers, orchestration, APIs performantes
- **Rust:** engines critiques, perf, sécurité, toolchains, runtimes
- **Python:** analyse, data, simulation, notebooks de validation, bindings
- **C/C++:** bas niveau, media, systèmes, compiler backends
- **OCaml/Haskell/Zig/Julia** selon le projet, seulement quand le choix est justifié

## Ordre de priorité ROI

Si l’objectif est de maximiser l’impact recrutement sans disperser l’énergie:

1. **Adversary Forge**
2. **Orchestra Mesh**
3. **Compiler Garden**
4. **Kernel Sentinel**
5. **Sentinel Fabric**
6. **Quantum Ledger**
7. **Atlas Delta**
8. **Formal Foundry**
9. **Cloud Shipyard**
10. **Pixel Pipeline**
11. **Graph Atelier**
12. **Bio Signal Lab**

## Règles anti-doublon

Avant de lancer un nouveau dépôt, vérifier:

- le problème métier est-il distinct?
- l’architecture principale est-elle distincte?
- le “hero story” du repo en entretien est-il distinct?
- le langage principal et la difficulté mise en avant sont-ils distincts?
- le dépôt montre-t-il une facette différente de l’ingénierie?

Si la réponse est non à plusieurs de ces questions, le projet est probablement redondant.

## Ce qu’un excellent dépôt doit contenir

Même si le code est déjà fini, la documentation doit systématiquement inclure:

- vision claire du problème
- architecture globale
- sous-systèmes et responsabilités
- trade-offs et ADRs
- cas d’usage réels
- modèle de données ou d’exécution
- risques, limites, sécurité
- roadmap crédible
- raisons pour lesquelles le projet est difficile et intéressant

## Recommandation globale

Le bon angle n’est pas “faire beaucoup de projets”, c’est “faire un portfolio impossible à confondre avec celui d’un simple full-stack généraliste”.

Ici, la meilleure stratégie est un portefeuille de projets:

- chacun premium
- chacun techniquement distinct
- chacun racontable en entretien
- chacun assez documenté pour paraître pensé par un ingénieur senior, pas bricolé pour GitHub
