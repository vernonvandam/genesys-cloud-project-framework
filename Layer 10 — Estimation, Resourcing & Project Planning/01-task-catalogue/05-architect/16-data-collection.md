# Layer 10 — 2.05.16 Data Collection

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.16 |
| Capability | Data Collection |
| Task Catalogue ID | 05.16 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Collect, validate and use customer-provided information within Architect flows.

## Source Implementation Activities

1. Define data collection requirements.
2. Configure input collection.
3. Validate collected data.

## Implementation Tasks

### Activity 01 — Define Data Collection

#### L10-05.16-001 — Define Data Collection Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define required customer data, formats, validation, storage and downstream use.

**Dependencies**

- Customer journey requirements

**Deliverable**

Data collection specification.

**Acceptance Criteria**

Data requirements are approved.

---

#### L10-05.16-002 — Configure Data Collection

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure customer input collection, validation and variable assignment.

**Dependencies**

- L10-05.16-001

**Deliverable**

Configured data collection.

**Acceptance Criteria**

Inputs are collected and validated according to requirements.

---

#### L10-05.16-003 — Validate Data Collection

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate valid, invalid, missing and malformed inputs.

**Dependencies**

- L10-05.16-002

**Deliverable**

Data collection test evidence.

**Acceptance Criteria**

All defined input scenarios pass.