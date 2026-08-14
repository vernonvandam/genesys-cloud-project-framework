<!-- FILE: 15-inbound-call-routing.md -->

# Layer 10 — 2.03.15 Inbound Call Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.15 |
| Capability | Inbound Call Routing |
| Task Catalogue ID | 03.15 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Implement inbound voice routing from telephone numbers through trunks, call flows, IVR and queues to the correct destination.

## Source Implementation Activities

1. Define inbound routing requirements.
2. Map numbers.
3. Design routing.
4. Configure.
5. Test.
6. Validate production routing.

## Implementation Tasks

#### L10-03.15-001 — Define Inbound Routing Requirements

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

Document number-to-service, IVR, queue and business-hours routing requirements.

**Dependencies**

- Number inventory
- Routing requirements

**Deliverable**

Inbound routing requirements.

**Acceptance Criteria**

Routing matrix approved.

#### L10-03.15-002 — Design Inbound Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Design inbound call paths and exception handling.

**Dependencies**

- L10-03.15-001

**Deliverable**

Inbound routing design.

**Acceptance Criteria**

Design approved.

#### L10-03.15-003 — Configure Inbound Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h/flow |
| Critical Path | YES |

**Description**

Configure inbound number mappings, call flows, queues and routing logic.

**Dependencies**

- L10-03.15-002
- Architect
- ACD routing

**Deliverable**

Configured inbound routing.

**Acceptance Criteria**

Routing matches approved design.

#### L10-03.15-004 — Test Inbound Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test successful, exception, after-hours, overflow and failure routing.

**Dependencies**

- L10-03.15-003

**Deliverable**

Inbound test evidence.

**Acceptance Criteria**

All approved routing scenarios pass.

## Capability-Level Dependencies

- Telephone numbers
- Architect
- ACD
- Queues
- Business hours

## Capability-Level Estimation Considerations

Estimate by number, flow and routing complexity.

## Definition of Done

Inbound voice routes correctly across all approved scenarios.