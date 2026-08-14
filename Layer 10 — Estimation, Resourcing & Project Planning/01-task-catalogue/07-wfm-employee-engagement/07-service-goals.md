# Layer 10 — 2.07.07 Service Goals

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.07 |
| Capability | Service Goals |
| Task Catalogue ID | 07.07 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P12 |

## Capability Objective

Define service goals used to drive staffing, forecasting and schedule requirements.

## Source Implementation Activities

1. Discover service objectives.
2. Define service-level targets.
3. Map service goals to planning groups.
4. Configure service goals.
5. Validate planning behaviour.

## Implementation Tasks

### Activity 01 — Define Service Goals

#### L10-07.07-001 — Capture Service-Level Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Capture service-level, response-time, abandonment and operational targets.

**Dependencies**

- Business requirements
- ACD routing requirements

**Deliverable**

Service-goal requirements.

**Acceptance Criteria**

Targets are documented and approved.

#### L10-07.07-002 — Map Service Goals to Planning Groups

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Determine which service goals apply to each planning group.

**Dependencies**

- L10-07.07-001
- Planning-group design

**Deliverable**

Service-goal mapping.

**Acceptance Criteria**

Every applicable planning group has an approved target.

### Activity 02 — Configure and Validate

#### L10-07.07-003 — Configure Service Goals

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Configure approved service goals.

**Dependencies**

- L10-07.07-002

**Deliverable**

Configured service goals.

**Acceptance Criteria**

Configured values match approved targets.

#### L10-07.07-004 — Validate Service Goals

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate service goals are correctly applied to workforce planning.

**Dependencies**

- L10-07.07-003

**Deliverable**

Service-goal validation evidence.

**Acceptance Criteria**

Service goals drive planning as expected.