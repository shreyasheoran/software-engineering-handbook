# Distributed Services Checklist

## Reliability

- Timeouts and deadlines
- Bounded retries with jitter
- Idempotency keys
- Cancellation propagation
- Backpressure
- Circuit or overload protection
- Crash recovery and replay semantics

## Data correctness

- Delivery and ordering assumptions
- Duplicate and out-of-order handling
- Transaction boundaries
- Schema compatibility
- Reconciliation procedure

## Operations

Define health, readiness, capacity, latency, error rate and saturation signals. Provide a runbook and rollback procedure.