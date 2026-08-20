# Connector-first delivery workflow

## Operating boundary

The ChatGPT Pro GitHub connector is the sole discovery and context path for the
web workflow. GitHub is the durable ledger. Codex may execute code changes and
publish authorized results, but task context must not depend on a private chat,
local-only file, or Project-only field.

## Issue contract

An executable issue contains:

1. **Outcome** — the observable change.
2. **Context** — why it matters and links to authoritative specifications.
3. **Scope** — explicit in-scope and out-of-scope boundaries.
4. **Acceptance criteria** — observable completion checks.
5. **Validation** — exact commands, runtimes, or evidence required.
6. **Relationships** — native parent, sub-issues, blockers, and typed links.
7. **Delivery** — owning repository, artifact, base branch, and publication boundary.

Roadmaps and Epics coordinate executable sub-issues. A Task, Bug, Feature, or
Gate should normally fit one primary pull request.

## Readiness

Project Readiness is a visual projection of issue evidence:

- `Ready` — the issue contract is complete and native blockers are clear.
- `Needs decision` — a human product or architecture choice is missing.
- `Needs specification` — expected behavior or boundaries are incomplete.
- `Needs reproduction` — a reported failure lacks reliable reproduction.
- `Needs access` — execution requires unavailable credentials, repositories,
  environments, or approvals.

The reason must be stated in the issue. The field alone is not evidence.

## Work record

When work starts, record the agent or person, base SHA, intended scope,
validation plan, and material assumptions. Scope or architecture changes are
written back to the issue or a versioned decision document.

## Pull-request contract

Every implementation pull request contains one canonical Primary issue URL,
changes and reasons, commands actually run and their outcomes, inspectable
evidence, compatibility and risk notes, dependency links, and remaining work.

Use `Closes` only for complete delivery. Use `Advances` for partial delivery or
an Epic contribution.

## Completion and parking

Close completed work as completed. Close deferred work as not planned with a
reason and a concrete return condition. Reopening parked work returns it to
review: refresh the issue contract and readiness before execution resumes.
