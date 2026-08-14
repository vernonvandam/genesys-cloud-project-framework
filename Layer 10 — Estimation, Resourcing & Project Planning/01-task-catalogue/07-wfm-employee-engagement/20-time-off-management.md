# Layer 10 — 2.07.20 Time-Off Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.20 |
| Capability | Time-Off Management |
| Task Catalogue ID | 07.20 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Define and configure workforce time-off management processes and rules.

## Source Implementation Activities

1. Identify time-off requirements.
2. Define categories and rules.
3. Configure time-off management.
4. Validate request and approval processes.
5. Prepare operational procedures.

## Implementation Tasks

### Activity 01 — Define Time-Off Model

#### L10-07.20-001 — Identify Time-Off Requirements

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

Identify leave categories, approval requirements and workforce constraints.

**Dependencies**

- HR policy
- Scheduling strategy

**Deliverable**

Time-off requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-07.20-002 — Define Time-Off Governance

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

Define time-off categories, approval rules, ownership and operational controls.

**Dependencies**

- L10-07.20-001

**Deliverable**

Time-off governance model.

**Acceptance Criteria**

Model is approved.

### Activity 02 — Configure and Validate

#### L10-07.20-003 — Configure Time-Off Management

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

Configure time-off categories and approved rules.

**Dependencies**

- L10-07.20-002

**Deliverable**

Configured time-off model.

**Acceptance Criteria**

Configuration matches approved requirements.

#### L10-07.20-004 — Test Time-Off Requests

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

Test submission, approval, rejection and schedule impact of time-off requests.

**Dependencies**

- L10-07.20-003

**Deliverable**

Time-off test evidence.

**Acceptance Criteria**

Time-off workflow behaves as designed.