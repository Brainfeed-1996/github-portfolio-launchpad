# Meridian DB

Storage engine and database systems project focused on indexing, logging, snapshots, recovery, concurrency, and query execution fundamentals.

Meridian DB is a high-signal systems project designed to demonstrate deep engineering capability in one of the most respected areas of software infrastructure: data storage correctness and performance. It treats a database not as a generic app backend, but as a carefully layered engine with explicit constraints, recovery semantics, and architectural trade-offs.

---

## Why this project matters

Database and storage projects reveal a lot about an engineer because they force clear thinking around:

- persistence
- crash safety
- concurrency
- indexing
- isolation
- query behavior
- recovery correctness

Meridian DB exists to make those concerns concrete through a compact but conceptually serious storage engine.

## What this project demonstrates

- storage engine architecture
- write path and recovery design
- indexing structures
- transaction and snapshot semantics
- benchmark-driven reasoning
- data durability trade-offs

## Core capabilities

- page and segment storage model
- WAL or append journal
- B-tree or LSM-backed indexing
- point lookups and range scans
- snapshot reads and simplified MVCC
- recovery and restart semantics
- benchmark harness for throughput and latency

## Why it stands out in a portfolio

A good database-engine project is one of the clearest signals of strong systems and backend talent. It shows rigor, taste, and comfort with difficult technical boundaries.

## Suggested stack

- Rust or C++
- benchmark harness with repeatable workloads
- optional SQL-like query layer for ergonomics

## Documentation

- `docs/architecture.md`
- `docs/roadmap.md`
- `docs/tradeoffs.md`

## License

Apache-2.0
