# Layer 10 — 2.13.16 Data Extraction

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.16 |
| Capability | Data Extraction |
| Task Catalogue ID | 13.16 |
| Primary Layer 1 Phases | P05, P06, P08, P10 |

## Capability Objective

Extract migration data from approved source systems using controlled and repeatable methods.

## Source Implementation Activities

1. Establish source access.
2. Develop extraction process.
3. Validate extracts.

## Implementation Tasks

### L10-13.16-001 — Establish Source Extraction Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Establish authorised access required to extract migration data.

**Dependencies**

- Source system inventory
- Security requirements

**Deliverable**

Validated extraction access.

**Acceptance Criteria**

Required source data can be accessed securely.

### L10-13.16-002 — Implement Data Extraction

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Data Engineer |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Implement repeatable extraction procedures.

**Dependencies**

- L10-13.16-001
- Migration mapping

**Deliverable**

Extraction process.

**Acceptance Criteria**

Required datasets can be extracted consistently.

### L10-13.16-003 — Validate Extracted Data

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

Validate extract completeness, integrity and volume.

**Dependencies**

- L10-13.16-002

**Deliverable**

Extraction validation report.

**Acceptance Criteria**

Extracts satisfy completeness and integrity criteria.

## Definition of Done

Approved migration datasets can be extracted repeatably and securely.

---
