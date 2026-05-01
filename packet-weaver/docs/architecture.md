# Packet Weaver Architecture

## Overview

Packet Weaver is organized around transport sessions, packet scheduling, retransmission logic, congestion or flow heuristics, and simulation-driven validation.

## Core subsystems

### 1. Session manager
Maintains logical connection state, peer metadata, timers, sequence tracking, and stream coordination.

### 2. Packet engine
Encodes, decodes, validates, and dispatches packets according to protocol rules.

### 3. Reliability layer
Handles acknowledgements, retransmission, reordering, duplication control, and delivery guarantees.

### 4. Multiplexing layer
Supports multiple logical streams over a shared session while preserving fairness and ordering semantics as defined by the protocol.

### 5. Simulation harness
Introduces loss, latency, jitter, and reordering to validate behavior under degraded conditions.

## Design priorities

- explicit protocol state
- measurable transport behavior
- strong observability for debugging
- clear isolation between session logic and simulation tooling
