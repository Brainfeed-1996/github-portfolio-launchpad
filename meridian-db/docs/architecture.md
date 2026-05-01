# Meridian DB Architecture

## Overview

Meridian DB is structured around a storage engine, write path, index maintenance, recovery logic, and snapshot-aware read execution.

## Core subsystems

### 1. Storage layer
Manages pages, segments, allocation, and durable layout on disk.

### 2. Write path
Coordinates mutation validation, logging, page updates, and commit visibility.

### 3. Index layer
Maintains primary lookup structures such as B-trees or LSM-inspired components.

### 4. Recovery layer
Reconstructs consistent state after restart from the WAL or append journal.

### 5. Read path
Supports point lookups, range queries, and snapshot-consistent reads.

## Design priorities

- crash recoverability
- explicit write ordering
- understandable concurrency model
- measurable read and write behavior
- clean boundary between logical data model and storage representation
