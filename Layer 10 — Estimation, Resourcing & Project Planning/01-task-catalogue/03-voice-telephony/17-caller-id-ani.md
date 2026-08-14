# Layer 10 — 2.03.17 Caller ID & ANI

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.17 |
| Capability | Caller ID & ANI |
| Task Catalogue ID | 03.17 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define and validate inbound caller identification and outbound caller ID/ANI presentation.

## Source Implementation Activities

1. Define presentation requirements.
2. Design caller ID strategy.
3. Configure.
4. Test.

## Implementation Tasks

#### L10-03.17-001 — Define Caller ID Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define required caller ID, ANI and number-presentation behaviour.

**Dependencies**

- Outbound requirements

**Deliverable**

Caller ID requirements.

**Acceptance Criteria**

Requirements approved.

#### L10-03.17-002 — Design Caller ID Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define presentation by queue, site, campaign or business service.

**Dependencies**

- L10-03.17-001

**Deliverable**

Caller ID design.

**Acceptance Criteria**

Design approved.

#### L10-03.17-003 — Configure Caller ID

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved caller ID and ANI behaviour.

**Dependencies**

- L10-03.17-002

**Deliverable**

Caller ID configuration.

**Acceptance Criteria**

Configuration matches design.

#### L10-03.17-004 — Validate Caller ID Presentation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate caller ID presentation across required outbound scenarios.

**Dependencies**

- L10-03.17-003

**Deliverable**

Caller ID test evidence.

**Acceptance Criteria**

Expected caller ID is displayed.

## Capability-Level Dependencies

- Outbound routing
- Telephone numbers
- Carrier
- Number normalisation

## Capability-Level Estimation Considerations

Carrier restrictions and number ownership can affect implementation.

## Definition of Done

Caller ID and ANI behaviour is configured and validated.