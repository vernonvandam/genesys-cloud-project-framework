# Layer 10 — 2.13.43 Transition Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.43 |
| Capability | Transition Management |
| Task Catalogue ID | 13.43 |
| Primary Layer 1 Phases | P09, P10, P11, P12 |

## Capability Objective

Coordinate the organisational, operational and technical transition from legacy operations to Genesys Cloud.

## Implementation Tasks

### L10-13.43-001 — Define Transition Plan

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Transition Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define transition activities, ownership, communications and operational dependencies.

**Dependencies**

- Migration strategy
- Operational readiness

**Deliverable**

Transition plan.

**Acceptance Criteria**

Transition activities and ownership are approved.

### L10-13.43-002 — Execute Transition

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Transition Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Coordinate transition of users, operations, support and business processes.

**Dependencies**

- Production cutover
- Operational readiness

**Deliverable**

Transition execution record.

**Acceptance Criteria**

Target operating model is active.

### L10-13.43-003 — Confirm Transition Completion

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Confirm transition objectives and responsibilities have been completed.

**Dependencies**

- L10-13.43-002

**Deliverable**

Transition completion approval.

**Acceptance Criteria**

Customer accepts transition completion.

## Definition of Done

Operational transition is complete and accepted.

---