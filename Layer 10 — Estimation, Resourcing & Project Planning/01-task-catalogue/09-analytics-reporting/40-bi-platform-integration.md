# Layer 10 — 2.09.40 BI Platform Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.40 |
| Capability | BI Platform Integration |
| Task Catalogue ID | 09.40 |
| Primary Layer 1 Phases | P03, P04, P07, P08 |

## Capability Objective

Integrate Genesys Cloud analytics data with enterprise business intelligence platforms.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define BI requirements |
| P04 | Design BI integration |
| P07 | Implement integration |
| P08 | Validate BI reporting |

## Source Implementation Activities

1. Identify BI platform.
2. Define datasets.
3. Design integration.
4. Build data connection.
5. Validate dashboards.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-40-001 — Define BI Integration Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | BI Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define required BI platform integration and reporting outcomes.

**Dependencies**

- L10-09-39-001

**Deliverable**

BI requirements.

**Acceptance Criteria**

BI requirements are approved.

### Activity 02 — Design

#### L10-09-40-002 — Design BI Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | BI Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Design datasets, connections, refresh and security.

**Dependencies**

- L10-09-40-001

**Deliverable**

BI integration design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Implement

#### L10-09-40-003 — Implement BI Platform Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | BI Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | CONDITIONAL |
| Baseline Effort | 6.0h |
| Critical Path | NO |

**Description**

Implement data connections and required BI datasets.

**Dependencies**

- L10-09-40-002

**Deliverable**

BI integration.

**Acceptance Criteria**

BI platform successfully accesses approved data.

### Activity 04 — Validation

#### L10-09-40-004 — Validate BI Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Validate BI calculations, refresh and dashboard results.

**Dependencies**

- L10-09-40-003

**Deliverable**

BI validation evidence.

**Acceptance Criteria**

BI reporting reconciles to approved source data.

## Capability-Level Dependencies

- Data warehouse/lake
- Analytics APIs
- BI platform
- Data model

## Capability-Level Estimation Considerations

Effort depends on BI platform, dataset count and transformation requirements.

## Definition of Done

BI integration is implemented and validated where required.