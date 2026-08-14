# Layer 10 — 2.06.12 Email

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.12 |
| Capability | Email |
| Task Catalogue ID | 06.12 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Implement email as an asynchronous customer interaction channel with appropriate routing, service levels, templates, security and operational controls.

## Implementation Tasks

### L10-06.12-001 — Define Email Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define email addresses, queues, routing, SLAs, operating hours, attachments, auto-responses and escalation.

**Dependencies**

- Digital architecture

**Deliverable**

Email requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-06.12-002 — Configure Email Channel

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure email addresses, queues and routing.

**Dependencies**

- L10-06.12-001

**Deliverable**

Configured email channel.

**Acceptance Criteria**

Test emails are accepted and routed.

### L10-06.12-003 — Configure Email Service Levels

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure service-level and operating-hour behaviour for asynchronous email.

**Dependencies**

- L10-06.12-002
- Digital Priority & SLA

**Deliverable**

Email SLA configuration.

**Acceptance Criteria**

Email interactions are measured against approved targets.

### L10-06.12-004 — Test Email Handling

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test inbound email, routing, attachments, responses, transfers and closure.

**Dependencies**

- L10-06.12-003

**Deliverable**

Email test evidence.

**Acceptance Criteria**

Approved email scenarios pass.

### L10-06.12-005 — Activate Email

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Activate production email routing.

**Dependencies**

- L10-06.12-004

**Deliverable**

Production email capability.

**Acceptance Criteria**

Production email is successfully received, routed and handled.

## Definition of Done

Email is configured, routed, measured, tested and operational.

---
