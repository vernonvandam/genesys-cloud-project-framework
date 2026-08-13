# Layer 10 — 2.01.09 Business Hours

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.09 |
| Capability | Business Hours |
| Task Catalogue ID | 01.09 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define and configure business-hour schedules required by routing, Architect, digital, operational processes, and customer service requirements.

## Source Implementation Activities

1. Identify business-hour requirements.
2. Obtain customer schedules.
3. Design schedule model.
4. Configure business-hour schedules.
5. Validate schedule behaviour.
6. Document schedule model.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.09-001 — Identify Business Hour Requirements

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

Identify operating hours by business unit, location, queue, service, channel, and other applicable operating structures.

**Dependencies**

- Time-zone requirements

**Deliverable**

Business-hour requirements.

**Acceptance Criteria**

All required operating schedules are identified.

#### L10-01.09-002 — Obtain Approved Business Hour Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | EXTERNAL |
| Automation | IMPORT |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain customer-approved operating hours and associated schedule information.

**Dependencies**

- L10-01.09-001

**Deliverable**

Approved business-hour dataset.

**Acceptance Criteria**

Customer has approved the schedule data.

### Activity 02 — Design

#### L10-01.09-003 — Design Business Hour Schedule Model

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

Design the Genesys Cloud schedule structure and determine how schedules will be used by dependent capabilities.

**Dependencies**

- L10-01.09-002

**Deliverable**

Business-hour schedule design.

**Acceptance Criteria**

Schedule model is approved.

### Activity 03 — Configure

#### L10-01.09-004 — Configure Business Hour Schedules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | 0.5h per schedule |
| Critical Path | YES |

**Description**

Create and configure approved business-hour schedules.

**Dependencies**

- L10-01.09-003

**Deliverable**

Configured business-hour schedules.

**Acceptance Criteria**

Schedules match approved source data.

### Activity 04 — Validate

#### L10-01.09-005 — Validate Business Hour Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per schedule group |
| Critical Path | YES |

**Description**

Validate schedule behaviour, including open, closed, and exceptional periods.

**Dependencies**

- L10-01.09-004
- Holiday schedules

**Deliverable**

Schedule validation evidence.

**Acceptance Criteria**

Business-hour behaviour passes defined test scenarios.

## Estimation Considerations

Drivers include:

- number of schedules
- number of time zones
- schedule complexity
- multiple operating periods
- exceptions
- customer approval cycles
- automation approach

## Definition of Done

All approved business-hour schedules are configured, validated, and ready for dependent routing and Architect configuration.