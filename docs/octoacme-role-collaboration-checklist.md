# OctoAcme — Role Collaboration & Handoff Checklist

## Purpose
Clarify who owns key activities and how handoffs between personas are managed across project phases. Use this checklist when transitioning work between roles to avoid gaps in accountability.

---

## Requirements → Design Handoff (Business Analyst → UX/UI Designer)

- [ ] Requirements document or user stories shared with the UX/UI Designer
- [ ] Business process flows and user journey maps provided
- [ ] Acceptance criteria clarified for any UX-sensitive features
- [ ] Open questions documented and resolved before design begins
- [ ] Designer confirms scope is understood and feasible

---

## Design → Development Handoff (UX/UI Designer → Developer)

- [ ] High-fidelity mockups and interactive prototype shared
- [ ] Component specifications and design tokens documented
- [ ] Accessibility requirements (WCAG level, keyboard nav, ARIA) listed
- [ ] Assets exported and available in the shared design system
- [ ] Developer kickoff session held to walk through design intent
- [ ] Open questions logged and assigned with due dates

---

## Development → QA Handoff (Developer → QA Engineer)

- [ ] Feature branch merged and CI passing
- [ ] PR includes reference to the issue and acceptance criteria
- [ ] Known limitations or out-of-scope items noted in the PR or issue
- [ ] Test environment configured and deployment confirmed
- [ ] QA Engineer briefed on implementation details or edge cases
- [ ] Automated tests written and passing before QA begins

---

## QA → Release Handoff (QA Engineer → Release Manager)

- [ ] All acceptance criteria verified and QA sign-off documented
- [ ] Defect report reviewed — no blocking or critical open issues
- [ ] Test summary (including smoke-test results) shared with Release Manager
- [ ] Release notes reviewed for accuracy with Product Manager
- [ ] Rollback plan confirmed with the Release Manager
- [ ] Deployment window communicated to all stakeholders

---

## Release → Stakeholder Communication (Release Manager → Project/Product Manager)

- [ ] Release deployed and post-deploy verifications passed
- [ ] Release notes published (repo, changelog, or internal wiki)
- [ ] Stakeholder announcement sent (email, Slack, or equivalent)
- [ ] Known issues and workarounds documented and communicated
- [ ] Success metrics baseline recorded for post-release tracking

---

## Onboarding Checklist for New Roles

When a new QA Engineer, UX/UI Designer, Release Manager, or Business Analyst joins the team:

- [ ] Introduced to the team in the next standup or sync
- [ ] Access provisioned (repo, project board, design tools, CI/CD, staging environment)
- [ ] [Roles & Personas doc](octoacme-roles-and-personas.md) reviewed
- [ ] [Project Management Overview](octoacme-project-management-overview.md) reviewed
- [ ] Current sprint backlog and active issues walked through
- [ ] Buddy/mentor assigned for the first two weeks
- [ ] First task identified and scoped to enable an early contribution

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [QA Testing Checklist](octoacme-qa-testing-checklist.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
