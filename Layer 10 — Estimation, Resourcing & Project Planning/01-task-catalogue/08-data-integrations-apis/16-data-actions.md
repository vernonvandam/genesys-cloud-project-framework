# Layer 10 — 2.08.16 Data Actions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.16 |
| Capability | Data Actions |
| Task Catalogue ID | 08.16 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Design, configure and validate Genesys Cloud Data Actions used to invoke external services from Genesys Cloud workflows.

## Implementation Tasks

### L10-08.16-001 — Identify Data Action Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify Architect, routing or workflow requirements requiring external data retrieval or updates.

**Dependencies**

- Integration inventory

**Deliverable**

Data Action requirements.

**Acceptance Criteria**

Required Data Actions are identified.

### L10-08.16-002 — Configure Data Actions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure contracts, inputs, outputs, authentication and error handling.

**Dependencies**

- L10-08.16-001

**Deliverable**

Configured Data Actions.

**Acceptance Criteria**

Data Actions execute successfully.

### L10-08.16-003 — Test Data Actions in Architect Context

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate Data Actions from consuming Architect flows and confirm expected responses and failure handling.

**Dependencies**

- L10-08.16-002

**Deliverable**

Data Action test evidence.

**Acceptance Criteria**

Data Actions operate correctly in target workflows.