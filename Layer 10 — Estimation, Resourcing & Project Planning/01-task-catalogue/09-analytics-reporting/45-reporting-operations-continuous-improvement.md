# Layer 10 — 2.09.45 Reporting Operations & Continuous Improvement

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.45 |
| Capability | Reporting Operations & Continuous Improvement |
| Task Catalogue ID | 09.45 |
| Primary Layer 1 Phases | P09, P11, P12 |

## Capability Objective

Establish operational ownership, support processes, monitoring and continuous improvement for analytics and reporting.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P09 | Prepare operational support |
| P11 | Operate during hypercare |
| P12 | Handover to BAU |

## Source Implementation Activities

1. Define reporting support model.
2. Define monitoring.
3. Establish issue management.
4. Execute hypercare.
5. Handover.
6. Establish improvement process.

## Implementation Tasks

### Activity 01 — Support Model

#### L10-09-45-001 — Define Reporting Support Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define reporting support responsibilities, escalation paths and service processes.

**Dependencies**

- L10-09-06-003

**Deliverable**

Reporting support model.

**Acceptance Criteria**

Support ownership is approved.

### Activity 02 — Monitoring

#### L10-09-45-002 — Define Reporting Monitoring Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Operations Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | CONDITIONAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define monitoring for data pipelines, report failures, API failures and reporting availability.

**Dependencies**

- L10-09-45-001

**Deliverable**

Reporting monitoring model.

**Acceptance Criteria**

Monitoring requirements are documented.

### Activity 03 — Hypercare

#### L10-09-45-003 — Execute Reporting Hypercare

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Monitor reporting after production deployment and resolve defects.

**Dependencies**

- L10-09-44-004

**Deliverable**

Hypercare report.

**Acceptance Criteria**

Critical reporting defects are resolved or accepted.

### Activity 04 — Handover

#### L10-09-45-004 — Handover Reporting Operations

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Transfer reporting operational ownership to BAU teams.

**Dependencies**

- L10-09-45-003

**Deliverable**

Reporting operational handover.

**Acceptance Criteria**

BAU ownership is accepted.

### Activity 05 — Improvement

#### L10-09-45-005 — Establish Reporting Continuous Improvement Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Reporting Product Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Establish ongoing review of report usage, quality, duplication and business value.

**Dependencies**

- L10-09-45-004

**Deliverable**

Reporting improvement backlog.

**Acceptance Criteria**

Continuous improvement process is operational.

## Capability-Level Dependencies

- Reporting governance
- Support model
- Production deployment
- Monitoring

## Capability-Level Estimation Considerations

Initial project effort is driven by operational complexity; BAU effort should be treated separately.

## Definition of Done

Reporting operations, support, hypercare, handover and continuous improvement are established.