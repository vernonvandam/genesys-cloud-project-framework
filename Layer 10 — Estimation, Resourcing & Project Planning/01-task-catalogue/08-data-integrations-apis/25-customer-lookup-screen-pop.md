# Layer 10 — 2.08.25 Customer Lookup & Screen Pop

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.25 |
| Capability | Customer Lookup & Screen Pop |
| Task Catalogue ID | 08.25 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide agents with relevant customer information and screen-pop behaviour based on interaction context.

## Implementation Tasks

### L10-08.25-001 — Define Lookup and Screen-Pop Requirements

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

Define lookup keys, customer matching rules and screen-pop requirements.

**Dependencies**

- Customer data integration

**Deliverable**

Lookup and screen-pop requirements.

**Acceptance Criteria**

Matching and display requirements are approved.

### L10-08.25-002 — Implement Customer Lookup and Screen Pop

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement lookup, matching and agent screen-pop behaviour.

**Dependencies**

- L10-08.25-001

**Deliverable**

Working customer lookup and screen pop.

**Acceptance Criteria**

Correct customer context is presented to agents.

### L10-08.25-003 — Validate Matching Scenarios

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Test exact matches, multiple matches, no match and invalid customer data.

**Dependencies**

- L10-08.25-002

**Deliverable**

Screen-pop validation evidence.

**Acceptance Criteria**

All approved matching scenarios behave correctly.