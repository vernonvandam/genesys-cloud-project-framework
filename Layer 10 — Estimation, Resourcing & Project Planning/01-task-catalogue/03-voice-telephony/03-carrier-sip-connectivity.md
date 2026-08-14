# Layer 10 — 2.03.03 Carrier & SIP Connectivity

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.03 |
| Capability | Carrier & SIP Connectivity |
| Task Catalogue ID | 03.03 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P07, P08, P10 |

## Capability Objective

Design, provision, configure and validate carrier and SIP connectivity required to deliver production voice services.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover existing carrier services |
| P03 | Define carrier requirements |
| P04 | Design carrier/SIP architecture |
| P05 | Establish technical prerequisites |
| P07 | Implement carrier connectivity |
| P08 | Test connectivity |
| P10 | Activate production connectivity |

## Source Implementation Activities

1. Identify carrier requirements.
2. Define SIP connectivity.
3. Engage carrier.
4. Provision connectivity.
5. Configure Genesys Cloud.
6. Test voice paths.
7. Activate production.

## Implementation Tasks

### Activity 01 — Carrier Discovery

#### L10-03.03-001 — Inventory Carrier Services

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Inventory carriers, SIP services, trunks, numbers, routing and contractual dependencies.

**Dependencies**

- Telephony discovery

**Deliverable**

Carrier inventory.

**Acceptance Criteria**

Carrier services are documented.

### Activity 02 — Design

#### L10-03.03-002 — Define SIP Connectivity Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define SIP endpoints, authentication, transport, codecs, capacity and network requirements.

**Dependencies**

- L10-03.03-001

**Deliverable**

SIP connectivity design.

**Acceptance Criteria**

Requirements are approved.

### Activity 03 — Provision

#### L10-03.03-003 — Coordinate Carrier Provisioning

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Coordinate carrier-side provisioning and configuration.

**Dependencies**

- L10-03.03-002
- Carrier readiness

**Deliverable**

Carrier connectivity provisioned.

**Acceptance Criteria**

Carrier confirms service readiness.

### Activity 04 — Validate

#### L10-03.03-004 — Test SIP Connectivity

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test signalling, media, inbound and outbound calls and failure conditions.

**Dependencies**

- L10-03.03-003

**Deliverable**

SIP test evidence.

**Acceptance Criteria**

All agreed SIP test cases pass.

## Capability-Level Dependencies

- Carrier
- Network
- Firewall
- Telephony model
- Number strategy

## Capability-Level Estimation Considerations

Carrier lead times and customer/vendor coordination are major schedule risks.

## Definition of Done

Carrier and SIP connectivity is provisioned, tested, documented and production-ready.