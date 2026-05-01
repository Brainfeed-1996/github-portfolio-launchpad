# Cloud Shipyard

Infrastructure lifecycle control plane for multi-environment cloud delivery, IaC orchestration, policy enforcement, drift detection, and platform governance.

Cloud Shipyard is a portfolio-grade platform engineering project designed to show how modern infrastructure can be managed as a coherent product rather than a collection of scripts, pipelines, and ad hoc dashboards. It focuses on environment creation, change governance, release safety, visibility, and the operational discipline required by serious cloud-native organizations.

---

## Why this project matters

Many engineering organizations claim to have platform maturity while still relying on fragile combinations of:

- Terraform wrappers
- CI/CD scripts
- manual approvals in chat
- undocumented environment conventions
- inconsistent policy enforcement
- weak drift visibility

Cloud Shipyard exists to model infrastructure operations as a first-class control plane problem.

## What this project demonstrates

- platform engineering and internal developer platforms
- cloud control-plane architecture
- IaC lifecycle orchestration
- policy and governance design
- deployment safety and environment management
- multi-team operational modeling

## Core capabilities

- environment templates and lifecycle contracts
- infrastructure plan and apply orchestration
- policy gates before change execution
- drift detection and reconciliation workflows
- preview environments and teardown automation
- ownership, quota, cost, and metadata governance
- audit trail for infrastructure changes

## Architecture at a glance

```text
developer request / platform API
             |
             v
   environment and change planner
             |
   +---------+----------+----------------+
   |                    |                |
   v                    v                v
policy evaluation   IaC orchestration   drift detection
   |                    |                |
   +---------+----------+----------------+
             |
             v
     state registry and operator views
```

## Why it stands out in a portfolio

Cloud Shipyard shows the difference between “I know DevOps tools” and “I can design a platform that governs infrastructure safely at scale”. That is a much stronger signal for selective platform, SRE, cloud, and internal tooling teams.

## Suggested stack

- Go for the control plane
- Terraform or Pulumi integration layer
- PostgreSQL for registry and workflow state
- TypeScript for operator and self-service surfaces

## Documentation

- `docs/architecture.md`
- `docs/roadmap.md`
- `docs/tradeoffs.md`

## License

Apache-2.0
