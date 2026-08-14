# Layer 10 — 2.07.25 Real-Time Adherence

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.25 |
| Capability | Real-Time Adherence |
| Task Catalogue ID | 07.25 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P11 |

## Capability Objective

Configure real-time adherence capabilities to identify deviations between scheduled and actual agent activity.

## Source Implementation Activities

1. Define adherence requirements.
2. Define adherence states.
3. Configure adherence.
4. Define exception handling.
5. Validate real-time behaviour.

## Implementation Tasks

### Activity 01 — Define Adherence

#### L10-07.25-001 — Define Adherence Requirements

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

Define adherence objectives, monitored populations and operational thresholds.

**Dependencies**

- Scheduling model
- Intraday model

**Deliverable**

Adherence requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-07.25-002 — Define Adherence States and Rules

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

Map scheduled activities to expected real-time states and exceptions.

**Dependencies**

- L10-07.25-001
- Activity catalogue

**Deliverable**

Adherence rules.

**Acceptance Criteria**

Rules are approved.

### Activity 02 — Configure and Validate

#### L10-07.25-003 — Configure Real-Time Adherence

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the approved adherence model.

**Dependencies**

- L10-07.25-002

**Deliverable**

Configured adherence capability.

**Acceptance Criteria**

Adherence monitoring is available.

#### L10-07.25-004 — Validate Adherence Scenarios

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

Test on-schedule, late, early, unavailable and incorrect-state scenarios.

**Dependencies**

- L10-07.25-003

**Deliverable**

Adherence test evidence.

**Acceptance Criteria**

Adherence states and exceptions are correctly identified.