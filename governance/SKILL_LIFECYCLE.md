# Skill Lifecycle

## Statuses
- **Proposed:** drafted, not approved for operational use.
- **Review:** source and safety review in progress.
- **Tested:** acceptance tests passed in a controlled environment.
- **Approved:** maintainer accepted it for approved use.
- **Deprecated:** retained for history but should no longer be selected.
- **Rejected:** unsuitable; do not use.

## Required lifecycle
1. Discover a repeatable capability gap.
2. Search the library for existing coverage.
3. Gather primary sources and record checked dates.
4. Draft with the standard template.
5. Review source quality, security, privacy, licensing, and overlap.
6. Test using normal, edge, and failure scenarios.
7. Obtain human approval proportional to risk.
8. Merge, index, and changelog the skill.
9. Monitor failures and update when sources or tools change.

## Review cadence
- High-risk skills: review before each production adoption and at least quarterly.
- Medium-risk skills: review at least every six months or after a major tool change.
- Low-risk skills: review annually or when a source becomes stale.
- Any skill implicated in an incident must be reviewed immediately.

## Do not optimize for quantity
A smaller, tested library is better than a large collection of unverified prompts. Skills should be added when they solve a repeatable problem, not just because a new repository exists.
