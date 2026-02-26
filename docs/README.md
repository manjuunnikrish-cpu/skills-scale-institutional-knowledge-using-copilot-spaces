# OctoAcme Project Management Docs

> This folder contains the process documents for OctoAcme's project management lifecycle. It serves as the knowledge base for the **OctoAcme Project Management Copilot Space**, centralizing tacit team insights into versioned, searchable artifacts that improve onboarding, consistency, and decision-making.

---

## Purpose of this Copilot Space

The OctoAcme Project Management Copilot Space helps teammates:

- **Onboard faster** — new PMs, PdMs, developers, and QA engineers can understand how work flows from idea to release.
- **Centralize knowledge** — process decisions that once lived in people's heads or scattered emails are captured here as versioned docs.
- **Get role-specific guidance** — use these docs as Copilot context to get answers tailored to your role and project phase.
- **Improve consistency** — shared templates and checklists reduce rework and miscommunication across projects.

---

## Lifecycle Overview

OctoAcme projects follow a six-phase lifecycle:

### 1. Initiation
Validate the business need, align stakeholders, and create a lightweight one-pager before committing to planning.
Key deliverables: Project One-pager, stakeholder list, high-level timeline, initial risk list, go/no-go decision.

### 2. Planning
Turn an approved initiative into an actionable backlog and release plan.
Key deliverables: Kickoff meeting, prioritized backlog with acceptance criteria, estimates, Definition of Done (DoD), risk register, milestone map.

### 3. Execution & Tracking
Build, test, review, and iterate while keeping the team and stakeholders aligned.
Key activities: Daily standups, weekly sync, project-board workflow, small focused PRs, CI/CD quality gates, burndown tracking, blocker escalation.

### 4. Risk Management & Communication
Identify, assess, and communicate risks throughout the project.
Key activities: Risk register maintenance, stakeholder status updates, escalation paths (Team → PM → Product Lead → Sponsor), incident communication templates.

### 5. Release & Deployment
Ship reliably with pre-release checks, a deployment checklist, and a rollback plan.
Release types: Patch, Minor, Major. Key artifacts: release notes, smoke tests, post-deploy verification, rollback playbook.

### Close: Retrospective & Continuous Improvement
After each sprint, release, or milestone, capture learnings and convert them into tracked action items.
Structure: What went well · What could be improved · Action items (owner + due date) · Follow-up on previous actions.

---

## Roles & Personas

| Role | Focus |
|---|---|
| **Project Manager (PM)** | Delivery coordination, schedules, risk, communications |
| **Product Manager (PdM)** | Outcomes, backlog prioritization, success metrics |
| **Developers** | Implementation, code reviews, test coverage |
| **QA / Testing** | Acceptance validation, quality gates |
| **Stakeholders** | Inputs, approvals, escalation recipients |

---

## Quick Links

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | One-pager template, stakeholder alignment, go/no-go checklist |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimates, DoD, dependencies, release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Standups, board workflow, PR expectations, quality & metrics |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, communication templates, escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro structure, action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each role |

---

## How to use these docs with Copilot Spaces

1. Add the relevant process doc(s) to your Copilot Space context (e.g., via `.copilot/`).
2. Ask Copilot role-specific questions such as *"What should I do at project initiation?"* or *"What's in the deployment checklist?"*.
3. Use the templates and checklists in each doc as starting points for your project artifacts.
