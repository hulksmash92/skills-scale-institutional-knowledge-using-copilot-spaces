# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and specialized personas whose collaboration ensures quality, usability, and smooth releases across all project phases.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineer

### Role Summary
QA Engineers are responsible for validating that features meet acceptance criteria and quality standards before release. They design and execute test plans, identify defects, and work closely with Developers and the Release Manager to ensure production readiness.

### Responsibilities
- Design, write, and execute test plans and test cases aligned to acceptance criteria
- Perform functional, regression, and exploratory testing
- Report and track defects, verifying fixes before sign-off
- Contribute to and maintain automated test suites (unit, integration, end-to-end)
- Participate in sprint planning and backlog refinement to assess testability
- Own the QA column on the project board and gate merges to Done

### Goals
- Prevent defects from reaching production
- Ensure consistent, repeatable validation of all features
- Increase test automation coverage over time

### Typical Communication
- Daily standups and sprint ceremonies with the delivery team
- Defect reports and QA sign-off notes in pull requests and issues
- Test summary reports shared with the Release Manager before deployments

### Interactions with Existing Roles
- **Developers**: Collaborate on acceptance criteria, review PRs for testability, and co-own the Definition of Done.
- **Product Managers**: Clarify ambiguous requirements and success metrics to ensure test cases reflect intended behavior.
- **Project Managers**: Surface blocking defects and testing timelines so schedules can be adjusted.
- **Release Manager**: Provide QA sign-off and smoke-test results as a gate for production releases.

---

## UX/UI Designer

### Role Summary
UX/UI Designers craft the user experience and visual design of product features. They ensure that interfaces are intuitive, accessible, and aligned with user needs and brand standards.

### Responsibilities
- Conduct user research, interviews, and usability testing to inform design decisions
- Produce wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns, component specifications, and accessibility requirements
- Collaborate with Product Managers on problem framing and with Developers on feasibility
- Maintain a shared design system and style guide
- Review implemented UIs for design fidelity before QA sign-off

### Goals
- Deliver usable, accessible, and visually consistent product experiences
- Reduce rework by aligning design and engineering expectations early
- Advocate for end-user needs throughout the product lifecycle

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Annotated mockups and prototype links shared in issues and PRs
- Usability test findings presented at sprint demos or milestone reviews

### Interactions with Existing Roles
- **Product Managers**: Partner on feature discovery, user research synthesis, and solution framing.
- **Developers**: Provide detailed specs, clarify design intent during implementation, and review UI output.
- **QA Engineers**: Share accessibility requirements and design acceptance criteria for testing.
- **Business Analysts**: Align on user workflows and requirements to ensure designs meet business needs.

---

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, ensuring that deployments are safe, coordinated, and well-communicated. They serve as the gate-keepers between development completion and production delivery.

### Responsibilities
- Plan and schedule releases, including deployment windows and change-freeze periods
- Maintain and execute the Release & Deployment checklist
- Coordinate readiness across QA, development, and operations teams
- Draft and distribute release notes and stakeholder announcements
- Own rollback plans and incident response coordination during deployments
- Track post-release metrics and confirm release success criteria are met

### Goals
- Deliver reliable, low-risk releases to production
- Ensure all stakeholders are informed before, during, and after deployments
- Reduce mean time to recovery (MTTR) when issues arise

### Typical Communication
- Release readiness meetings with QA Engineers, Developers, and Project Managers
- Pre-release announcements and post-release summaries to stakeholders
- Incident communication using the escalation and incident communication templates

### Interactions with Existing Roles
- **QA Engineers**: Require formal QA sign-off and smoke-test results before authorizing a release.
- **Developers**: Confirm all PRs are merged, CI is green, and release branches are stable.
- **Project Managers**: Align on release timelines and surface any scope or schedule risks.
- **Product Managers**: Ensure release notes accurately reflect shipped value and any known limitations.

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and the delivery team. They translate business needs into clear, actionable requirements and ensure solutions deliver measurable value.

### Responsibilities
- Elicit, document, and validate business and user requirements
- Write detailed user stories, acceptance criteria, and process flow diagrams
- Conduct gap analysis and identify process improvement opportunities
- Facilitate requirements workshops and stakeholder interviews
- Validate delivered features against business requirements before sign-off
- Maintain requirements traceability from business need to delivered feature

### Goals
- Ensure that what is built solves the correct business problem
- Reduce ambiguity and rework by providing clear, complete requirements
- Improve alignment between business stakeholders and the delivery team

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written requirements documents, user stories, and acceptance criteria in the backlog
- Review sessions with Product Managers and Developers to confirm shared understanding

### Interactions with Existing Roles
- **Product Managers**: Collaborate on problem framing, prioritization, and success metrics.
- **Developers**: Provide detailed requirements and answer clarifying questions during implementation.
- **UX/UI Designers**: Share business process flows and user needs to inform design decisions.
- **Project Managers**: Flag scope changes or new requirements that may affect timelines.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See also: [QA Testing Checklist](octoacme-qa-testing-checklist.md) and [Role Collaboration & Handoff Checklist](octoacme-role-collaboration-checklist.md) for cross-role process guides.

