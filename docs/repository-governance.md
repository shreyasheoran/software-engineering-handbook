# Repository governance

## Source of truth

The repository contains requirements, architecture, implementation, tests, runbooks, evidence and release history. Public claims must reconcile with committed repository evidence.

## Branch and commit policy

- Work on a focused branch.
- Keep commits logically isolated and reproducible.
- Use conventional commit prefixes for changes such as `docs`, `feat`, `fix`, `test`, and `ci`.
- Do not commit generated dependencies, secrets, private employer data, credentials or customer artifacts.

## Review policy

Every non-documentation change should receive review for:

- Requirements fit and scope
- Correctness and failure behavior
- Security and privacy
- Testability
- Accessibility
- Observability
- Operational impact
- Public claims and evidence

## Protected default branch

Require successful CI and at least one review for changes to the default branch. Keep history understandable; avoid destructive rewriting after review or release.

## Issue definitions

An issue should include outcome, acceptance criteria, constraints, risks and relevant evidence. Separate bugs, product work and documentation debt rather than mixing unrelated scope.

## Dependency ownership

Review dependency additions for license, maintenance, vulnerability, supply-chain and bundle impact. Prefer a small, maintained dependency set.

## Documentation ownership

Documentation is updated in the same change set as behavior. Stale documentation is treated as a delivery defect, not deferred polish.
