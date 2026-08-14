# Layer 10 — 2.13.09 Data Retention

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.09 |
| Capability | Data Retention |
| Task Catalogue ID | 13.09 |
| Primary Layer 1 Phases | P03, P04, P12 |

## Capability Objective

Determine retention requirements for migrated, historical, archived and source data.

## Source Implementation Activities

1. Identify retention requirements.
2. Map retention to migration scope.
3. Define archival and deletion requirements.

## Implementation Tasks

### L10-13.09-001 — Identify Retention Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify contractual, regulatory and business retention requirements.

**Dependencies**

- Data classification
- Privacy requirements

**Deliverable**

Retention requirements.

**Acceptance Criteria**

Retention requirements are documented.

### L10-13.09-002 — Define Migration Retention Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define which records are migrated, retained in source, archived or deleted.

**Dependencies**

- L10-13.09-001

**Deliverable**

Retention decision matrix.

**Acceptance Criteria**

Disposition of retained data is defined.

### L10-13.09-003 — Validate Retention Handover

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Validate that retention responsibilities and controls are transferred to operations.

**Dependencies**

- L10-13.09-002
- Operational handover

**Deliverable**

Retention handover evidence.

**Acceptance Criteria**

Retention ownership is accepted.

## Definition of Done

Retention and disposition rules are documented and operationally owned.

---

