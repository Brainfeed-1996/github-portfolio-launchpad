# Packet Weaver Trade-offs

## Protocol simplicity versus feature richness
A smaller protocol is easier to reason about, but may limit performance and flexibility.

## Retransmission aggressiveness versus network pressure
Faster recovery improves latency in some cases, but can worsen congestion and fairness.

## Strong observability
Detailed tracing helps development and debugging, but can distort performance measurements if always enabled.
