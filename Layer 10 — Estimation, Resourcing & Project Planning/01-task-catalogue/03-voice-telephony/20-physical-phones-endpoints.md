# Layer 10 — 2.03.20 Physical Phones & Endpoints

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.20 |
| Capability | Physical Phones & Endpoints |
| Task Catalogue ID | 03.20 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P09 |

## Capability Objective

Define, provision, configure and validate physical telephony endpoints where required.

## Source Implementation Activities

1. Inventory devices.
2. Define endpoint standard.
3. Prepare devices.
4. Provision devices.
5. Test.
6. Prepare BAU support.

## Implementation Tasks

#### L10-03.20-001 — Inventory Physical Voice Devices

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Inventory existing physical phones and endpoint requirements.

**Dependencies**

- Current-state discovery

**Deliverable**

Endpoint inventory.

**Acceptance Criteria**

Endpoint estate is documented.

#### L10-03.20-002 — Define Endpoint Standard

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define supported phone models, accessories, deployment and support standards.

**Dependencies**

- L10-03.20-001

**Deliverable**

Endpoint standard.

**Acceptance Criteria**

Standard approved.

#### L10-03.20-003 — Provision Physical Phones

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 0.5h/device |
| Critical Path | CONDITIONAL |

**Description**

Provision and configure physical endpoints.

**Dependencies**

- L10-03.20-002
- Network readiness

**Deliverable**

Configured phones.

**Acceptance Criteria**

Phones register and operate.

#### L10-03.20-004 — Test Physical Endpoints

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h/device |
| Critical Path | CONDITIONAL |

**Description**

Validate registration, calling, audio and user controls.

**Dependencies**

- L10-03.20-003

**Deliverable**

Endpoint test evidence.

**Acceptance Criteria**

Endpoints pass test criteria.

## Capability-Level Dependencies

- Sites
- Network
- Device standards
- Identity

## Capability-Level Estimation Considerations

Estimate installation and configuration separately from platform configuration.

## Definition of Done

Required physical endpoints are deployed, tested and supported.