# Layer 10 — 2.08.32 External Data & Reference Services

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.32 |
| Capability | External Data & Reference Services |
| Task Catalogue ID | 08.32 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Enable Genesys Cloud workflows to consume trusted external reference and enrichment data.

## Implementation Tasks

### L10-08.32-001 — Identify External Reference Data Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify external data required for routing, customer interaction, validation or enrichment.

**Dependencies**

- Business requirements

**Deliverable**

External data requirements.

**Acceptance Criteria**

Required reference services are documented.

### L10-08.32-002 — Implement Reference Service Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement approved reference-data service integration.

**Dependencies**

- L10-08.32-001

**Deliverable**

Reference service integration.

**Acceptance Criteria**

Required data is retrieved successfully.

### L10-08.32-003 — Validate Reference Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate accuracy, availability, timeout and fallback behaviour.

**Dependencies**

- L10-08.32-002

**Deliverable**

Reference data validation evidence.

**Acceptance Criteria**

Approved reference scenarios pass.