# Meridian DB Trade-offs

## B-tree versus LSM direction
B-trees simplify some read paths, while LSM designs can improve write throughput. The right choice depends on the workload story the project wants to tell.

## Simplicity versus realism
A simpler engine is easier to understand and explain, but overly simplifying can weaken the signal of the project.

## Snapshot semantics
Even a simplified concurrency model should remain explicit. Hidden assumptions here make the project much less credible.
