# Layer 10 — 2.07.21 Time-Off Plans & Requests

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.21 |
| Capability | Time-Off Plans & Requests |
| Task Catalogue ID | 07.21 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Configure time-off plans, request windows, approval processes and workforce availability rules.

## Source Implementation Activities

1. Define time-off plans.
2. Configure request windows.
3. Define approval rules.
4. Configure plans.
5. Validate request processing.

## Implementation Tasks

### Activity 01 — Design Time-Off Plans

#### L10-07.21-001 — Define Time-Off Plans

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

Define time-off plans and applicable workforce populations.

**Dependencies**

- Time-off requirements

**Deliverable**

Time-off plan catalogue.

**Acceptance Criteria**

Plans are approved.

#### L10-07.21-002 — Define Request and Approval Rules

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

Define request windows, approval responsibilities, quotas and scheduling constraints.

**Dependencies**

- L10-07.21-001

**Deliverable**

Time-off rules catalogue.

**Acceptance Criteria**

Rules are approved.

### Activity 02 — Configure and Test

#### L10-07.21-003 — Configure Time-Off Plans

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved time-off plans and rules.

**Dependencies**

- L10-07.21-002

**Deliverable**

Configured time-off plans.

**Acceptance Criteria**

Plans are available to intended workforce groups.

#### L10-07.21-004 — Validate Time-Off Request Processing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate employee request, supervisor approval and schedule impact.

**Dependencies**

- L10-07.21-003

**Deliverable**

Request-processing validation.

**Acceptance Criteria**

Requests process correctly.