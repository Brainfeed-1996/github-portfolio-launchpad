# Graph Atelier Architecture

## Overview

Graph Atelier is built around typed entities, relationship indexes, traversal execution, update propagation, and projection layers for graph-native workloads.

## Core subsystems

### 1. Graph model layer
Defines node, edge, label, property, and identity semantics.

### 2. Storage and index layer
Supports adjacency-oriented access patterns, lookup indexes, and relationship traversal efficiency.

### 3. Traversal engine
Executes path expansion, neighborhood search, filtering, scoring, and bounded exploration.

### 4. Entity resolution layer
Handles merge candidates, identity confidence, conflict resolution, and provenance.

### 5. Projection layer
Creates materialized views or subgraphs for operational and analytical use cases.

## Design priorities

- explicit relationship semantics
- efficient neighborhood access
- explainable entity merge behavior
- clear distinction between raw graph truth and derived projections
