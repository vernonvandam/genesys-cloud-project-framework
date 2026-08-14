# Layer 10 — 2.09.28 Historical Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.28 |
| Capability | Historical Reporting |
| Task Catalogue ID | 09.28 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide reliable historical reporting across agreed reporting periods and data retention windows.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define historical requirements |
| P04 | Define historical reporting model |
| P06 | Configure reports |
| P08 | Validate history |

## Source Implementation Activities

1. Define history requirements.
2. Define retention periods.
3. Configure historical reports.
4. Validate historical results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-28-001 — Define Historical Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define required historical reporting periods, dimensions and measures.

**Dependencies**

- L10-09-02-002

**Deliverable**

Historical reporting requirements.

**Acceptance Criteria**

Historical requirements are approved.

### Activity 02 — Configuration

#### L10-09-28-002 — Configure Historical Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure historical reports and required filters.

**Dependencies**

- L10-09-28-001

**Deliverable**

Historical reporting.

**Acceptance Criteria**

Required history is accessible.

### Activity 03 — Validation

#### L10-09-28-003 — Validate Historical Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate historical reports against known source results.

**Dependencies**

- L10-09-28-002

**Deliverable**

Historical validation evidence.

**Acceptance Criteria**

Historical reporting is accurate within agreed tolerances.

## Capability-Level Dependencies

- Analytics
- Data retention
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on history periods, report count and external historical data requirements.

## Definition of Done

Historical reporting is configured and validated.