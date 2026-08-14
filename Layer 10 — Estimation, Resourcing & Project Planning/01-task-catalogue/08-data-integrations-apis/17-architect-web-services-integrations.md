# Layer 10 — 2.08.17 Architect Web Services & Integrations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.17 |
| Capability | Architect Web Services & Integrations |
| Task Catalogue ID | 08.17 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Implement external web-service integrations consumed directly by Genesys Cloud Architect workflows.

## Implementation Tasks

### L10-08.17-001 — Identify Architect Web-Service Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify Architect flows requiring external web-service access.

**Dependencies**

- Architect requirements
- Integration inventory

**Deliverable**

Architect web-service requirements.

**Acceptance Criteria**

Required integrations are documented.

### L10-08.17-002 — Configure Web-Service Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure the approved web-service integration and response handling.

**Dependencies**

- L10-08.17-001

**Deliverable**

Configured Architect integration.

**Acceptance Criteria**

Web-service requests and responses operate as designed.

### L10-08.17-003 — Validate Web-Service Failure Handling

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Test successful, timeout, unavailable and invalid-response scenarios.

**Dependencies**

- L10-08.17-002

**Deliverable**

Web-service validation evidence.

**Acceptance Criteria**

Failure scenarios produce approved customer experience.