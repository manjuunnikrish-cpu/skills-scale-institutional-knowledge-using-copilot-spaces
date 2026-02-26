# OctoAcme — Role Handoff Checklist

## Purpose
Ensure consistent, clear handoffs between roles at key project transition points. Use this checklist to confirm that the receiving role has everything they need before work moves forward.

---

## 1. Requirements → Development Handoff
*From: Business Analyst / Product Manager (PdM) → To: Developers*

- [ ] User stories are written with clear acceptance criteria
- [ ] Edge cases and business rules are documented
- [ ] Wireframes / design mockups are linked (if applicable)
- [ ] Dependencies on other teams or services are identified
- [ ] Definition of Done is understood by the development team
- [ ] Questions from Developers resolved before sprint start

---

## 2. Design → Development Handoff
*From: UX Designer / Product Designer → To: Developers*

- [ ] Final mockups and prototypes are accessible (e.g., Figma link in ticket)
- [ ] Design annotations cover edge cases, empty states, and error states
- [ ] Assets (icons, images) are exported and available
- [ ] Interaction specifications and animations are documented where needed
- [ ] Accessibility requirements are noted
- [ ] UX Designer available for questions during implementation

---

## 3. Development → QA / Review Handoff
*From: Developers → To: QA / Reviewers*

- [ ] PR description includes issue link and summary of changes
- [ ] Acceptance criteria are addressed and noted in the PR
- [ ] Automated tests (unit, integration) are passing in CI
- [ ] Security scanning in CI is passing
- [ ] Manual testing notes or scenarios provided for complex changes
- [ ] Known limitations or out-of-scope items are documented in the PR

---

## 4. QA / Review → Release Handoff
*From: QA / Reviewers → To: Project Manager + DevOps/SRE*

- [ ] All acceptance criteria verified and sign-off recorded
- [ ] Regression tests passed (automated and/or manual)
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- [ ] Security/Compliance sign-off obtained (if required)
- [ ] Customer Support notified of upcoming release and provided with release notes

---

## 5. Release → Post-Release Handoff
*From: DevOps/SRE + Project Manager → To: Developers + Customer Support*

- [ ] Deployment completed and post-deploy verifications passed
- [ ] Release announcement published to stakeholders and support team
- [ ] Monitoring dashboards and alerts confirmed active
- [ ] Known issues and workarounds communicated to Customer Support
- [ ] Incident escalation path confirmed and on-call schedule updated if needed
- [ ] Retrospective / post-mortem scheduled (if applicable)

---

## 6. Sprint / Project Close Handoff
*From: Scrum Master / Project Manager → To: All Roles*

- [ ] Sprint retrospective completed and action items logged
- [ ] Risk register updated with resolved and new risks
- [ ] RAID log reviewed (see [RAID Log Template](octoacme-raid-log-template.md))
- [ ] Any carry-over work moved to next sprint backlog or parking lot
- [ ] Documentation updated to reflect shipped changes
- [ ] Lessons learned captured for future reference

---

## Notes
- Handoff checklists should be attached to the relevant GitHub Issue, PR, or project board card.
- If a handoff item is blocked, escalate immediately rather than waiting for the next standup.
- See [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for role descriptions and interaction guidance.
- See [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths.
