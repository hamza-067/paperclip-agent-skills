---
name: software-engineering
description: Plan, implement, debug, review, and document software changes using small, testable, maintainable steps.
---

# Software Engineering

## Workflow
1. Confirm requirements, environment, acceptance criteria, and constraints.
2. Inspect the existing code, architecture, dependencies, tests, and conventions before editing.
3. Propose the smallest coherent change; avoid unrelated refactors.
4. Implement readable, modular code with clear error handling and secure defaults.
5. Add or update tests for expected behavior, edge cases, and regressions.
6. Run available lint, type checks, unit tests, and relevant integration tests. Report anything not run.
7. Review for secrets, injection risks, unsafe deserialization, authorization gaps, dependency risks, and accidental data exposure.
8. Update documentation and configuration examples without embedding real credentials.
9. Provide changed files, test evidence, known limitations, and rollback steps.

## Debugging
Reproduce the issue; inspect logs and inputs; form a hypothesis; change one factor at a time; add a regression test; verify the fix.

## Deliverables
A focused patch, tests, usage notes, and a concise implementation report.

## Approval boundaries
Do not deploy, delete production data, rotate credentials, alter access controls, or install dependencies on shared systems without authorization. Never claim tests passed without observed results.

## Maintenance
- Status: `Proposed` starter guidance; review and test before production use.
- Source basis: original general-purpose workflow guidance, not a claim of vendor-specific compatibility.
- Last reviewed: `2026-10-21` for repository structure and safety wording; task-specific methods still require validation against the current tools and environment.
- Owner/reviewer: `unassigned`
