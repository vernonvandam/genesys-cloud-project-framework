# Layer 10 — 2.14.58 BAU Transition

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.58 |
| Capability | BAU Transition |
| Task Catalogue ID | 14.58 |
| Primary Layer 1 Phases | P11, P12 |

## Capability Objective

Transition the Genesys Cloud service from project delivery into normal BAU operation.

## Implementation Tasks

### L10-14.58-001 — Prepare BAU Transition Plan

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the transition activities, ownership, dates and dependencies for BAU.

**Dependencies**

- Hypercare exit
- Operational handover

**Deliverable**

BAU transition plan.

**Acceptance Criteria**

Transition plan is approved.

### L10-14.58-002 — Execute BAU Transition

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute the transfer of operational processes, ownership, support and governance into BAU.

**Dependencies**

- L10-14.58-001
- Hypercare exit
- Handover

**Deliverable**

BAU transition record.

**Acceptance Criteria**

BAU teams assume agreed responsibilities.

### L10-14.58-003 — Validate BAU Transition

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate that normal support and governance are operating after transition.

**Dependencies**

- L10-14.58-002

**Deliverable**

BAU transition validation.

**Acceptance Criteria**

BAU operation is stable and accepted.

## Definition of Done

The service has transitioned successfully into BAU.

---
