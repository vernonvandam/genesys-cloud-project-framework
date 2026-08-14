# Layer 10 — 2.07.12 Staffing Requirements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.12 |
| Capability | Staffing Requirements |
| Task Catalogue ID | 07.12 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Translate forecast demand and service goals into required staffing levels.

## Source Implementation Activities

1. Define staffing requirements.
2. Map service goals and staffing assumptions.
3. Calculate required staffing.
4. Validate staffing outputs.

## Implementation Tasks

### Activity 01 — Define Staffing Model

#### L10-07.12-001 — Define Staffing Assumptions

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

Define service goals, occupancy, handle time and other staffing assumptions.

**Dependencies**

- Service goals
- Forecasting strategy

**Deliverable**

Staffing assumptions.

**Acceptance Criteria**

Assumptions are approved.

#### L10-07.12-002 — Define Staffing Requirements Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define how forecast demand is converted into staffing requirements.

**Dependencies**

- L10-07.12-001

**Deliverable**

Staffing requirements model.

**Acceptance Criteria**

Model is approved.

### Activity 02 — Generate and Validate Staffing

#### L10-07.12-003 — Generate Staffing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Generate staffing requirements from the approved forecast and service goals.

**Dependencies**

- Forecast generation
- L10-07.12-002

**Deliverable**

Staffing requirement output.

**Acceptance Criteria**

Staffing requirements are generated successfully.

#### L10-07.12-004 — Validate Staffing Requirements

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

Validate staffing outputs against operational expectations.

**Dependencies**

- L10-07.12-003

**Deliverable**

Staffing validation report.

**Acceptance Criteria**

Customer accepts staffing requirements.