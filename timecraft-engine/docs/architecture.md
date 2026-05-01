# Timecraft Engine Architecture

## Overview

Timecraft Engine is a discrete-event simulation platform organized around event scheduling, resource contention, dependency graphs, scenario replay, and comparative timeline analysis.

## Core subsystems

### 1. Event model layer
Represents actions, durations, dependencies, and resource requirements.

### 2. Timeline scheduler
Advances simulated time and coordinates event execution according to ordering and readiness constraints.

### 3. Resource contention layer
Models queues, bottlenecks, delays, and competing access to shared capacity.

### 4. Replay and comparison layer
Stores scenario runs for repeatable study and side-by-side outcome analysis.

### 5. Visualization layer
Presents timelines, bottlenecks, critical paths, and scenario deltas.

## Design priorities

- deterministic replay
- explainable timing behavior
- support for what-if comparisons
- clean separation between simulation logic and presentation
