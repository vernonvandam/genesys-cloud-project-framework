# Layer 10 — 2.04.17 In-Queue Flows

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.17 |
| Capability | In-Queue Flows |
| Task Catalogue ID | 04.17 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Configure customer experience while interactions remain in queue, including messaging, prompts, estimated wait behaviour and routing decisions.

## Source Implementation Activities

1. Define in-queue experience.
2. Design in-queue flow logic.
3. Configure flows.
4. Validate queue experience.

## Implementation Tasks

### L10-04.17-001 — Define In-Queue Experience

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define customer messaging, prompts, announcements, wait handling and exit conditions.

**Dependencies**

- Queue architecture
- Customer experience requirements

**Deliverable**

In-queue experience requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-04.17-002 — Design In-Queue Flow Logic

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Design the flow logic governing interactions waiting in queue.

**Dependencies**

- L10-04.17-001

**Deliverable**

In-queue flow design.

**Acceptance Criteria**

Flow logic is approved.

### L10-04.17-003 — Configure In-Queue Flows

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h per flow |
| Critical Path | YES |

**Description**

Build and configure the approved in-queue flows.

**Dependencies**

- L10-04.17-002

**Deliverable**

Configured in-queue flows.

**Acceptance Criteria**

Flows execute without errors.

### L10-04.17-004 — Validate In-Queue Experience

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per flow |
| Critical Path | YES |

**Description**

Validate announcements, prompts, wait behaviour, exits and fallback paths.

**Dependencies**

- L10-04.17-003

**Deliverable**

Flow validation evidence.

**Acceptance Criteria**

All expected in-queue scenarios pass.

## Definition of Done

In-queue experience is configured, tested and accepted.

---