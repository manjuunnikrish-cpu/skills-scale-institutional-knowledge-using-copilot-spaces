# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on continuous improvement. They act as a servant-leader who protects the team's focus and ensures agile practices are applied consistently.

### Responsibilities
- Facilitate standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove blockers and impediments blocking team progress
- Shield the team from unplanned interruptions during a sprint
- Track sprint progress and surface risks to the Project Manager early
- Coach team members on agile practices and foster a culture of continuous improvement

### Goals
- Keep teams aligned, unblocked, and delivering predictably
- Improve team velocity and reduce cycle time over time
- Create a safe environment for open feedback and retrospection

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment log updates and blocker escalation to Project Manager
- Sprint metrics (velocity, burndown) shared with Project Manager and Product Manager

### Interactions with Existing Roles
- **Project Manager**: Shares impediment status, escalates blockers that require cross-team resolution; coordinates on milestone and release timelines.
- **Product Manager (PdM)**: Coordinates sprint planning and backlog refinement; ensures stories are ready before sprint start.
- **Developers**: Facilitates ceremonies, coaches on process, and protects sprint commitments from scope creep.
- **Handoff**: Sprint retrospective outputs feed into the Project Manager's risk register and continuous improvement backlog.

---

## UX Designer / Product Designer

### Role Summary
The UX Designer leads user-centered design efforts, translates user needs into wireframes and interactive prototypes, and validates solutions with end-users before and during development.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design systems and interaction standards
- Collaborate on acceptance criteria to include usability requirements
- Iterate designs based on user feedback and analytics

### Goals
- Ensure the product is intuitive, accessible, and meets user needs
- Reduce rework by validating design direction early
- Maintain design consistency across the product

### Typical Communication
- Design reviews with Product Manager and Developers
- Usability test reports shared with Product Manager and QA
- Figma/design tool links in tickets and PRs for developer reference

### Interactions with Existing Roles
- **Product Manager (PdM)**: Collaborates on problem definition and user stories; shares research findings to inform prioritization.
- **Developers**: Provides design specs, assets, and clarifications during implementation; reviews built features against designs.
- **Project Manager**: Flags design work as a dependency in the project plan; surfaces design-blocking risks.
- **Handoff**: Designs handed off to Developers via annotated mockups or design tool links once approved by Product Manager; QA uses acceptance criteria that include usability standards.

---

## DevOps / SRE / Platform Engineer

### Role Summary
The DevOps/SRE/Platform Engineer builds and maintains CI/CD pipelines, deployment automation, infrastructure-as-code, and operational monitoring. They bridge development and operations to ensure reliable, repeatable, and secure delivery.

### Responsibilities
- Build, maintain, and improve CI/CD pipelines and release automation
- Manage infrastructure-as-code (IaC) for environments (dev, staging, production)
- Implement and monitor observability (logs, metrics, alerts)
- Ensure deployment repeatability and support rollback capabilities
- Partner with Security/Compliance on hardening and scanning integrations

### Goals
- Enable teams to ship confidently and frequently with minimal manual effort
- Maximize system reliability and minimize mean time to recovery (MTTR)
- Keep infrastructure secure, compliant, and well-documented

### Typical Communication
- Deployment and pipeline status updates to Project Manager and Developers
- Incident postmortems and runbooks shared with the team
- Infrastructure change announcements ahead of releases

### Interactions with Existing Roles
- **Project Manager**: Coordinates deployment windows and release schedules; reports environment readiness.
- **Developers**: Provides tooling, environment access, and CI/CD guidance; reviews infra-impacting PRs.
- **Product Manager (PdM)**: Informs on release readiness and operational constraints that affect delivery timelines.
- **Handoff**: Deployment readiness confirmed by DevOps/SRE before release is triggered; post-deploy verification handed back to Project Manager and Developers for sign-off.

---

## Business Analyst

### Role Summary
The Business Analyst elicits business requirements, documents acceptance criteria, and bridges communication between stakeholders and technical teams to ensure the right solution is built.

### Responsibilities
- Elicit, document, and validate business requirements and process workflows
- Translate stakeholder needs into clear user stories with measurable acceptance criteria
- Maintain requirement traceability from business objective to delivered feature
- Facilitate requirements workshops and working sessions with stakeholders
- Support QA in understanding testable outcomes and edge cases

### Goals
- Ensure the delivered solution meets business objectives and stakeholder expectations
- Reduce ambiguity in requirements before development begins
- Improve traceability and audit-readiness of requirements

### Typical Communication
- Requirements workshops and stakeholder walkthroughs
- User story documentation in the project backlog (e.g., GitHub Issues)
- Acceptance criteria reviews with Developers and QA

### Interactions with Existing Roles
- **Product Manager (PdM)**: Collaborates on refining product vision into actionable requirements and prioritized backlog items.
- **Project Manager**: Aligns on scope boundaries and flags requirement changes that affect timelines or budget.
- **Developers**: Clarifies business rules, edge cases, and acceptance criteria during implementation.
- **Handoff**: Finalized user stories and acceptance criteria handed off to Developers at sprint start; validated requirements handed to QA for test planning.

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager / Tech Lead provides technical leadership, mentors developers, drives architectural decisions, and ensures the team has the capacity and capability to deliver high-quality software. *(In smaller teams these may be one person; in larger organizations they are separate — the Engineering Manager focuses on people and team health, while the Tech Lead focuses on technical direction.)*

### Responsibilities
- Define and uphold technical standards, coding conventions, and architectural patterns
- Lead design reviews and technical decision-making
- Support developer growth through code reviews, mentoring, and feedback
- Balance technical debt reduction with feature delivery
- Coordinate engineering capacity and flag staffing risks to Project Manager

### Goals
- Maintain a healthy, productive, and growing engineering team
- Deliver technically sound solutions that are maintainable and scalable
- Reduce technical debt and accidental complexity over time

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review feedback in PRs
- Capacity and risk updates in weekly syncs with Project Manager and Product Manager

### Interactions with Existing Roles
- **Project Manager**: Communicates engineering capacity, technical risks, and dependency blockers.
- **Product Manager (PdM)**: Collaborates on feasibility, trade-offs, and effort estimates for roadmap items.
- **Developers**: Mentors and guides technical decisions; reviews and approves critical PRs.
- **Handoff**: Technical designs reviewed and approved before implementation begins; architectural risks surfaced to Project Manager for the risk register.

---

## Security / Compliance Representative

### Role Summary
The Security/Compliance Representative ensures that security and compliance requirements are identified early, built into delivery processes, and met before releases. This is a lightweight, embedded role that advises rather than approves every artifact.

### Responsibilities
- Define and communicate security and compliance requirements relevant to the project
- Review architecture and design decisions for security implications
- Ensure security scanning is integrated into CI (SAST, dependency scanning, secrets detection)
- Act as the escalation point for security incidents identified during development or production
- Validate compliance posture before major releases

### Goals
- Shift security left — catch issues in design and development, not production
- Minimize security risk in released software
- Ensure the team understands and meets relevant compliance obligations

### Typical Communication
- Security review notes on design docs and PRs when risk is identified
- Compliance checklist updates before major releases
- Incident escalation communications following the security incident runbook

### Interactions with Existing Roles
- **Project Manager**: Flags security risks for inclusion in the risk register; advises on compliance-driven timeline constraints.
- **Developers / DevOps**: Reviews code and pipeline configurations for security issues; provides remediation guidance.
- **Product Manager (PdM)**: Advises on security implications of product decisions (e.g., data handling, integrations).
- **Handoff**: Security sign-off provided to Project Manager and DevOps/SRE as part of the pre-release checklist before production deployment.

---

## Customer Support / Customer Success Representative

### Role Summary
The Customer Support / Customer Success Representative is the voice of the customer inside the delivery team. They surface recurring customer issues, communicate upcoming changes to support teams, and ensure release communications reach end-users effectively.

### Responsibilities
- Share customer feedback, support ticket trends, and usability pain points with the Product Manager
- Communicate upcoming releases and changes to support teams ahead of deployment
- Draft or review customer-facing release notes and announcements
- Escalate customer-impacting production issues to the Project Manager and DevOps/SRE
- Coordinate with the team on known issues and workarounds at time of release

### Goals
- Ensure customers are informed and supported through product changes
- Feed real-world usage feedback back into the product roadmap
- Reduce support burden by advocating for clear UX and documentation

### Typical Communication
- Customer feedback summaries shared before roadmap planning sessions
- Release announcement drafts reviewed with Product Manager before publish
- Escalation notifications for customer-impacting incidents

### Interactions with Existing Roles
- **Product Manager (PdM)**: Provides customer insight to inform prioritization; reviews customer-facing messaging for releases.
- **Project Manager**: Receives advance notice of releases to prepare support communications; escalates customer-impacting incidents.
- **Developers / DevOps**: Reports customer-facing bugs and production issues; receives ETAs and workaround guidance.
- **Handoff**: Release notes and customer communications handed off by Project Manager / Product Manager for review and publish at release time.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for how roles map to the project lifecycle.
- See [OctoAcme Role Handoff Checklist](octoacme-role-handoff-checklist.md) for guidance on handoffs between roles.

