# Pixel Pipeline Trade-offs

## Quality versus latency versus cost
Media systems almost always live on this triangle. The architecture should make the trade visible, not hide it.

## Heavy caching
Caching can cut cost dramatically, but complicates invalidation and storage management.

## Resource specialization
GPU-aware execution improves throughput for some workloads, but increases scheduling complexity and operational constraints.
