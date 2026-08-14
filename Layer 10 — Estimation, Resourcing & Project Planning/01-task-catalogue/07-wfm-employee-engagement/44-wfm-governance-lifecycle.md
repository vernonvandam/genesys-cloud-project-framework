# Layer 10 — 2.07.44 WFM Governance & Lifecycle

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.44 |
| Capability | WFM Governance & Lifecycle |
| Task Catalogue ID | 07.44 |
| Primary Layer 1 Phases | P03, P04, P09, P11, P12 |

## Capability Objective

Establish lifecycle controls governing WFM configuration, change, ownership and ongoing evolution.

## Source Implementation Activities

1. Define WFM lifecycle.
2. Establish configuration governance.
3. Define change control.
4. Establish review cadence.
5. Transfer lifecycle ownership.

## Implementation Tasks

### Activity 01 — Define Lifecycle

#### L10-07.44-001 — Define WFM Lifecycle Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define how WFM capabilities move through design, configuration, testing, production and BAU lifecycle states.

**Dependencies**

- WFM strategy

**Deliverable**

WFM lifecycle model.

**Acceptance Criteria**

Lifecycle model is approved.

#### L10-07.44-002 — Define WFM Change Control

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define change assessment, approval, testing and deployment requirements for WFM changes.

**Dependencies**

- L10-07.44-001

**Deliverable**

WFM change-control process.

**Acceptance Criteria**

Change process is approved.

### Activity 02 — Establish Governance

#### L10-07.44-003 — Establish WFM Configuration Governance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define ownership and governance for WFM configuration and production changes.

**Dependencies**

- L10-07.44-002

**Deliverable**

Configuration governance model.

**Acceptance Criteria**

Customer accepts configuration governance.

#### L10-07.44-004 — Handover WFM Lifecycle Governance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Transfer lifecycle governance responsibilities to BAU owners.

**Dependencies**

- L10-07.44-003

**Deliverable**

Lifecycle governance handover.

**Acceptance Criteria**

BAU owner accepts lifecycle responsibilities.