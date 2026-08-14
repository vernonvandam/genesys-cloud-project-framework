# Layer 10 — 2.09.02 Reporting Requirements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.02 |
| Capability | Reporting Requirements |
| Task Catalogue ID | 09.02 |
| Primary Layer 1 Phases | P02, P03, P04, P08 |

## Capability Objective

Capture, classify and approve detailed reporting requirements across operational, supervisory, management and executive consumers.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover reporting needs |
| P03 | Capture requirements |
| P04 | Design reporting solution |
| P08 | Validate requirements |

## Source Implementation Activities

1. Identify report consumers.
2. Capture reporting requirements.
3. Define report frequency and latency.
4. Define report acceptance criteria.
5. Obtain approval.

## Implementation Tasks

### Activity 01 — Stakeholders

#### L10-09-02-001 — Identify Reporting Consumers

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify all operational, supervisory, management and executive reporting consumers.

**Dependencies**

- L10-09-01-001

**Deliverable**

Reporting stakeholder catalogue.

**Acceptance Criteria**

All reporting consumer groups are identified.

### Activity 02 — Requirements

#### L10-09-02-002 — Capture Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 6.0h |
| Critical Path | YES |

**Description**

Document required reports, metrics, filters, dimensions and consumers.

**Dependencies**

- L10-09-02-001

**Deliverable**

Reporting requirements catalogue.

**Acceptance Criteria**

Requirements are documented and traceable to consumers.

### Activity 03 — Reporting Behaviour

#### L10-09-02-003 — Define Frequency and Data Latency Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define real-time, near-real-time and historical reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

Reporting latency model.

**Acceptance Criteria**

Required frequency and latency are defined for each report class.

### Activity 04 — Approval

#### L10-09-02-004 — Approve Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Obtain customer approval for reporting requirements.

**Dependencies**

- L10-09-02-003

**Deliverable**

Approved reporting requirements.

**Acceptance Criteria**

Requirements are formally approved.

### Activity 05 — Validation

#### L10-09-02-005 — Validate Requirements Against Solution

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate implemented reporting against approved requirements.

**Dependencies**

- L10-09-02-004

**Deliverable**

Requirements validation evidence.

**Acceptance Criteria**

All required reporting requirements are traceably validated.

## Capability-Level Dependencies

- Analytics strategy
- Business stakeholders
- KPI framework
- Data source catalogue

## Capability-Level Estimation Considerations

Effort increases with report count, stakeholder groups, complex calculations and external reporting dependencies.

## Definition of Done

Reporting requirements are documented, approved, traceable and validated against the delivered reporting solution.