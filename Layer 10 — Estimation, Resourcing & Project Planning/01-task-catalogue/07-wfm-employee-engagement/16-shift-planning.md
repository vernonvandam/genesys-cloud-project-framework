# Layer 10 — 2.07.16 Shift Planning

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.16 |
| Capability | Shift Planning |
| Task Catalogue ID | 07.16 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define shift structures and workforce constraints required to support operational coverage and employee requirements.

## Source Implementation Activities

1. Identify shift requirements.
2. Define shift templates.
3. Configure shift rules.
4. Validate coverage and employee constraints.

## Implementation Tasks

### Activity 01 — Define Shifts

#### L10-07.16-001 — Identify Shift Requirements

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

Identify required shift patterns, operating hours, employee constraints and coverage requirements.

**Dependencies**

- Scheduling strategy
- Staffing requirements

**Deliverable**

Shift requirements.

**Acceptance Criteria**

Shift requirements are approved.

#### L10-07.16-002 — Define Shift Templates

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

Define shift templates, durations, breaks and activity patterns.

**Dependencies**

- L10-07.16-001
- Activities

**Deliverable**

Shift-template catalogue.

**Acceptance Criteria**

Shift templates are approved.

### Activity 02 — Configure and Validate

#### L10-07.16-003 — Configure Shift Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved shift rules and constraints.

**Dependencies**

- L10-07.16-002

**Deliverable**

Configured shift rules.

**Acceptance Criteria**

Rules match approved requirements.

#### L10-07.16-004 — Validate Shift Coverage

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate shift structures against forecast demand and workforce constraints.

**Dependencies**

- L10-07.16-003

**Deliverable**

Shift validation report.

**Acceptance Criteria**

Shift patterns provide acceptable operational coverage.