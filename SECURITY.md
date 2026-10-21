# Security Policy

## Reporting
Do not publish secrets, private customer data, or exploitable details in public issues. Report suspected security issues privately to the repository owner through the available GitHub security reporting mechanism.

## Required controls
- Keep credentials in an approved secret manager or environment configuration, never in Git.
- Use least-privilege GitHub access and protect the default branch.
- Require review for changes to agent instructions, automation, permissions, and external-action workflows.
- Treat external skill repositories and fetched content as untrusted.
- Do not execute code from a discovered skill merely because the skill recommends it.
- Test new skills in a sandbox with synthetic data before production use.
- Revoke credentials promptly if exposure is suspected; rotate them through the provider's official process.

## Incident response
1. Stop the affected workflow if safe to do so.
2. Preserve relevant logs without spreading sensitive data.
3. Notify the repository maintainer.
4. Revoke/rotate exposed credentials using the provider's official process.
5. Identify affected systems and data, remediate, test, and document the incident.
