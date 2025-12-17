# Release Checklist Template

Use this checklist for each production release to ensure consistency, reduce risk, and maintain quality. Assign clear owners for each item and track completion status.

---

## Pre-Release Activities

### Requirements & Planning
- [ ] **All acceptance criteria met** — Owner: QA Lead
  - All user stories and features marked as complete
  - Edge cases and error handling verified
- [ ] **Release notes drafted** — Owner: Product Manager
  - Summary of changes, new features, bug fixes
  - Migration steps or breaking changes documented
  - Known issues or limitations noted
- [ ] **Rollback/mitigation plan documented** — Owner: DevOps Engineer
  - Steps to rollback to previous version
  - Data migration rollback procedures (if applicable)
  - Communication plan for failed deployment

### Code & Build Quality
- [ ] **All PRs merged to main/release branch** — Owner: Developers
  - No outstanding code review comments
  - All CI checks passing (tests, linting, security scans)
- [ ] **Security scans completed with no critical issues** — Owner: Security Liaison
  - SAST/DAST scans reviewed
  - Dependency vulnerabilities assessed and mitigated
  - Secrets scanning passed
- [ ] **Build artifacts generated and verified** — Owner: DevOps Engineer
  - Build succeeds in CI/CD pipeline
  - Artifacts uploaded to artifact repository
  - Version tags applied correctly

### Testing
- [ ] **Unit and integration tests passing** — Owner: Developers
  - All automated tests green in CI
  - Code coverage meets team standards
- [ ] **Smoke tests prepared** — Owner: QA Lead
  - Critical user flows documented and ready to execute
  - Test data and accounts prepared
- [ ] **Performance/load testing completed (if applicable)** — Owner: DevOps Engineer / QA Lead
  - Performance benchmarks met
  - No regressions in response times or throughput

---

## Deployment Activities

### Staging Deployment
- [ ] **Deploy to staging environment** — Owner: DevOps Engineer
  - Deployment process executed successfully
  - No errors in deployment logs
- [ ] **Run smoke tests in staging** — Owner: QA Lead
  - All critical flows verified
  - No blocking issues identified
- [ ] **Staging sign-off obtained** — Owner: QA Lead + Product Manager
  - Product Manager confirms feature correctness
  - QA Lead confirms quality acceptance

### Production Deployment
- [ ] **Deployment window scheduled and communicated** — Owner: Project Manager
  - Stakeholders notified of deployment timing
  - On-call and support teams alerted
  - Downtime or maintenance window announced (if needed)
- [ ] **Backup or snapshot taken (if applicable)** — Owner: DevOps Engineer
  - Database backup completed
  - Configuration backup saved
- [ ] **Deploy to production** — Owner: DevOps Engineer
  - Automated pipeline triggered or manual deployment executed
  - Deployment logs reviewed for errors
- [ ] **Post-deploy smoke tests executed** — Owner: QA Lead / Support Engineer
  - Critical user flows verified in production
  - No immediate errors or failures observed

---

## Post-Release Verification

### Monitoring & Observability
- [ ] **Verify monitoring and alerting** — Owner: DevOps Engineer
  - Application metrics (latency, errors, throughput) reviewed
  - No unexpected spikes or anomalies
  - Alerts configured and firing as expected
- [ ] **Review logs for errors** — Owner: DevOps Engineer / Support Engineer
  - Application and infrastructure logs checked
  - No critical errors or warnings
- [ ] **Database migrations completed (if applicable)** — Owner: DevOps Engineer
  - Schema changes applied successfully
  - Data integrity verified

### Communication
- [ ] **Announce release to stakeholders** — Owner: Project Manager
  - Release notes shared with stakeholders
  - Key features and changes highlighted
- [ ] **Notify support and on-call teams** — Owner: Project Manager
  - Support documentation updated
  - Known issues and troubleshooting steps shared
  - On-call team briefed on potential incidents

---

## Rollback Procedures (if needed)

If critical issues are detected post-deployment:

- [ ] **Trigger incident response** — Owner: Support/On-call Engineer
  - Incident declared and on-call notified
  - Incident channel or war room established
- [ ] **Execute rollback** — Owner: DevOps Engineer
  - Revert to last known-good release
  - Database rollback executed (if applicable)
- [ ] **Verify rollback success** — Owner: QA Lead / Support Engineer
  - Critical flows verified after rollback
  - Monitoring confirms stability
- [ ] **Communicate rollback to stakeholders** — Owner: Project Manager
  - Status update shared with stakeholders
  - Root cause investigation initiated
- [ ] **Capture action items for post-incident review** — Owner: Project Manager
  - Timeline and decisions documented
  - Lessons learned and improvements identified

---

## Post-Release Activities

- [ ] **Monitor production for 24-48 hours** — Owner: Support/On-call Engineer + DevOps Engineer
  - Track error rates, latency, and customer feedback
  - Respond to any incidents or anomalies
- [ ] **Conduct post-release retrospective** — Owner: Project Manager / Scrum Master
  - Review what went well and what didn't
  - Document lessons learned and action items
  - Update release process based on feedback
- [ ] **Update project documentation** — Owner: Project Manager
  - Mark release as complete in project board
  - Archive release artifacts and notes
  - Update project status and velocity metrics

---

## Notes
- Adapt this checklist based on release type (patch, minor, major) and criticality
- For hotfixes or emergency releases, prioritize rollback planning and post-deploy verification
- Ensure each checklist item has a clear owner assigned before starting the release process
