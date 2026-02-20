# OctoAcme — QA Testing Checklist

## Purpose
Provide a consistent checklist for QA Engineers (and the full delivery team) to follow when validating features before they are moved to Done and cleared for release.

## Ownership
- **Primary owner**: QA Engineer
- **Collaborators**: Developer (testability), Release Manager (release gate)

---

## Test Planning

- [ ] Acceptance criteria reviewed and understood
- [ ] Edge cases and negative test scenarios identified
- [ ] Test plan created and linked to the relevant issue or epic
- [ ] Automated test coverage assessed; gaps identified and logged

---

## Functional Testing

- [ ] All acceptance criteria verified against the implemented feature
- [ ] Regression tests run — no regressions introduced
- [ ] Edge cases and boundary conditions tested
- [ ] Error and empty states handled correctly
- [ ] Cross-browser / cross-device testing completed (if applicable)

---

## Accessibility & Usability

- [ ] Keyboard navigation works correctly
- [ ] Screen reader compatibility verified (if applicable)
- [ ] Color contrast and visual accessibility standards met
- [ ] UX/UI Designer sign-off on design fidelity obtained

---

## Integration & End-to-End Testing

- [ ] Integration tests pass for affected services or APIs
- [ ] End-to-end smoke tests pass for critical user flows
- [ ] Data integrity verified across system boundaries

---

## Security & Performance

- [ ] Security scanning in CI passed (no new critical findings)
- [ ] Performance benchmarks within acceptable thresholds (if applicable)
- [ ] No sensitive data exposed in logs or API responses

---

## Pre-release Gate

- [ ] All blocking defects resolved and verified
- [ ] QA sign-off documented in the issue or PR
- [ ] Test summary shared with Release Manager
- [ ] Feature flagged or toggled correctly for production (if applicable)

---

## Defect Tracking

Use the following template for defect reports:

- **Title**:
- **Severity** (Critical / High / Medium / Low):
- **Steps to reproduce**:
- **Expected result**:
- **Actual result**:
- **Environment**:
- **Attachments** (screenshots, logs):
- **Owner**:
- **Status**:

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Role Collaboration & Handoff Checklist](octoacme-role-collaboration-checklist.md)
