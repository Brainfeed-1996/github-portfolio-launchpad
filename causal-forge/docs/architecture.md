# Causal Forge Architecture

## Overview

Causal Forge is organized around causal graph definitions, intervention models, inference workflows, scenario comparison, and decision-facing explanation surfaces.

## Core subsystems

### 1. Causal model layer
Represents variables, directed dependencies, confounders, assumptions, and structural relationships.

### 2. Intervention engine
Applies hypothetical changes to the graph and evaluates outcome shifts under defined assumptions.

### 3. Counterfactual workflow layer
Supports what-if reasoning for observed cases and scenario-specific decision analysis.

### 4. Sensitivity analysis layer
Measures how conclusions change when assumptions or parameter estimates move.

### 5. Presentation layer
Exposes graph views, intervention results, explanation traces, and comparison outputs.

## Design priorities

- explicit assumptions
- explainable simulation outputs
- reproducibility of analysis scenarios
- clean separation between model definition and decision consumption
