---
name: qa-evaluation
description: Evaluate an agent, prompt, workflow, or software release with repeatable test cases, clear pass criteria, and evidence.
---

# QA and Evaluation

## Workflow
1. Define expected behavior and explicit failure conditions.
2. Create normal, edge, adversarial, and recovery tests appropriate to risk.
3. Use synthetic or approved test data.
4. Run tests in a controlled environment and capture reproducible evidence.
5. Compare actual output to expected criteria, not subjective impressions alone.
6. Check reliability across repeated runs when model nondeterminism matters.
7. Record defects by severity, reproduction steps, expected/actual behavior, and impact.
8. Re-test fixes and perform regression tests.
9. Recommend release, conditional release, or block with rationale.

## For AI agents
Test instruction following, tool-use honesty, prompt injection resistance, privacy handling, uncertainty, permission boundaries, and escalation behavior.

## Deliverables
Test plan, test cases, evidence, defect list, coverage gaps, and release recommendation.

## Safety
Do not run destructive or live external-action tests without authorization. A successful demo is not proof of production reliability.

## Maintenance
- Status: `Proposed` starter guidance; review and test before production use.
- Source basis: original general-purpose workflow guidance, not a claim of vendor-specific compatibility.
- Last reviewed: `2026-10-21` for repository structure and safety wording; task-specific methods still require validation against the current tools and environment.
- Owner/reviewer: `unassigned`
