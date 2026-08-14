# Layer 10 — 2.14.30 Data Operations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.30 |
| Capability | Data Operations |
| Task Catalogue ID | 14.30 |
| Primary Layer 1 Phases | P07, P09, P11, P12 |

## Capability Objective

Establish operational management of Genesys Cloud data flows, extracts, storage and data quality.

## Implementation Tasks

### L10-14.30-001 — Define Data Operations Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify operational datasets, data flows, ownership, retention and data quality requirements.

**Dependencies**

- Data architecture
- Integration architecture

**Deliverable**

Data operations model.

**Acceptance Criteria**

Material data flows and owners are identified.

### L10-14.30-002 — Establish Data Operations Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Document data monitoring, extraction, reconciliation, retention and issue management.

**Dependencies**

- L10-14.30-001

**Deliverable**

Data operations procedures.

**Acceptance Criteria**

Priority data operational processes are documented.

### L10-14.30-003 — Validate Data Operations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate operational data processes and reconciliation.

**Dependencies**

- L10-14.30-002

**Deliverable**

Data operations validation.

**Acceptance Criteria**

Required data processes operate successfully.

## Definition of Done

Data operations are controlled, monitored and supportable.

---
