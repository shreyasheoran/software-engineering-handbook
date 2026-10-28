# Software Engineering Handbook

A practical operating system for designing, documenting, testing, measuring, shipping and reviewing software as a single engineer.

## Purpose

This repository makes engineering decisions referenceable and proof-producing. It is intentionally tool-light, versioned, and reusable across frontend, backend, data, security and AI projects.

## Principles

1. **Measure before optimizing.** Every performance claim has methodology and raw evidence.
2. **Design for failure.** Backpressure, retries, timeouts, idempotency and recovery are first-class requirements.
3. **Ship accessible by default.** Keyboard interaction, semantics and contrast are part of quality—not QA polish.
4. **Document irreversible decisions.** Architecture Decision Records capture context, options and consequences.
5. **Prefer observability over assumptions.** Logs, traces and metrics answer questions in production.
6. **Make the repository the source of truth.** Setup, architecture, operations and trade-offs live beside the code.
7. **Use synthetic data by default.** Employer, customer and production secrets never enter portfolio repositories.
8. **Automate critical evidence.** CI, tests, benchmarks, security checks and deployments produce repeatable proof.

## Engineering loop

```
Problem → evidence → design → implementation → tests → benchmark → review → release
```

## Required repository artifacts

- Professional README with problem, demo, architecture and results
- Architecture overview
- Architecture Decision Records
- Threat model for security-sensitive features
- Runbook and rollback procedure
- Reproducible setup with containers or scripts
- CI for build, lint, unit, integration and accessibility checks
- Benchmark report with environment and methodology
- Security policy, license and dependency policy
- Issue and pull-request templates

## Engineering standards

### Delivery

- Small pull requests tied to a user or engineering outcome
- Conventional commits
- Semantic versioning for libraries and APIs
- Release notes and migration notes
- No direct commits to protected main branches

### Testing

- Unit tests for isolated behavior
- Integration tests at system boundaries
- End-to-end tests for critical workflows
- Concurrency and backpressure tests for real-time systems
- Accessibility checks with keyboard and screen-reader workflows
- Failure injection for retries, timeouts and partial outages

### Performance

- State an SLO and a percentile—not only an average
- Record hardware, environment, dataset and run count
- Compare with a baseline
- Publish methodology and interpretation
- Avoid benchmark claims from uncontrolled browser sessions

### Security

- Secrets excluded and rotated
- Dependencies pinned and monitored
- Input validation at trust boundaries
- Least-privilege service access
- Prompt-injection and retrieval controls for LLM systems
- Synthetic datasets in public demonstrations

## SDE II proof rubric

An engineering artifact should demonstrate several of these qualities:

- Clear ownership and ambiguous problem framing
- Cross-layer implementation
- Production scale or realistic load
- Reliability and recovery
- Security and privacy controls
- Accessibility
- Observability
- Benchmarks and trade-offs
- Mentoring or review leadership
- Maintainable documentation and operations

## Project templates

- [Frontend systems](docs/frontend-systems.md)
- [Distributed services](docs/distributed-services.md)
- [Architecture decisions](docs/architecture-decision.md)
- [Benchmark report](docs/benchmark-report.md)
- [Security review](docs/security-review.md)

## 2026 portfolio focus

1. Publish and package `use-batched-ring-buffer`.
2. Build a realistic real-time security operations dashboard.
3. Harden SecOps-LLM with reproducible retrieval evaluation and threat controls.
4. Convert engineering work into architecture decisions, benchmarks and technical writing.

> This handbook documents proof-producing engineering rather than claims without evidence.