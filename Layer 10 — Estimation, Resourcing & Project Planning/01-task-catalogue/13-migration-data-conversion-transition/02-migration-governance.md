# Layer 10 — 2.13.02 Migration Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.02 |
| Capability | Migration Governance |
| Task Catalogue ID | 13.02 |
| Primary Layer 1 Phases | P01, P03, P04, P08, P10, P12 |

## Capability Objective

Establish governance, decision rights, approvals, reporting and escalation mechanisms for migration.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish governance ownership |
| P03 | Define migration governance requirements |
| P04 | Establish governance model |
| P08 | Govern migration testing |
| P10 | Govern cutover approval |
| P12 | Complete governance closure |

## Source Implementation Activities

1. Establish migration governance.
2. Define decision rights and approvals.
3. Establish migration reporting.
4. Govern cutover and closure.

## Implementation Tasks

### L10-13.02-001 — Establish Migration Governance Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define migration governance, decision rights, escalation paths and approval authorities.

**Dependencies**

- L10-13.01-001

**Deliverable**

Migration governance model.

**Acceptance Criteria**

Governance structure and decision rights are approved.

### L10-13.02-002 — Establish Migration Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define migration status reporting, metrics, risks, issues and decision reporting.

**Dependencies**

- L10-13.02-001

**Deliverable**

Migration reporting model.

**Acceptance Criteria**

Reporting requirements are agreed.

### L10-13.02-003 — Establish Migration Approval Gates

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define formal approval gates for mock migration, rehearsal, cutover, production validation and closure.

**Dependencies**

- L10-13.02-001

**Deliverable**

Migration approval gates.

**Acceptance Criteria**

All required migration gates and approvers are documented.

## Capability-Level Dependencies

- Migration strategy
- Project governance
- Customer governance model

## Capability-Level Estimation Considerations

Effort increases with governance complexity, number of stakeholders and migration waves.

## Definition of Done

Migration governance, reporting and approval gates are established.

---
