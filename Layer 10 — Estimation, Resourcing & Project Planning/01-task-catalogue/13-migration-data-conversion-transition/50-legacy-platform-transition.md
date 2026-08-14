# Layer 10 — 2.13.50 Legacy Platform Transition

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.50 |
| Capability | Legacy Platform Transition |
| Task Catalogue ID | 13.50 |
| Primary Layer 1 Phases | P10, P11, P12 |

## Capability Objective

Control the transition from the legacy contact centre platform to Genesys Cloud.

## Implementation Tasks

### L10-13.50-001 — Define Legacy Transition Plan

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define legacy platform transition timing, dependencies, ownership and exit conditions.

**Dependencies**

- Migration approach
- Cutover plan

**Deliverable**

Legacy transition plan.

**Acceptance Criteria**

Transition plan is approved.

### L10-13.50-002 — Execute Legacy Transition

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Move operational activity from legacy platform to Genesys Cloud.

**Dependencies**

- Production migration
- Production validation

**Deliverable**

Legacy transition record.

**Acceptance Criteria**

Approved workloads operate on Genesys Cloud.

### L10-13.50-003 — Confirm Legacy Exit

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Customer Platform Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm legacy operational dependencies have been removed or accepted.

**Dependencies**

- L10-13.50-002
- Legacy decommissioning readiness

**Deliverable**

Legacy exit approval.

**Acceptance Criteria**

Customer approves legacy platform transition.

## Definition of Done

Legacy platform transition is complete and approved.

---
