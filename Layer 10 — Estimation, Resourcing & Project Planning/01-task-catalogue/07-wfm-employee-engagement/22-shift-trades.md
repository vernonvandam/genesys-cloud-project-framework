# Layer 10 — 2.07.22 Shift Trades

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.22 |
| Capability | Shift Trades |
| Task Catalogue ID | 07.22 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Provide controlled employee shift-trade functionality where required by the operating model.

## Source Implementation Activities

1. Confirm shift-trade requirements.
2. Define eligibility and rules.
3. Configure shift trades.
4. Validate trade workflows.
5. Prepare support procedures.

## Implementation Tasks

### Activity 01 — Define Shift Trades

#### L10-07.22-001 — Confirm Shift-Trade Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Determine whether employee shift trading is required and permitted.

**Dependencies**

- Scheduling strategy
- Employee policy

**Deliverable**

Shift-trade decision.

**Acceptance Criteria**

Customer confirms whether capability is required.

#### L10-07.22-002 — Define Shift-Trade Rules

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define eligibility, approval, restrictions and scheduling constraints.

**Dependencies**

- L10-07.22-001

**Deliverable**

Shift-trade rules.

**Acceptance Criteria**

Rules are approved.

### Activity 02 — Configure and Validate

#### L10-07.22-003 — Configure Shift Trades

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Configure approved shift-trade capability.

**Dependencies**

- L10-07.22-002

**Deliverable**

Configured shift trades.

**Acceptance Criteria**

Capability is available to authorised users.

#### L10-07.22-004 — Test Shift Trades

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Test eligible and ineligible trade scenarios.

**Dependencies**

- L10-07.22-003

**Deliverable**

Shift-trade test evidence.

**Acceptance Criteria**

Approved trade scenarios operate correctly.