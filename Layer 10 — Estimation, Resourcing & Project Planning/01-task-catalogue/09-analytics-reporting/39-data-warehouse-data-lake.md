# Layer 10 — 2.09.39 Data Warehouse & Data Lake

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.39 |
| Capability | Data Warehouse & Data Lake |
| Task Catalogue ID | 09.39 |
| Primary Layer 1 Phases | P03, P04, P07, P08 |

## Capability Objective

Integrate Genesys Cloud analytics data with enterprise warehouse or data lake platforms where required.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define warehouse requirements |
| P04 | Design integration architecture |
| P07 | Implement integration |
| P08 | Validate data |

## Source Implementation Activities

1. Define target platform.
2. Define data requirements.
3. Design ingestion.
4. Implement pipeline.
5. Validate.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-39-001 — Define Data Warehouse or Lake Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define enterprise data platform requirements for Genesys Cloud data.

**Dependencies**

- L10-09-38-001

**Deliverable**

Data platform requirements.

**Acceptance Criteria**

Target platform and data requirements are approved.

### Activity 02 — Design

#### L10-09-39-002 — Design Data Platform Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | NO |

**Description**

Design ingestion, storage, transformation and retention architecture.

**Dependencies**

- L10-09-39-001

**Deliverable**

Data platform design.

**Acceptance Criteria**

Architecture is approved.

### Activity 03 — Implement

#### L10-09-39-003 — Implement Data Warehouse or Lake Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | CONDITIONAL |
| Baseline Effort | 8.0h |
| Critical Path | NO |

**Description**

Implement the approved Genesys Cloud data ingestion pipeline.

**Dependencies**

- L10-09-39-002

**Deliverable**

Data platform integration.

**Acceptance Criteria**

Required data is successfully ingested.

### Activity 04 — Validation

#### L10-09-39-004 — Validate Data Platform Integration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Validate completeness, accuracy and transformation of ingested data.

**Dependencies**

- L10-09-39-003

**Deliverable**

Data platform validation.

**Acceptance Criteria**

Data reconciles to Genesys Cloud source data.

## Capability-Level Dependencies

- Data extraction
- Analytics APIs
- Enterprise data platform
- Security

## Capability-Level Estimation Considerations

Effort can be significant depending on data platform architecture, pipelines and historical data.

## Definition of Done

Genesys Cloud data is successfully integrated and validated in the enterprise data platform where required.