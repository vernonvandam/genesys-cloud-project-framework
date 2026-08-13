# Layer 10 — 2.01.05 Business Units

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.05 |
| Capability | Business Units |
| Task Catalogue ID | 01.05 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08 |

## Capability Objective

Define and configure business-unit structures required to represent the customer's operational model and support applicable workforce, analytics, and administrative requirements.

## Source Implementation Activities

1. Identify business unit requirements.
2. Design business unit model.
3. Configure business units.
4. Configure associated settings.
5. Validate business unit structure.
6. Document configuration.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.05-001 — Identify Business Unit Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify business units, operational ownership, reporting requirements, workforce management requirements, and organisational boundaries.

**Dependencies**

- L10-01.01-006

**Deliverable**

Business unit requirements.

**Acceptance Criteria**

Requirements are confirmed by the customer.

### Activity 02 — Design

#### L10-01.05-002 — Design Business Unit Structure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the target business unit structure and its relationship to operational and workforce requirements.

**Dependencies**

- L10-01.05-001

**Deliverable**

Business unit design.

**Acceptance Criteria**

Target structure is approved.

### Activity 03 — Configure

#### L10-01.05-003 — Create Business Units

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | 0.25h per business unit |
| Critical Path | YES |

**Description**

Create approved business units.

**Dependencies**

- L10-01.05-002

**Deliverable**

Configured business units.

**Acceptance Criteria**

All approved business units are created correctly.

### Activity 04 — Configure Business Unit Settings

#### L10-01.05-004 — Configure Business Unit Settings

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | CONDITIONAL |

**Description**

Configure applicable business unit settings based on the target operating model.

**Dependencies**

- L10-01.05-003

**Deliverable**

Configured business unit settings.

**Acceptance Criteria**

Settings conform to approved design.

### Activity 05 — Validate

#### L10-01.05-005 — Validate Business Units

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate business unit configuration and associated operational behaviour.

**Dependencies**

- L10-01.05-004

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Business units pass functional and configuration validation.

## Estimation Considerations

Drivers include:

- number of business units
- workforce management requirements
- operational complexity
- reporting requirements
- configuration volume

## Definition of Done

Business units are designed, configured, validated, documented, and available to dependent capabilities.