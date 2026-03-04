# OctoAcme — QA & Release Readiness Checklist

## Purpose
Ensure that all quality assurance and release readiness criteria are met before any release proceeds to production. This checklist is owned by the QA Lead and reviewed jointly with the Project Manager and Product Owner.

---

## QA Readiness

### Test Planning
- [ ] Test plan created and reviewed by QA Lead and Product Owner
- [ ] Acceptance criteria defined for all user stories in scope
- [ ] Test cases written and linked to acceptance criteria
- [ ] Test environments provisioned and verified

### Test Execution
- [ ] Unit tests passing with agreed coverage threshold met
- [ ] Integration tests passing
- [ ] End-to-end / acceptance tests executed
- [ ] Regression test suite executed and results reviewed
- [ ] Performance / load tests completed (if applicable)
- [ ] Security scans completed with no critical or high findings outstanding

### Defect Management
- [ ] All critical and high defects resolved or formally accepted with mitigation
- [ ] Medium defects triaged and disposition documented (fix or defer with rationale)
- [ ] Defect summary reviewed with Project Manager and Product Owner
- [ ] No open defects blocking release

---

## Release Readiness

### Documentation & Communication
- [ ] Release notes drafted and reviewed
- [ ] Known issues documented in release notes
- [ ] Stakeholder communication drafted (see [Stakeholder Communication Template](octoacme-stakeholder-communication-template.md))
- [ ] Support team briefed on changes

### Deployment Preparation
- [ ] Deployment plan reviewed and approved
- [ ] Deployment window confirmed with relevant teams
- [ ] Rollback plan documented and tested (if applicable)
- [ ] Feature flags / configuration changes reviewed
- [ ] Database migrations tested in staging (if applicable)

### Staging Verification
- [ ] Deployed to staging environment successfully
- [ ] Smoke tests passed in staging
- [ ] Post-deploy verification steps documented

### Approvals
- [ ] QA Lead sign-off obtained
- [ ] Product Owner sign-off on acceptance criteria met
- [ ] Project Manager confirms no outstanding blockers

---

## Post-Release Verification

- [ ] Production deployment completed successfully
- [ ] Post-deploy smoke tests passed
- [ ] Monitoring and alerting confirmed active
- [ ] Release announcement sent to stakeholders
- [ ] Rollback decision criteria defined and communicated to on-call team

---

## Release Sign-Off

| Role | Name | Signature / Approval | Date |
|---|---|---|---|
| QA Lead | | | |
| Product Owner | | | |
| Project Manager | | | |

---

## Notes
- This checklist must be completed before any production release.
- Archive completed checklists in the project repository alongside release notes.
- For hotfixes, a subset of this checklist may be used — document any skipped items and the rationale.
