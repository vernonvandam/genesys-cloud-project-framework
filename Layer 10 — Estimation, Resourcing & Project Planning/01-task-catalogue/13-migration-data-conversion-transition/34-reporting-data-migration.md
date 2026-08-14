# Layer 10 — 2.13.34 Reporting Data Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.34 |
| Capability | Reporting Data Migration |
| Task Catalogue ID | 13.34 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Transition historical reporting data, metrics, datasets and reporting dependencies.

## Implementation Tasks

### L10-13.34-001 — Assess Reporting History Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess reporting history, retention, regulatory and analytical requirements.

**Dependencies**

- Reporting requirements
- Data retention

**Deliverable**

Reporting migration assessment.

**Acceptance Criteria**

Historical reporting disposition is agreed.

### L10-13.34-002 — Implement Reporting Data Transition

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Migrate, transform or retain historical reporting datasets.

**Dependencies**

- L10-13.34-001

**Deliverable**

Reporting data transition.

**Acceptance Criteria**

Required historical reporting data is available.

### L10-13.34-003 — Validate Reporting Continuity

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate reporting continuity and agreed historical metrics.

**Dependencies**

- L10-13.34-002

**Deliverable**

Reporting validation results.

**Acceptance Criteria**

Customer accepts reporting continuity.

## Definition of Done

Reporting data transition is complete and accepted.

---
