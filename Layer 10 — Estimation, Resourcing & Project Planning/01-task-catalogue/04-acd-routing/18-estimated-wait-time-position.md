# Layer 10 — 2.04.18 Estimated Wait Time & Position

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.18 |
| Capability | Estimated Wait Time & Position |
| Task Catalogue ID | 04.18 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Configure customer-facing estimated wait time and queue-position behaviour where required.

## Source Implementation Activities

1. Define wait-time requirements.
2. Define customer messaging.
3. Configure wait-time behaviour.
4. Validate calculations and messaging.

## Implementation Tasks

### L10-04.18-001 — Define Wait-Time Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define where estimated wait time and queue position should be presented.

**Dependencies**

- In-queue experience requirements

**Deliverable**

Wait-time requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-04.18-002 — Configure Wait-Time Behaviour

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per flow |
| Critical Path | CONDITIONAL |

**Description**

Configure estimated wait time and position messaging.

**Dependencies**

- L10-04.18-001

**Deliverable**

Configured wait-time behaviour.

**Acceptance Criteria**

Wait information is presented according to design.

### L10-04.18-003 — Validate Wait-Time Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate wait-time and position messaging under different queue conditions.

**Dependencies**

- L10-04.18-002

**Deliverable**

Wait-time validation evidence.

**Acceptance Criteria**

Messaging behaves correctly.

## Definition of Done

Estimated wait and queue-position behaviour is validated where applicable.

---
