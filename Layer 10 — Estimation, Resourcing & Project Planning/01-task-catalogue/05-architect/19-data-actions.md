# Layer 10 — 2.05.19 Data Actions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.19 |
| Capability | Data Actions |
| Task Catalogue ID | 05.19 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Configure Data Actions to securely invoke external services and return data to Architect flows.

## Source Implementation Activities

1. Define Data Action requirements.
2. Configure integrations and contracts.
3. Build Data Actions.
4. Validate success and failure behaviour.

## Implementation Tasks

### Activity 01 — Define Data Action

#### L10-05.19-001 — Define Data Action Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define endpoint, authentication, request, response, timeout and error requirements.

**Dependencies**

- External system requirements

**Deliverable**

Data Action specification.

**Acceptance Criteria**

Data Action contract is approved.

---

#### L10-05.19-002 — Configure Data Action

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure the Data Action integration, request/response mappings and error handling.

**Dependencies**

- L10-05.19-001

**Deliverable**

Configured Data Action.

**Acceptance Criteria**

Data Action executes successfully against approved test data.

---

#### L10-05.19-003 — Validate Data Action

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Test successful, timeout, authentication, invalid-response and downstream failure scenarios.

**Dependencies**

- L10-05.19-002

**Deliverable**

Data Action validation evidence.

**Acceptance Criteria**

Success and failure paths behave as designed.