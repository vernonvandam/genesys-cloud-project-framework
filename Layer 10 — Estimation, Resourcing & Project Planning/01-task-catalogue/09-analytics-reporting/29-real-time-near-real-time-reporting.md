# Layer 10 — 2.09.29 Real-Time & Near-Real-Time Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.29 |
| Capability | Real-Time & Near-Real-Time Reporting |
| Task Catalogue ID | 09.29 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Provide operational reporting with agreed real-time or near-real-time latency.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define operational latency |
| P04 | Design real-time reporting |
| P06 | Configure reporting |
| P08 | Validate latency |
| P10 | Deploy reporting |

## Source Implementation Activities

1. Define latency requirements.
2. Define operational metrics.
3. Configure real-time views.
4. Validate data latency.
5. Deploy.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-29-001 — Define Real-Time Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define real-time and near-real-time reporting requirements.

**Dependencies**

- L10-09-02-003

**Deliverable**

Real-time reporting requirements.

**Acceptance Criteria**

Latency and metrics are approved.

### Activity 02 — Configure

#### L10-09-29-002 — Configure Real-Time Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure real-time and near-real-time reporting views.

**Dependencies**

- L10-09-29-001

**Deliverable**

Real-time reporting.

**Acceptance Criteria**

Required metrics update within agreed latency.

### Activity 03 — Validation

#### L10-09-29-003 — Validate Reporting Latency and Accuracy

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate reporting latency, accuracy and operational usefulness.

**Dependencies**

- L10-09-29-002

**Deliverable**

Real-time reporting validation.

**Acceptance Criteria**

Latency and accuracy meet approved requirements.

### Activity 04 — Deployment

#### L10-09-29-004 — Deploy Real-Time Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | CONDITIONAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Deploy validated real-time reporting.

**Dependencies**

- L10-09-29-003

**Deliverable**

Production real-time reporting.

**Acceptance Criteria**

Operational users can access validated reporting.

## Capability-Level Dependencies

- Genesys Cloud analytics
- ACD
- Queue configuration
- KPI framework

## Capability-Level Estimation Considerations

Effort is driven by latency requirements, dashboard complexity and integration needs.

## Definition of Done

Real-time and near-real-time reporting is deployed and operational.