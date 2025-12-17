# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Quick Reference
- [Sprint Execution Checklist](templates/execution-checklist.md) — Per-sprint checklist for consistent delivery
- [Role-Responsibility Matrix](role-responsibility-matrix.md) — RACI for key project activities

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - **PR size guidance**: Keep PRs small (<= 400 lines when possible, excluding generated code) to enable faster reviews and reduce integration risk. If a PR exceeds 400 lines, provide justification in the PR description.
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - **QA Lead sign-off for production releases**: Before merging PRs that will be deployed to production, ensure QA Lead has reviewed and approved based on testing results and quality standards. Refer to the [Sprint Execution Checklist](templates/execution-checklist.md) for detailed QA sign-off criteria.

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Team is familiar with [Sprint Execution Checklist](templates/execution-checklist.md)
- [ ] Roles and responsibilities clarified using [Role-Responsibility Matrix](role-responsibility-matrix.md)
