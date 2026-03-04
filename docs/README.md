# OctoAcme Project Management Docs

Welcome! This README centralizes all project management process documentation for OctoAcme.

---

## Overview: How OctoAcme Runs Projects

OctoAcme's project management approach is designed to deliver value quickly, share knowledge, and enable every team member to contribute confidently.

### Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments for rapid feedback
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and candor

### Core Roles
- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and business direction

### Project Lifecycle
1. **Initiation:** Define problem, stakeholders, and high-level timeline
2. **Planning:** Break work into shippable increments, identify dependencies and risks
3. **Execution:** Build, test, review, iterate with daily standups and demos
4. **Release:** Deploy to production, verify, and announce to stakeholders
5. **Retrospective:** Capture learnings and drive continuous improvements

### Key Artifacts & Processes
- **Project Charter / One-pager:** Problem statement, objectives, success metrics, timeline
- **Prioritized Backlog:** With acceptance criteria and Definition of Done
- **Roadmap & Release Plan:** High-level milestones and delivery windows
- **Risk Register:** ID, description, impact, likelihood, mitigation, status
- **Project Board:** Columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Retrospective Notes:** Learnings and action items with owners

### Communication Cadence
- **Weekly:** PM + PdM sync to align on priorities and risks
- **Twice-weekly or weekly:** Delivery team standups (15 min, focus on blockers and progress)
- **End of sprint/milestone:** Demo and review with stakeholders
- **Monthly:** Stakeholder status updates
- **Ad-hoc:** Risk escalations and incident communications

### Quality & Execution Standards
- Small PRs (≤ 400 lines when possible)
- Unit tests for new logic, integration tests where applicable
- Automated CI: tests, linting, security scanning
- At least one approval before merging (team-defined policy)
- Manual QA for feature acceptance when needed
- Smoke tests before release

### Risk & Blocker Escalation
1. **Level 1:** Team-level triage in daily standup
2. **Level 2:** PM escalates to Product Lead and dependent teams
3. **Level 3:** Sponsor-level escalation for business-impacting issues

---

## Key Process Docs

Navigate to the specific guides for detailed workflows, checklists, and templates:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, create Project One-pager, go/no-go decision
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiative into actionable plan: backlog, estimates, release timeline, Definition of Done
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, team rhythm, PR workflow, quality standards, metrics, blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, mitigate, and monitor risks; manage stakeholder communication and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases by type, pre-release requirements, deployment checklist, rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retrospectives, capture learnings, track and measure improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role definitions, responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers

---

## Quick Start

**Starting a new project?**
1. Read the [Project Management Overview](octoacme-project-management-overview.md)
2. Follow the [Project Initiation Guide](octoacme-project-initiation.md) to create your Project One-pager
3. Move to [Project Planning](octoacme-project-planning.md) once approved

**Executing your project?**
- Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily standup, PR workflow, and quality standards
- Monitor risks using [Risk Management & Communication](octoacme-risks-and-communication.md)
- Demo and gather feedback regularly

**Ready to release?**
- Follow [Release & Deployment Guide](octoacme-release-and-deployment.md)

**Improving as a team?**
- Run [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) after each sprint or release

---

## About This Copilot Space

This Copilot Space centralizes OctoAcme's project management processes, making them searchable, versioned, and accessible to all team members. We believe that:

- **Knowledge should be shared:** All team members deserve equal access to processes and decision rationale
- **Improvements are collaborative:** Use the issue templates in `.github/ISSUE_TEMPLATE/` to suggest updates and refinements
- **Processes evolve:** Regular retrospectives and feedback cycles keep our docs current, relevant, and aligned with how we actually work

### Contributing
Have an improvement or clarification? [Create an issue using the "Add Content to Project Management Process Docs" template](../../issues/new?template=add-update-content-to-process-docs.yml) and we'll review it together.

---

## How to Use This Space
- Keep the Project Charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for project-specific guidance
- Reference relevant docs during project kickoffs and team onboarding