# Cloud Shipyard Architecture

## Overview

Cloud Shipyard is a control plane for infrastructure lifecycle management. It is designed to coordinate change requests, policy evaluation, IaC execution, environment state tracking, and operator visibility.

## Core subsystems

### 1. Environment registry
Maintains the canonical description of environments, ownership, metadata, quotas, lifecycle state, and desired infrastructure composition.

### 2. Change planner
Accepts user or pipeline requests, computes the intended change set, associates approvals or policy context, and prepares the execution plan.

### 3. Policy layer
Evaluates rules before execution, including naming conventions, ownership checks, quota limits, security controls, tagging requirements, and environment-specific guardrails.

### 4. IaC orchestration layer
Coordinates Terraform, Pulumi, or similar engines for plan, apply, destroy, and drift analysis workflows.

### 5. Drift and reconciliation engine
Compares desired state, recorded state, and observed provider state to identify divergence and trigger remediation or operator review.

### 6. Operator surfaces
Expose environment views, recent changes, audit traces, drift summaries, and policy decisions.

## Data flow

```text
request -> planner -> policy evaluation -> IaC execution -> state registry update -> operator views
```

## Key design priorities

- strong governance without making the platform unusable
- explicit lifecycle and ownership model
- auditability of infrastructure changes
- support for ephemeral and long-lived environments
- clear separation between requested, desired, and observed state
