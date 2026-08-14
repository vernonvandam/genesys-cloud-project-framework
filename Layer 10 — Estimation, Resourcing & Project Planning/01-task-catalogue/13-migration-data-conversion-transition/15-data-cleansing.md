# Layer 10 — 2.13.15 Data Cleansing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.15 |
| Capability | Data Cleansing |
| Task Catalogue ID | 13.15 |
| Primary Layer 1 Phases | P02, P03, P06, P08 |

## Capability Objective

Identify and remediate data quality issues that would prevent or compromise migration.

## Source Implementation Activities

1. Identify cleansing requirements.
2. Execute data cleansing.
3. Validate cleansed data.

## Implementation Tasks

### L10-13.15-001 — Define Data Cleansing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define mandatory data quality rules and remediation requirements.

**Dependencies**

- Data profiling

**Deliverable**

Cleansing specification.

**Acceptance Criteria**

Required quality rules are approved.

### L10-13.15-002 — Execute Data Cleansing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Cleanse source data according to approved rules.

**Dependencies**

- L10-13.15-001

**Deliverable**

Cleansed migration dataset.

**Acceptance Criteria**

Mandatory quality rules are satisfied.

### L10-13.15-003 — Validate Cleansed Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate data quality after cleansing.

**Dependencies**

- L10-13.15-002

**Deliverable**

Cleansing validation report.

**Acceptance Criteria**

Quality thresholds are met or exceptions approved.

## Definition of Done

Migration data meets agreed quality thresholds.

---
