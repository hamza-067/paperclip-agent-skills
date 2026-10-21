# Contributing Skills

## Standard workflow
1. Open an issue or describe the capability gap.
2. Search the current index and repository for duplicates.
3. Create a branch named `skill/<short-name>` or `update/<short-name>`.
4. Add or revise one skill at a time when practical.
5. Provide evidence, tests, risks, and rollback notes.
6. Run the validation workflow locally or let GitHub Actions validate the pull request.
7. Request review from a maintainer. Do not merge your own changes unless the maintainer explicitly delegated that authority.
8. Update `SKILL_INDEX.md` and `CHANGELOG.md`.

## Acceptance checklist
- [ ] Clear, unique name and useful description
- [ ] YAML frontmatter parses and required fields exist
- [ ] Actionable workflow with inputs, outputs, and completion criteria
- [ ] Source links and checked date for externally sourced claims
- [ ] At least one realistic test case and one failure case
- [ ] Safety, privacy, and permission boundaries included
- [ ] No secrets, personal data, or copied bulk content
- [ ] No unsupported claims of capabilities or guaranteed results
- [ ] Index and changelog updated when needed

## Style
Write clear, direct instructions. Prefer checklists and examples. State uncertainty. Do not promise earnings, rankings, conversion rates, or model accuracy.
