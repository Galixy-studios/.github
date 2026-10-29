# Contributing to Galaxy Studios

## Working agreement

1. Create or reference a GitHub Issue describing the change and acceptance criteria.
2. Work on a short-lived branch: `feature/<issue>-description`, `fix/<issue>-description`, or `docs/<issue>-description`.
3. Use descriptive commits, preferably `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, or `chore:`.
4. Keep pull requests focused. Explain changes, tests, risks, and documentation updates.
5. Request review when another maintainer is available. Do not merge failing builds or unresolved review concerns.
6. Merge to `main` only when required checks pass. Production release approval is separate from merging.

## Definition of done

- Acceptance criteria are met.
- Relevant tests pass and test evidence is recorded.
- Security and privacy implications are considered.
- README, API documentation, or runbooks are updated if behavior changed.
- A reviewer approves where required; changes are merged to the intended branch.

## Project tracking

Recommended issue statuses: `Backlog`, `Todo`, `In Progress`, `In Review`, `Testing`, `Done`.
These are GitHub Projects fields, not labels or runtime health indicators. Update status as work progresses; `Done` means accepted, not necessarily deployed.

## Deployment and security

- Store secrets in approved secret management or deployment environment settings, never Git.
- Use separate development/staging/production settings where relevant.
- Pin dependency and container image versions where practical.
- Record deployment outcome and rollback steps for production changes.
- Never deploy private client code to infrastructure without authorization.
