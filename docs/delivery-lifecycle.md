# Documentation-first delivery lifecycle

Documentation defines the intended contract before code. Evidence reconciles the contract with reality before publication.

## 1. Frame the problem

Write the product brief and identify:

- Target user and goal
- Current pain and proposed outcome
- Success measure
- Explicit non-goals
- Risks, constraints and privacy boundary

## 2. Define the contract

Specify architecture, runtime data, APIs, accessibility, keyboard behavior, observability and failure states. Create ADRs for choices that are costly or difficult to reverse.

## 3. Establish quality gates

Document the test strategy, benchmark methodology, threat model and delivery checklist before implementation. Identify what must be automated versus reviewed manually.

## 4. Implement minimally

Implement only behavior covered by the contract. Prefer small slices that can be demonstrated and tested. Do not invent public performance or compliance claims.

## 5. Add evidence

Commit tests, benchmark output, screenshots, deployment evidence and implementation status. Report unknowns as unknowns.

## 6. Reconcile

Compare code and deployed behavior against requirements. Correct both mismatches and unsupported claims. The implementation status document is the final reconciliation record.

## 7. Review and release

Run the clean build, full relevant test set, threat review, accessibility review and deployment smoke checks. Publish only after every required checklist item is complete or explicitly accepted as an N/A exception.

## 8. Maintain

Update documentation and evidence with behavior-changing releases. Remove stale claims before they become recruiter-facing misinformation.
