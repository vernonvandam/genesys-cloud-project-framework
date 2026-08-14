# Layer 10 — 2.07.04 Business Units

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.04 |
| Capability | Business Units |
| Task Catalogue ID | 07.04 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P12 |

## Capability Objective

Define and configure WFM business units aligned to the customer's operational workforce model.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover organisational workforce structure |
| P03 | Define business-unit requirements |
| P04 | Design business-unit model |
| P05 | Configure business units |
| P08 | Validate business-unit configuration |
| P12 | Handover final model |

## Source Implementation Activities

1. Identify business units.
2. Define business-unit hierarchy.
3. Configure business units.
4. Validate relationships and ownership.
5. Document final configuration.

## Implementation Tasks

### Activity 01 — Discover and Design

#### L10-07.04-001 — Identify WFM Business Units

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify operational business units that require distinct WFM management.

**Dependencies**

- Workforce discovery
- Core Platform organisation model

**Deliverable**

Business-unit inventory.

**Acceptance Criteria**

All required business units are identified.

#### L10-07.04-002 — Define Business-Unit Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define naming, ownership, time zones, workforce populations and operational relationships.

**Dependencies**

- L10-07.04-001

**Deliverable**

Approved business-unit design.

**Acceptance Criteria**

Business-unit model is approved.

### Activity 02 — Configure and Validate

#### L10-07.04-003 — Configure Business Units

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Configure the approved business-unit model.

**Dependencies**

- L10-07.04-002

**Deliverable**

Configured business units.

**Acceptance Criteria**

Business units match the approved design.

#### L10-07.04-004 — Validate Business Units

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate business-unit relationships, ownership and workforce assignment.

**Dependencies**

- L10-07.04-003

**Deliverable**

Business-unit validation evidence.

**Acceptance Criteria**

Business units operate as designed.

#### L10-07.04-005 — Document Business-Unit Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document final business-unit configuration and operational ownership.

**Dependencies**

- L10-07.04-004

**Deliverable**

Business-unit configuration record.

**Acceptance Criteria**

Documentation is accepted for BAU.