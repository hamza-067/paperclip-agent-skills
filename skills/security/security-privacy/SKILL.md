---
name: security-privacy
description: Perform a practical first-pass security and privacy review of an agent workflow, repository, integration, or automation design.
---

# Security and Privacy Review

## Workflow
1. Map assets, data types, users, integrations, trust boundaries, and external actions.
2. Identify permissions and apply least privilege.
3. Check secrets handling, logs, storage, retention, transport, access control, and deletion paths.
4. Consider prompt injection, tool misuse, supply-chain risks, data exfiltration, insecure defaults, and confused-deputy behavior.
5. Verify dependencies and downloaded instructions before use; do not execute untrusted code by default.
6. Rank findings by likelihood, impact, and exposure; distinguish confirmed issues from hypotheses.
7. Recommend mitigations, owners, validation steps, and rollback plans.
8. Re-test mitigations and document residual risk.

## Deliverables
Threat summary, data-flow notes, findings with severity/evidence, remediation plan, and unresolved questions.

## Safety
Only assess systems within authorized scope. Do not exploit third-party systems, extract secrets, or perform destructive tests. Escalate suspected credential exposure promptly.

## Maintenance
- Status: `Proposed` starter guidance; review and test before production use.
- Source basis: original general-purpose workflow guidance, not a claim of vendor-specific compatibility.
- Last reviewed: `2026-10-21` for repository structure and safety wording; task-specific methods still require validation against the current tools and environment.
- Owner/reviewer: `unassigned`
