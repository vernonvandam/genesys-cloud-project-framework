# Layer 10 — 2.05.04 In-Queue Call Flows

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.04 |
| Capability | In-Queue Call Flows |
| Task Catalogue ID | 05.04 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Provide customer treatment while waiting in queue, including announcements, position or wait treatment, self-service, callback and queue exit behaviour.

## Source Implementation Activities

1. Define in-queue experience.
2. Configure in-queue flow.
3. Test queue treatment.

## Implementation Tasks

### Activity 01 — Define In-Queue Experience

#### L10-05.04-001 — Define In-Queue Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define announcements, music, estimated wait treatment, self-service, callback and queue-exit requirements.

**Dependencies**

- Queue design
- Inbound flow requirements

**Deliverable**

In-queue requirements.

**Acceptance Criteria**

Approved in-queue customer journey.

---

#### L10-05.04-002 — Configure In-Queue Flow

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Build the approved in-queue treatment and associated customer options.

**Dependencies**

- L10-05.04-001

**Deliverable**

Configured in-queue flow.

**Acceptance Criteria**

Configured behaviour matches approved design.

---

#### L10-05.04-003 — Validate In-Queue Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate normal waiting, extended waiting, callback, transfer and queue-exit scenarios.

**Dependencies**

- L10-05.04-002

**Deliverable**

In-queue test evidence.

**Acceptance Criteria**

All approved queue-treatment scenarios pass.