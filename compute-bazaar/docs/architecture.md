# Compute Bazaar Architecture

## Overview

Compute Bazaar is structured around resource inventory, workload descriptions, placement logic, execution accounting, and fairness-oriented scheduling.

## Core subsystems

### 1. Resource registry
Tracks available compute nodes, hardware types, quotas, and capacity metadata.

### 2. Workload model layer
Represents job requirements, runtime characteristics, priority, and placement constraints.

### 3. Scheduler
Matches workloads to resources according to availability, fairness rules, placement constraints, and optimization goals.

### 4. Accounting layer
Records resource consumption, usage ownership, and settlement-oriented metrics.

### 5. Operator and marketplace views
Expose fleet state, queue pressure, placement outcomes, and resource demand patterns.

## Design priorities

- explicit resource modeling
- fairness and quota awareness
- explainable placement decisions
- support for heterogeneous infrastructure
