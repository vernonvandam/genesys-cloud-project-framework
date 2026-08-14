# Layer 10 — 2.09.19 Architect Flow Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.19 |
| Capability | Architect Flow Reporting |
| Task Catalogue ID | 09.19 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide reporting on Architect flow execution, outcomes, routing behaviour and flow-level business events.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define flow reporting requirements |
| P04 | Design flow reporting |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Identify reporting events.
2. Define flow metrics.
3. Configure reporting.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-19-001 — Define Architect Flow Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Architect Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify Architect flow events and outcomes requiring reporting.

**Dependencies**

- L10-09-02-002

**Deliverable**

Flow reporting requirements.

**Acceptance Criteria**

Required flow reporting events are documented.

### Activity 02 — Design

#### L10-09-19-002 — Design Flow Reporting Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define how Architect flow events and outcomes will be reported.

**Dependencies**

- L10-09-19-001

**Deliverable**

Flow reporting design.

**Acceptance Criteria**

Reporting model is approved.

### Activity 03 — Configure

#### L10-09-19-003 — Configure Architect Flow Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure required Architect flow reporting.

**Dependencies**

- L10-09-19-002

**Deliverable**

Flow reporting configuration.

**Acceptance Criteria**

Required flow outcomes are reportable.

### Activity 04 — Validation

#### L10-09-19-004 — Validate Architect Flow Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate flow reporting using representative flow executions.

**Dependencies**

- L10-09-19-003

**Deliverable**

Flow reporting validation.

**Acceptance Criteria**

Flow outcomes are correctly reported.

## Capability-Level Dependencies

- Architect
- ACD
- Data Actions
- Analytics

## Capability-Level Estimation Considerations

Effort depends on number and complexity of flows and custom reporting requirements.

## Definition of Done

Required Architect flow reporting is configured and validated.