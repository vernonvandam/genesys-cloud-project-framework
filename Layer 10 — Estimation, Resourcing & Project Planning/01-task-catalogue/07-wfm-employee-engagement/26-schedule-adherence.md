# Layer 10 — 2.07.26 Schedule Adherence

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.26 |
| Capability | Schedule Adherence |
| Task Catalogue ID | 07.26 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Define how schedule adherence is measured, reported, managed and improved.

## Source Implementation Activities

1. Define adherence metrics.
2. Define calculation rules.
3. Configure reporting.
4. Define exception management.
5. Validate adherence reporting.

## Implementation Tasks

### Activity 01 — Define Measurement

#### L10-07.26-001 — Define Schedule Adherence KPIs

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

Define adherence KPIs, thresholds and reporting expectations.

**Dependencies**

- Real-time adherence
- Operational KPI model

**Deliverable**

Adherence KPI catalogue.

**Acceptance Criteria**

KPIs are approved.

#### L10-07.26-002 — Define Adherence Exception Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define investigation, coaching and escalation processes for adherence exceptions.

**Dependencies**

- L10-07.26-001

**Deliverable**

Adherence exception process.

**Acceptance Criteria**

Exception process is approved.

### Activity 02 — Configure and Validate

#### L10-07.26-003 — Configure Adherence Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure the agreed adherence reporting and operational views.

**Dependencies**

- L10-07.26-001

**Deliverable**

Adherence reporting.

**Acceptance Criteria**

KPIs are available to authorised users.

#### L10-07.26-004 — Validate Adherence Reporting

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

Validate calculations, thresholds and exception reporting.

**Dependencies**

- L10-07.26-003

**Deliverable**

Adherence reporting validation.

**Acceptance Criteria**

Reported values reconcile to test scenarios.