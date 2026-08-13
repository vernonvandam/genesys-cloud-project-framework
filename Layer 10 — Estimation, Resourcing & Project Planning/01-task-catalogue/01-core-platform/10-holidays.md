# Layer 10 — 2.01.10 Holidays

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.10 |
| Capability | Holidays |
| Task Catalogue ID | 01.10 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define and configure holiday schedules and exceptions required to support accurate routing, schedules, customer communications, and operational processes.

## Source Implementation Activities

1. Identify holiday requirements.
2. Obtain approved holiday calendars.
3. Design holiday schedule structure.
4. Configure holidays.
5. Associate holidays with applicable schedules.
6. Validate holiday behaviour.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.10-001 — Identify Holiday Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Identify holiday calendars and exceptions required across locations, business units, services, and operating schedules.

**Dependencies**

- Business-hour requirements

**Deliverable**

Holiday requirements.

**Acceptance Criteria**

All required holiday calendars are identified.

#### L10-01.10-002 — Obtain Approved Holiday Calendars

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

Obtain customer-approved holiday dates and exceptions.

**Dependencies**

- L10-01.10-001

**Deliverable**

Approved holiday dataset.

**Acceptance Criteria**

Customer approves holiday data.

### Activity 02 — Design

#### L10-01.10-003 — Design Holiday Schedule Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define holiday schedule structure and its relationship to business-hour schedules.

**Dependencies**

- L10-01.10-002

**Deliverable**

Holiday schedule design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Configure

#### L10-01.10-004 — Configure Holiday Calendars

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | 0.25h per holiday group |
| Critical Path | YES |

**Description**

Configure approved holiday schedules.

**Dependencies**

- L10-01.10-003

**Deliverable**

Configured holiday schedules.

**Acceptance Criteria**

Holiday configuration matches approved data.

#### L10-01.10-005 — Associate Holidays with Operating Schedules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | YES |

**Description**

Associate configured holiday schedules with the applicable business-hour schedules.

**Dependencies**

- L10-01.10-004
- L10-01.09-004

**Deliverable**

Schedule/holiday associations.

**Acceptance Criteria**

All applicable operating schedules reference the correct holiday configuration.

### Activity 04 — Validate

#### L10-01.10-006 — Validate Holiday Behaviour

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

Validate that holiday periods produce the intended routing and schedule behaviour.

**Dependencies**

- L10-01.10-005

**Deliverable**

Holiday validation evidence.

**Acceptance Criteria**

Holiday behaviour passes defined test scenarios.

## Estimation Considerations

Drivers include:

- number of holiday calendars
- number of dates
- number of associated schedules
- regional complexity
- annual maintenance requirements

## Definition of Done

Holiday calendars are approved, configured, associated, validated, and documented.