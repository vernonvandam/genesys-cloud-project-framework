<!-- FILE: 04-byoc-cloud.md -->

# Layer 10 — 2.03.04 BYOC Cloud

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.04 |
| Capability | BYOC Cloud |
| Task Catalogue ID | 03.04 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10, P12 |

## Capability Objective

Implement and validate BYOC Cloud where the customer retains carrier services while using Genesys Cloud for contact-centre voice services.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define BYOC requirements |
| P04 | Design BYOC Cloud |
| P05 | Prepare platform and network |
| P06 | Configure BYOC Cloud |
| P08 | Test voice paths |
| P10 | Deploy production |
| P12 | Handover |

## Source Implementation Activities

1. Confirm BYOC Cloud suitability.
2. Define carrier requirements.
3. Configure trunks and sites.
4. Configure numbers and routing.
5. Validate voice.
6. Document BAU.

## Implementation Tasks

### Activity 01 — Design

#### L10-03.04-001 — Confirm BYOC Cloud Requirements

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

Confirm carrier, SIP, network, number and operational requirements.

**Dependencies**

- L10-03.02-004

**Deliverable**

BYOC Cloud requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-03.04-002 — Configure BYOC Cloud Trunks

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure BYOC Cloud trunks and associated telephony settings.

**Dependencies**

- L10-03.04-001
- Carrier readiness

**Deliverable**

Configured BYOC Cloud trunks.

**Acceptance Criteria**

Trunks are configured according to design.

### Activity 03 — Validate

#### L10-03.04-003 — Validate BYOC Cloud Voice Paths

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate inbound, outbound, media and failure scenarios.

**Dependencies**

- L10-03.04-002

**Deliverable**

BYOC Cloud validation evidence.

**Acceptance Criteria**

Required voice scenarios pass.

## Capability-Level Dependencies

- Carrier
- SIP
- Network
- Sites
- Number strategy

## Capability-Level Estimation Considerations

Effort varies with trunk quantity, carrier complexity and geographic deployment.

## Definition of Done

BYOC Cloud is configured, tested and accepted for production use.