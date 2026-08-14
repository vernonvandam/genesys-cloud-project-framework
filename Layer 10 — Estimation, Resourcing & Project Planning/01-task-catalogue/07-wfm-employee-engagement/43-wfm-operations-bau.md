# Layer 10 — 2.07.43 WFM Operations & BAU

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.43 |
| Capability | WFM Operations & BAU |
| Task Catalogue ID | 07.43 |
| Primary Layer 1 Phases | P09, P10, P11, P12 |

## Capability Objective

Establish the operational processes, support model and ownership required to run WFM in BAU.

## Source Implementation Activities

1. Define WFM operating model.
2. Define support processes.
3. Prepare operational documentation.
4. Train operational users.
5. Execute hypercare.
6. Complete BAU handover.

## Implementation Tasks

### Activity 01 — Prepare Operations

#### L10-07.43-001 — Define WFM BAU Operating Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define WFM planning, scheduling, forecasting, adherence and support responsibilities.

**Dependencies**

- WFM governance
- WFM architecture

**Deliverable**

BAU operating model.

**Acceptance Criteria**

Customer approves BAU operating model.

#### L10-07.43-002 — Prepare WFM Operational Runbook

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Document recurring WFM procedures, exception handling and support activities.

**Dependencies**

- L10-07.43-001

**Deliverable**

WFM operations runbook.

**Acceptance Criteria**

Runbook is approved.

### Activity 02 — Prepare Users

#### L10-07.43-003 — Train WFM Operational Users

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Train planners, supervisors and other operational users.

**Dependencies**

- L10-07.43-002
- UAT acceptance

**Deliverable**

WFM training completion record.

**Acceptance Criteria**

Required users are trained.

### Activity 03 — Hypercare and Handover

#### L10-07.43-004 — Execute WFM Hypercare

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Monitor WFM operation, investigate defects and support workforce users after go-live.

**Dependencies**

- Production cutover

**Deliverable**

WFM hypercare report.

**Acceptance Criteria**

Critical early-life issues are resolved or transferred.

#### L10-07.43-005 — Complete WFM BAU Handover

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Transfer WFM documentation, operational ownership, support responsibilities and known issues.

**Dependencies**

- L10-07.43-004

**Deliverable**

WFM BAU handover pack.

**Acceptance Criteria**

BAU ownership is formally accepted.