# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management process documentation for all cross-functional product and project teams. Use this README as the single entrypoint to understand our approach, find role descriptions, and jump to detailed process documents.

## Brief overview

OctoAcme follows a lightweight, iterative project management approach that prioritizes delivering customer value in small, testable increments. Work is planned using a project one-pager and a prioritized backlog, executed in short iterations or milestones, and validated with clear acceptance criteria. Each project names a Project Manager (PM) and Product Manager / Product Lead (PdM) to ensure both coordination and outcome ownership.

Day-to-day workflows emphasize clear handoffs and rapid feedback: the team uses a project board with states such as Backlog → Ready → In Progress → In Review → QA → Done, small pull requests with linked issues and acceptance criteria, and a regular team cadence (daily standups, weekly delivery syncs, and end-of-sprint demos). Blockers escalate through a defined path (team → PM → Product Lead → Sponsor) and risks are tracked in a Risk Register reviewed weekly.

Communication is structured around a shared single source of truth (project README, release notes, and project artifacts), weekly PM+PdM syncs, and stakeholder-tailored updates. Templates are provided for weekly status and incident communications so cross-functional teams and stakeholders receive consistent, actionable updates.

Quality assurance is built into the lifecycle: developers add unit and integration tests, CI runs automated tests and security scans, critical flows have end-to-end smoke tests in staging, and manual QA verifies acceptance when needed. Releases follow a checklist (pre-release checks, smoke tests, automated pipeline deployments when possible), include rollback/mitigation plans, and capture release notes and post-release retrospectives.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution &amp; Tracking](octoacme-execution-and-tracking.md)
- [Risk Management &amp; Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles &amp; Personas](octoacme-roles-and-personas.md)

## How to use this folder

- Start here when onboarding to a project.
- Link to these docs from your project README and Project One-pager.
- Keep the process docs updated; propose changes via the Add Content to Project Management Process Docs issue template.

## Acceptance criteria for this README

- Content aligns with existing process docs in docs/
- README improves discoverability and provides a clear starting point
- README is linked from the project issue that requested it (issue #2)
