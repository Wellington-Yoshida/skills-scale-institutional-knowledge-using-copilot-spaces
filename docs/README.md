# OctoAcme Project Management — Overview

A concise reference for onboarding new team members to OctoAcme's project management processes.

---

## Key Workflows

OctoAcme follows a full-lifecycle model across five phases:

1. **Initiation** — A lightweight one-pager defines the problem, goals, success metrics, stakeholders, timeline, risks, and initial team roles before any work begins.
2. **Planning** — The approved initiative is converted into a prioritized backlog with clear acceptance criteria, estimates, dependencies, a Definition of Done, and milestone-based release planning.
3. **Execution** — Teams deliver iteratively using a board-based workflow: `Backlog → Ready → In Progress → In Review → QA → Done`. Short standups, weekly delivery syncs, and milestone demos keep the team aligned. Pull requests must be small, linked to issues, pass CI, and receive required approvals before merging.
4. **Release** — Deployments are preceded by release checklists, smoke tests, and stakeholder notifications. Post-release verification and rollback/incident playbooks are in place for every release.
5. **Retrospective** — Each cycle closes with a structured retrospective that converts lessons learned into owned, time-bound action items, reinforcing continuous improvement.

---

## Personas / Roles

| Role | Responsibilities |
|------|-----------------|
| **Project Manager (PM)** | Coordinates execution, schedules, risks, and stakeholder communication. |
| **Product Manager (PdM)** | Sets direction, prioritizes the backlog, and defines measurable outcomes. |
| **Developers** | Implement and validate solutions with attention to maintainability and testability. |
| **QA / Testing** | Validates acceptance criteria and release readiness. |
| **Stakeholders** | Provide inputs, approvals, and business context throughout the lifecycle. |

---

## Communication Strategies

- **Cadence** — Twice-weekly standups for the delivery team, a weekly PM + PdM sync, and monthly stakeholder updates.
- **Status updates** — Weekly written reports cover progress, next steps, risks/blockers, and decisions needed. A single source of truth is maintained for project status.
- **Escalation** — Issues move from team triage → PM/Product Lead → sponsor-level escalation when business impact is significant.
- **Risk management** — A risk register tracks each risk with an owner, impact/likelihood rating, mitigation plan, and weekly review cadence.

---

## Quality Assurance Practices

- **Testing** — Unit, integration, and end-to-end smoke tests are required before release.
- **CI / Security scans** — All pull requests must pass automated CI pipelines and security scans before merge.
- **Release verification** — Post-release smoke tests confirm the deployment is healthy.
- **Rollback & incidents** — Rollback procedures and incident playbooks are defined and rehearsed so teams can respond quickly if issues arise.

---

*For deeper detail, see the other documents in this `docs/` folder.*
