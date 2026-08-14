# Layer 10 — 2.13.32 Quality Data Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.32 |
| Capability | Quality Data Migration |
| Task Catalogue ID | 13.32 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Determine how historical evaluations, quality records and quality-management data will transition.

## Implementation Tasks

### L10-13.32-001 — Assess Quality Data Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Quality Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess historical evaluations, scorecards, calibration and quality records.

**Dependencies**

- Quality requirements
- Migration scope

**Deliverable**

Quality migration assessment.

**Acceptance Criteria**

Quality data disposition is agreed.

### L10-13.32-002 — Implement Quality Data Transition

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Quality Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Migrate, recreate or archive quality data according to the approved approach.

**Dependencies**

- L10-13.32-001

**Deliverable**

Quality data transition.

**Acceptance Criteria**

Required quality history is available.

### L10-13.32-003 — Validate Quality Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Quality Specialist |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate historical quality records and access.

**Dependencies**

- L10-13.32-002

**Deliverable**

Quality validation evidence.

**Acceptance Criteria**

Required quality data passes acceptance.

## Definition of Done

Quality data transition is complete and accepted.

---