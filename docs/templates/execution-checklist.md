# Sprint Execution Checklist Template

Use this checklist for each sprint or iteration to ensure consistent execution, quality, and delivery. Track progress daily and address blockers immediately.

---

## Sprint Planning

- [ ] **Sprint goal defined and communicated** — Owner: Product Manager / Scrum Master
  - Clear, measurable objective for the sprint
  - Team understands the goal and agrees it's achievable
- [ ] **Backlog items prioritized and ready** — Owner: Product Manager
  - Top priority items meet Definition of Ready
  - Dependencies identified and resolved or tracked
- [ ] **Team capacity confirmed** — Owner: Scrum Master / Project Manager
  - Team availability known (vacations, holidays, other commitments)
  - Capacity adjusted for meetings, on-call, and overhead
- [ ] **Sprint backlog committed** — Owner: Developers + Team
  - Team commits to selected work items
  - Work is estimated and fits within capacity

---

## Definition of Ready

Before pulling a work item into the sprint, ensure it meets the following criteria:

- [ ] **Clear acceptance criteria defined** — Owner: Product Manager / Business Analyst
  - Success conditions are specific and testable
  - Edge cases and error handling addressed
- [ ] **Dependencies identified and resolved** — Owner: Project Manager / Scrum Master
  - No blocking dependencies on other teams or work items
  - External dependencies tracked and communicated
- [ ] **Designs and specs available (if needed)** — Owner: UX Designer / Business Analyst
  - Wireframes, mockups, or technical specs provided
  - Design questions resolved
- [ ] **Estimated and fits team capacity** — Owner: Developers
  - Work item sized (story points, T-shirt size, or hours)
  - Estimate accounts for development, testing, and review time

---

## Development Workflow

### Code Development
- [ ] **Feature branch created from main** — Owner: Developers
  - Branch naming follows team conventions (e.g., `feature/issue-123-description`)
- [ ] **Code implements acceptance criteria** — Owner: Developers
  - All acceptance criteria met
  - Edge cases and error handling included
- [ ] **Unit tests written and passing** — Owner: Developers
  - New code has test coverage
  - All tests pass locally

### Pull Request (PR) Guidelines
- [ ] **PR size is reasonable** — Owner: Developers
  - PRs should be <= 400 lines when possible (excluding generated code)
  - Large PRs broken into smaller, incremental changes
  - If > 400 lines, justify in PR description
- [ ] **PR description is complete** — Owner: Developers
  - Linked to issue or work item
  - Summarizes changes and approach
  - Includes screenshots or demos for UI changes
  - References acceptance criteria
- [ ] **CI checks passing** — Owner: Developers
  - All automated tests passing
  - Linting and code formatting checks pass
  - Security scans pass with no critical issues
- [ ] **Code review requested and completed** — Owner: Developers (author) + Reviewers
  - At least one approval from a team member
  - Review comments addressed or discussed
  - No unresolved threads

### Merge and Integration
- [ ] **PR merged to main branch** — Owner: Developers
  - Merge conflicts resolved
  - Main branch CI checks still pass after merge

---

## Testing & Quality Assurance

### Automated Testing
- [ ] **Integration tests passing** — Owner: Developers / QA Lead
  - Tests validate end-to-end behavior
  - No regressions introduced
- [ ] **Security scans completed** — Owner: Security Liaison / DevOps Engineer
  - SAST, DAST, and dependency scans reviewed
  - No critical vulnerabilities introduced

### Manual Testing
- [ ] **Deploy to staging environment** — Owner: DevOps Engineer
  - Changes deployed to staging/QA environment
  - Deployment logs reviewed for errors
- [ ] **QA testing completed** — Owner: QA Lead
  - Manual testing against acceptance criteria
  - Exploratory testing for edge cases
  - Regression testing for critical flows
- [ ] **QA sign-off obtained** — Owner: QA Lead
  - All acceptance criteria verified
  - No blocking bugs or issues
  - Ready for production deployment

---

## Sprint Tracking & Communication

### Daily Progress
- [ ] **Daily standup held** — Owner: Scrum Master
  - Each team member shares progress, plan, and blockers
  - Blockers escalated and tracked
- [ ] **Project board updated** — Owner: Developers + Team
  - Work items moved through board states (Backlog → In Progress → In Review → QA → Done)
  - WIP (work in progress) limits respected
- [ ] **Blockers addressed within 24 hours** — Owner: Scrum Master / Project Manager
  - Blockers identified in standup
  - Escalated if team cannot resolve independently

### Sprint Review
- [ ] **Demo prepared** — Owner: Developers / Product Manager
  - Features demonstrated to stakeholders
  - Feedback captured and prioritized
- [ ] **Sprint metrics reviewed** — Owner: Scrum Master / Project Manager
  - Velocity and burndown tracked
  - Completed vs. committed work analyzed

---

## Acceptance Criteria Verification

For each work item marked as "Done", ensure:

- [ ] **All acceptance criteria met** — Owner: QA Lead
  - Functional requirements validated
  - Non-functional requirements (performance, accessibility, security) verified
- [ ] **Documentation updated** — Owner: Developers
  - README, API docs, or user guides updated as needed
  - Code comments added for complex logic
- [ ] **No known critical bugs** — Owner: QA Lead
  - Any known issues are documented and prioritized
  - Critical or blocking bugs resolved before sign-off

---

## Sprint Retrospective

- [ ] **Retrospective held** — Owner: Scrum Master
  - What went well, what didn't, and what to improve
  - Psychological safety maintained
- [ ] **Action items defined and assigned** — Owner: Scrum Master / Project Manager
  - Specific, actionable improvements identified
  - Owners assigned and tracked in next sprint

---

## Production Readiness (for releases)

If the sprint includes a production release, ensure:

- [ ] **Release checklist completed** — Owner: Project Manager / DevOps Engineer
  - Refer to [Release Checklist](release-checklist.md)
- [ ] **QA Lead provides production sign-off** — Owner: QA Lead
  - Production release approved based on quality and risk assessment
- [ ] **Stakeholders notified of release** — Owner: Project Manager
  - Release timing communicated
  - Release notes shared

---

## Notes
- Customize this checklist based on your team's workflow and cadence
- Review and update the checklist during retrospectives
- Use this checklist as a living document to improve execution quality over time
- For distributed or remote teams, ensure all checklist items are tracked in a shared tool (e.g., project board, wiki)
