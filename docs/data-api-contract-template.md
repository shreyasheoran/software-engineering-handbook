# Data and API contract

## Ownership

Name the producer, consumer and source-of-truth owner.

## Version and compatibility

- Contract version:
- Backward-compatible change policy:
- Breaking-change policy:
- Deprecation period:

## Schema

Provide the authoritative fields, types, units, nullability and default values.

| Field | Type | Required | Meaning or unit | Validation |
|---|---|---:|---|---|

## Invariants

List properties every valid value or state must preserve.

## Validation

Define validation at trust boundaries and the behavior for malformed or unknown values.

## Errors

| Code/condition | Client-visible result | Retry | Telemetry |
|---|---|---|---|

## Ordering and delivery

Describe ordering, duplicates, replay, timestamps and eventual consistency.

## Pagination and limits

Define limits, cursor behavior, bounded retention and abuse controls.

## Data lifecycle

Define creation, update, retention, deletion and export behavior.

## Compatibility tests

Name fixtures, schema tests, consumer tests and migration checks.
