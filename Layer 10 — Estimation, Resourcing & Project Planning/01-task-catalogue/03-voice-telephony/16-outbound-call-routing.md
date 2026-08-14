<!-- FILE: 16-outbound-call-routing.md -->

# Layer 10 — 2.03.16 Outbound Call Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.16 |
| Capability | Outbound Call Routing |
| Task Catalogue ID | 03.16 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Define and implement outbound routing, classification, carrier selection, restrictions and treatment.

## Source Implementation Activities

1. Define outbound requirements.
2. Define route classifications.
3. Configure outbound routes.
4. Configure restrictions.
5. Test.

## Implementation Tasks

#### L10-03.16-001 — Define Outbound Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define allowed destinations, restrictions, carrier routes and presentation requirements.

**Dependencies**

- Number plan

**Deliverable**

Outbound requirements matrix.

**Acceptance Criteria**

Requirements approved.

#### L10-03.16-002 — Design Outbound Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Design outbound route selection and restrictions.

**Dependencies**

- L10-03.16-001

**Deliverable**

Outbound routing design.

**Acceptance Criteria**

Design approved.

#### L10-03.16-003 — Configure Outbound Routes

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

Configure outbound routes, classifications and restrictions.

**Dependencies**

- L10-03.16-002
- SIP trunks

**Deliverable**

Outbound routing configuration.

**Acceptance Criteria**

Configuration matches design.

#### L10-03.16-004 — Test Outbound Calling

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

Test local, national, international, restricted and invalid destinations.

**Dependencies**

- L10-03.16-003

**Deliverable**

Outbound test evidence.

**Acceptance Criteria**

All approved outbound scenarios pass.

## Capability-Level Dependencies

- SIP trunks
- Number plans
- Caller ID
- Security
- Carrier

## Capability-Level Estimation Considerations

Estimate based on route complexity and number of carrier destinations.

## Definition of Done

Outbound routing is configured, restricted appropriately and fully validated.