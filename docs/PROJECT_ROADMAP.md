# Project Roadmap

## Priority model

Each project is scored on:

- recruiter signal
- technical depth
- business usefulness
- originality
- documentation potential
- compounding reuse across future work

## Flagship Project 1, Security Control Plane

### Working title
Sentinel Fabric

### Concept
A security operations and exposure management platform that unifies asset inventory, attack surface mapping, secret leak detection, misconfiguration analysis, lightweight threat correlation, and remediation workflows.

### Why it is strong

- matches your cybersecurity identity directly
- demonstrates backend, data, infra, and security engineering
- can evolve into a serious SaaS-style architecture
- extremely legible to recruiters

### Ideal stack

- Rust or Go backend services
- Python analysis workers
- TypeScript frontend
- Postgres
- ClickHouse or OpenSearch for events
- Docker Compose, then Kubernetes manifests
- OpenTelemetry

### High-value features

- asset graph
- credential and secret exposure scanning
- cloud configuration posture checks
- attack path modeling
- rule engine for detections
- remediation playbooks
- plugin SDK
- tenant isolation design

## Flagship Project 2, AI Red Team and Defense Lab

### Working title
Adversary Forge

### Concept
A framework for evaluating LLM applications and agentic systems against prompt injection, data exfiltration, tool abuse, jailbreaks, policy evasion, and agent workflow compromise.

### Why it is strong

- timely and high-value
- aligns cybersecurity with AI
- attractive to frontier labs and platform companies
- enables papers, benchmarks, and demos

### High-value features

- attack scenario packs
- replayable evaluation harness
- policy compliance scoring
- tool-call abuse simulation
- memory poisoning tests
- benchmark dashboards
- model-to-model comparison
- red/blue team mode

## Flagship Project 3, Distributed Workflow Engine

### Working title
Orchestra Mesh

### Concept
A developer-focused workflow and orchestration engine for long-running, stateful, event-driven automation with strong auditability and failure recovery.

### Why it is strong

- demonstrates systems design and platform engineering
- broadly useful beyond security
- excellent for architecture discussions in interviews
- can connect with AI agents, security workflows, and operations automation

### High-value features

- durable execution model
- event sourcing or append-only history
- retries and compensation
- DAG and state machine support
- human approval gates
- pluggable storage backends
- observability and replay

## Supporting Projects

### 1. Cloud Misconfiguration DSL
A domain-specific language and engine for expressing cloud security rules and policy-as-code checks.

### 2. Binary and Protocol Analysis Toolkit
A modular toolkit for packet, protocol, and binary introspection with parsers, signatures, and visualization.

### 3. Secure Developer Workstation Bootstrapper
Cross-platform security hardening and developer environment bootstrap automation.

### 4. Privacy-Preserving Analytics Pipeline
A data pipeline with differential privacy inspired controls, lineage, and auditable transformations.

### 5. Incident Graph Explorer
Graph-based incident correlation and root-cause exploration UI.

### 6. Multi-agent Evaluation Sandbox
A safe sandbox for evaluating agent workflows, permissions, tool access, and failure modes.

### 7. High-performance API Gateway Template
A production-grade gateway template with auth, rate limiting, telemetry, and policy hooks.

### 8. Full-stack Collaboration Product
A real application with auth, billing simulation, offline sync, observability, and role-based access control.

## Compact Repositories

- yara and sigma utilities
- malware config extractor examples
- browser security lab
- wasm sandbox experiments
- benchmarking harnesses
- code property graph experiments
- static analysis rulesets
- CI security templates
- API fuzzing examples

## Delivery order

### Phase 1

- portfolio standards
- GitHub profile repo
- Sentinel Fabric scaffold
- Adversary Forge scaffold

### Phase 2

- Orchestra Mesh scaffold
- 2 supporting projects
- documentation system and diagrams

### Phase 3

- benchmarks
- demos
- seeded issues
- contribution workflows
- content polish

## Recommendation

Start by building two flagship repos in parallel:

- Sentinel Fabric for direct recruiter signal
- Adversary Forge for modern differentiation
