# Layer 10 — 2.04.20 Business Hours Schedule Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.20 |
| Capability | Business Hours Schedule Routing |
| Task Catalogue ID | 04.20 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Route interactions according to business operating hours and defined schedules.

## Source Implementation Activities

1. Define operating schedules.
2. Configure schedules.
3. Apply schedules to routing.
4. Validate open and closed conditions.

## Implementation Tasks

### L10-04.20-001 — Define Business Hours Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define operating hours by business unit, queue, location and channel.

**Dependencies**

- Business requirements

**Deliverable**

Business hours matrix.

**Acceptance Criteria**

Schedules are approved.

### L10-04.20-002 — Configure Business Hours Schedules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per schedule |
| Critical Path | YES |

**Description**

Create and configure business-hours schedules.

**Dependencies**

- L10-04.20-001

**Deliverable**

Configured schedules.

**Acceptance Criteria**

Schedules reflect approved operating hours.

### L10-04.20-003 — Apply Schedule Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per routing model |
| Critical Path | YES |

**Description**

Apply schedules to routing and closed-hours behaviour.

**Dependencies**

- L10-04.20-002

**Deliverable**

Schedule-based routing.

**Acceptance Criteria**

Open and closed conditions execute correctly.

### L10-04.20-004 — Validate Schedule Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate routing during open, closed and boundary conditions.

**Dependencies**

- L10-04.20-003

**Deliverable**

Schedule validation evidence.

**Acceptance Criteria**

Schedule routing behaves as designed.

## Definition of Done

Business-hours routing is configured and validated.

---
