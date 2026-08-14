# Layer 10 — 2.09.36 Report Scheduling & Distribution

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.36 |
| Capability | Report Scheduling & Distribution |
| Task Catalogue ID | 09.36 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Configure controlled report scheduling, distribution, recipient management and delivery validation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define distribution requirements |
| P04 | Design distribution model |
| P06 | Configure schedules |
| P08 | Validate delivery |
| P10 | Deploy |

## Source Implementation Activities

1. Define scheduled reports.
2. Identify recipients.
3. Configure schedules.
4. Validate delivery.
5. Deploy.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-36-001 — Define Report Distribution Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define reports requiring scheduled distribution and recipients.

**Dependencies**

- L10-09-02-002

**Deliverable**

Distribution requirements.

**Acceptance Criteria**

Required schedules and recipients are approved.

### Activity 02 — Configure

#### L10-09-36-002 — Configure Report Schedules

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

Configure report schedules and distribution settings.

**Dependencies**

- L10-09-36-001

**Deliverable**

Scheduled reports.

**Acceptance Criteria**

Schedules execute as designed.

### Activity 03 — Validation

#### L10-09-36-003 — Validate Report Distribution

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

Validate schedule timing, report content and recipient delivery.

**Dependencies**

- L10-09-36-002

**Deliverable**

Distribution validation evidence.

**Acceptance Criteria**

Reports are delivered to approved recipients.

## Capability-Level Dependencies

- Reporting
- Security
- Recipient access
- Email or distribution mechanisms

## Capability-Level Estimation Considerations

Effort depends on report count, schedules and recipient groups.

## Definition of Done

Required reports are scheduled, distributed and validated.