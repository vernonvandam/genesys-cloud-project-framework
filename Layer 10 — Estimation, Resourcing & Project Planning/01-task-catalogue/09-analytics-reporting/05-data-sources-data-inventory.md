# Layer 10 — 2.09.05 Data Sources & Data Inventory

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.05 |
| Capability | Data Sources & Data Inventory |
| Task Catalogue ID | 09.05 |
| Primary Layer 1 Phases | P02, P03, P04, P07 |

## Capability Objective

Identify, classify and document all data sources required to support Genesys Cloud reporting and analytics.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover existing sources |
| P03 | Define data requirements |
| P04 | Design data architecture |
| P07 | Integrate external sources |

## Source Implementation Activities

1. Inventory data sources.
2. Classify data.
3. Identify source systems.
4. Map data requirements.
5. Define integration requirements.

## Implementation Tasks

### Activity 01 — Inventory

#### L10-09-05-001 — Inventory Analytics Data Sources

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Inventory Genesys Cloud and external data sources supporting reporting.

**Dependencies**

- L10-09-02-002

**Deliverable**

Data source inventory.

**Acceptance Criteria**

Relevant data sources are documented.

### Activity 02 — Classification

#### L10-09-05-002 — Classify Analytics Data Sources

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

Classify sources according to ownership, sensitivity, latency and authority.

**Dependencies**

- L10-09-05-001

**Deliverable**

Classified data inventory.

**Acceptance Criteria**

Source classification is complete.

### Activity 03 — Mapping

#### L10-09-05-003 — Map Reporting Requirements to Data Sources

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Map reporting requirements and KPIs to authoritative data sources.

**Dependencies**

- L10-09-05-002

**Deliverable**

Data source mapping.

**Acceptance Criteria**

Required metrics have identified source data.

### Activity 04 — Integration

#### L10-09-05-004 — Establish Required Data Source Connections

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Establish required access or integration to external reporting sources.

**Dependencies**

- L10-09-05-003

**Deliverable**

Configured data source connectivity.

**Acceptance Criteria**

Required data sources are accessible.

## Capability-Level Dependencies

- Reporting requirements
- KPI framework
- Data architecture
- Integration architecture

## Capability-Level Estimation Considerations

External systems, security requirements and data source count significantly affect effort.

## Definition of Done

All required analytics data sources are inventoried, classified, mapped and accessible.