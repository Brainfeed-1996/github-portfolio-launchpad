# Cloud Shipyard Trade-offs

## Control plane versus raw IaC usage
A control plane adds overhead, but it creates consistency, traceability, and reusable governance.

## Opinionated policy layer
Strong policies reduce accidental risk, but can frustrate teams if they are too rigid. The platform should support explainable denials and safe override paths.

## Central registry model
A registry improves visibility, but becomes a critical dependency that must stay reliable and understandable.

## Desired state and observed state separation
This separation increases conceptual complexity, but is necessary for drift handling and operator trust.
