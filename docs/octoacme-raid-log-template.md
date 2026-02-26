# OctoAcme — RAID Log Template

## Purpose
Track Risks, Assumptions, Issues, and Dependencies in a single, easy-to-maintain log. Update this log at each weekly sync and review it ahead of major milestones.

---

## How to Use
- Copy this template into your project's `docs/` folder or link it from your Project One-pager.
- Assign an Owner to each item — unowned items are not tracked.
- Review and update Status at every weekly sync.
- Escalate High-impact items to the appropriate stakeholder immediately; do not wait for the next review.

---

## Risks

| ID | Description | Impact (H/M/L) | Likelihood (H/M/L) | Owner | Mitigation Plan | Status |
|----|-------------|----------------|--------------------|-------|-----------------|--------|
| R1 | *(e.g., Key engineer out of office during critical sprint)* | H | M | Project Manager | Identify backup resource; document knowledge | Open |
| R2 | | | | | | |

> See [Risk Management & Communication](octoacme-risks-and-communication.md) for the full risk lifecycle and escalation paths.

---

## Assumptions

| ID | Description | Owner | Validation Date | Status |
|----|-------------|-------|-----------------|--------|
| A1 | *(e.g., External API will remain stable through Q3)* | Tech Lead | 2026-03-31 | Open |
| A2 | | | | |

> If an assumption is invalidated, convert it to a Risk or Issue and update the Owner immediately.

---

## Issues

| ID | Description | Impact (H/M/L) | Owner | Resolution Plan | Target Date | Status |
|----|-------------|----------------|-------|-----------------|-------------|--------|
| I1 | *(e.g., Staging environment unavailable — blocking QA)* | H | DevOps/SRE | Rebuild staging from IaC; ETA 2 days | 2026-03-05 | In Progress |
| I2 | | | | | | |

> Active High-impact Issues should be escalated per the [Blocker Escalation](octoacme-execution-and-tracking.md) levels in the Execution & Tracking guide.

---

## Dependencies

| ID | Description | Type (Internal/External) | Dependent On (Team/System) | Owner | Required By | Status |
|----|-------------|--------------------------|---------------------------|-------|-------------|--------|
| D1 | *(e.g., Auth service API contract finalized by Platform team)* | Internal | Platform Engineering | Tech Lead | 2026-03-15 | Pending |
| D2 | | | | | | |

> Flag unresolved dependencies in the weekly sync and in the Project One-pager when they affect the critical path.

---

## Log History

| Date | Updated By | Summary of Changes |
|------|------------|--------------------|
| YYYY-MM-DD | *(name/role)* | Initial log created |
| | | |

---

## Notes
- Keep entries concise and actionable — if an item needs a full write-up, link to a separate document.
- Archive resolved items at the end of each sprint rather than deleting them (move to a "Resolved" section below).
- See [Role Handoff Checklist](octoacme-role-handoff-checklist.md) — the RAID log is reviewed as part of the Sprint/Project Close Handoff.
- See [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for the full key artifacts list.
