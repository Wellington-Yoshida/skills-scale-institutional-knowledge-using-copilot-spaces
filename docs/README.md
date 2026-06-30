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

## How to Use This Docs Folder

This folder is the single source of truth for OctoAcme's project management processes. Use it to onboard new team members, refresh your understanding of a phase, or share context with Copilot Spaces.

| Document | What it covers |
|----------|---------------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and communication cadence — the best starting point. |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | How to validate and authorize new work: one-pager template, stakeholder alignment, and the go/no-go decision gate. |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog: kickoff, prioritization, estimation, Definition of Done, and release planning. |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day delivery rhythm: board workflow, PR conventions, quality and testing expectations, metrics, and blocker escalation. |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, post-release verification, and the rollback/incident playbook. |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action-item tracking, and how OctoAcme builds a continuous-improvement culture. |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths. |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each team role. |

> **Tip:** Keep this folder updated as processes evolve. If you're using Copilot Spaces, add these docs as context sources so the team can ask questions and get role-specific guidance directly from the knowledge base.
