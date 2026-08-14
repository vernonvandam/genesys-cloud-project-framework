# Layer 10 — 2.13.06 Data Profiling

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.06 |
| Capability | Data Profiling |
| Task Catalogue ID | 13.06 |
| Primary Layer 1 Phases | P02, P03, P08 |

## Capability Objective

Determine the quality, completeness, consistency, volume and suitability of source data for migration.

## Source Implementation Activities

1. Profile source data.
2. Identify data-quality issues.
3. Establish baseline metrics.

## Implementation Tasks

### L10-13.06-001 — Profile Source Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Profile source data for structure, volume, completeness and consistency.

**Dependencies**

- Data discovery
- Source access

**Deliverable**

Data profiling report.

**Acceptance Criteria**

Required profiling metrics are captured.

### L10-13.06-002 — Identify Data Quality Exceptions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify invalid, incomplete, duplicate, inconsistent or obsolete data.

**Dependencies**

- L10-13.06-001

**Deliverable**

Data quality exception register.

**Acceptance Criteria**

Material quality issues are documented and classified.

### L10-13.06-003 — Validate Profiling Results

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate that profiling results accurately represent migration data.

**Dependencies**

- L10-13.06-002

**Deliverable**

Validated profiling results.

**Acceptance Criteria**

Data owners accept the profiling baseline.

## Definition of Done

Data quality and volume characteristics are documented and accepted.

---
