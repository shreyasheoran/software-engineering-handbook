# Documentation inventory

A production-facing repository should contain the documents below before implementation starts. Mark an item **N/A** only with a written reason.

## Required

| Document | Purpose |
|---|---|
| Professional README | Problem, audience, demo, setup, architecture, evidence and limitations |
| Requirements or product brief | Scope, users, journeys, acceptance criteria and non-goals |
| System architecture | Components, boundaries, data flow and failure modes |
| Data/API contract | Runtime shapes, invariants, validation, compatibility and error behavior |
| Architecture Decision Records | Recorded context and consequences for consequential choices |
| Engineering principles | Non-negotiable quality, reliability, security and accessibility standards |
| Test strategy | Unit, integration, end-to-end, failure, accessibility and performance coverage |
| Threat model | Assets, trust boundaries, abuse cases and mitigations |
| Benchmark methodology | Environment, workload, sample size, metrics and analysis |
| Implementation status | What is verified, measured, provisional or deliberately unimplemented |
| Deployment runbook | Build, release, rollback, smoke checks and ownership |
| Operations runbook | Startup, health, common failures, recovery and escalation |
| Synthetic-data policy | Prohibitions and controls for portfolio data |
| Delivery checklist | Release gate for docs, code, tests, evidence and deployment |
| Contributing guide | Local workflow, commits, review, quality and release expectations |
| Security policy | Vulnerability reporting and supported versions |
| License | Usage terms |
| Dependency policy | Update, review, vulnerability and license expectations |

## Recommended proof set

- Evidence map linking résumé/GitHub claims to committed proof.
- Browser and environment capture for benchmarks.
- Screenshot set with viewport and version/date metadata.
- Accessibility review notes and keyboard test recording.
- Release notes and migration notes when public behavior changes.
