# Layer 10 — 2.13.41 Data Freeze

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.41 |
| Capability | Data Freeze |
| Task Catalogue ID | 13.41 |
| Primary Layer 1 Phases | P10, P11 |
| Classification | CONDITIONAL |

## Capability Objective

Control source-system changes during the migration window to preserve data integrity.

## Implementation Tasks

### L10-13.41-001 — Define Data Freeze Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define systems, data and activities subject to freeze.

**Dependencies**

- Cutover plan
- Delta strategy

**Deliverable**

Data freeze plan.

**Acceptance Criteria**

Freeze scope and timing are approved.

### L10-13.41-002 — Execute Data Freeze

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Execute approved source-system data freeze.

**Dependencies**

- L10-13.41-001

**Deliverable**

Freeze execution record.

**Acceptance Criteria**

Freeze is confirmed by source owners.

### L10-13.41-003 — Release Data Freeze

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Migration Lead |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | CONDITIONAL |

**Description**

Release source systems after migration acceptance criteria are met.

**Dependencies**

- Production validation
- Reconciliation

**Deliverable**

Freeze release approval.

**Acceptance Criteria**

Customer authorises normal source operations.

## Definition of Done

Data freeze is controlled and formally released.

---
