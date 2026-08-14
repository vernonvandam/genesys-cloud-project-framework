# Layer 10 — 10.12 Data Quality Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.12 |
| Capability | Data Quality Governance |
| Task Catalogue ID | 10.12 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Ensure planning and estimation data is complete, accurate, consistent and traceable.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define data quality requirements |
| P04 | Establish quality controls |
| P09 | Validate planning data |
| P12 | Review final data quality |

## Source Implementation Activities

1. Define data-quality rules.
2. Establish validation controls.
3. Validate planning data.
4. Correct exceptions.
5. Review data quality.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.12-001 — Define Planning Data Quality Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define mandatory completeness, validity, consistency and traceability rules.

**Dependencies**

- Task standard
- Spreadsheet model

**Deliverable**

Data quality rules.

**Acceptance Criteria**

Required quality rules are documented.

### Activity 02 — Validate

#### L10-10.12-002 — Validate Task Catalogue Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P04 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Check task IDs, roles, effort, mappings, dependencies and acceptance criteria.

**Dependencies**

- L10-10.12-001

**Deliverable**

Data quality report.

**Acceptance Criteria**

Critical defects are identified.

### Activity 03 — Correct

#### L10-10.12-003 — Correct Data Quality Exceptions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Resolve identified quality defects.

**Dependencies**

- L10-10.12-002

**Deliverable**

Corrected planning dataset.

**Acceptance Criteria**

Critical defects are resolved.

### Activity 04 — Validate

#### L10-10.12-004 — Validate Final Planning Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Confirm final project planning data remains complete and traceable.

**Dependencies**

- L10-10.12-003

**Deliverable**

Final data quality validation.

**Acceptance Criteria**

No unresolved critical data defects remain.

## Capability-Level Dependencies

- Task catalogue
- Estimation model
- Spreadsheet model

## Capability-Level Estimation Considerations

Effort depends on dataset size and degree of automation.

## Definition of Done

Planning data is validated, corrected and traceable.

---