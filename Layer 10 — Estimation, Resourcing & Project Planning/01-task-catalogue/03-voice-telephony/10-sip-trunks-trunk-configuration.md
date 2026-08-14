<!-- FILE: 10-sip-trunks-trunk-configuration.md -->

# Layer 10 — 2.03.10 SIP Trunks & Trunk Configuration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.10 |
| Capability | SIP Trunks & Trunk Configuration |
| Task Catalogue ID | 03.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Design and configure SIP trunks required to connect Genesys Cloud voice services to carriers and telephony infrastructure.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define trunk requirements |
| P04 | Design trunk architecture |
| P06 | Configure trunks |
| P08 | Validate |
| P10 | Activate production |

## Source Implementation Activities

1. Define trunk requirements.
2. Design trunk topology.
3. Configure trunks.
4. Validate inbound/outbound media.
5. Activate production.

## Implementation Tasks

### Activity 01 — Design

#### L10-03.10-001 — Define SIP Trunk Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define trunk capacity, signalling, transport, codec, security and routing requirements.

**Dependencies**

- Carrier strategy

**Deliverable**

Trunk requirements.

**Acceptance Criteria**

Requirements approved.

#### L10-03.10-002 — Design SIP Trunk Configuration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define trunk configuration and routing relationships.

**Dependencies**

- L10-03.10-001

**Deliverable**

SIP trunk design.

**Acceptance Criteria**

Design approved.

### Activity 02 — Configure

#### L10-03.10-003 — Configure SIP Trunks

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.5h/trunk |
| Critical Path | CONDITIONAL |

**Description**

Configure required SIP trunks.

**Dependencies**

- L10-03.10-002
- Carrier readiness

**Deliverable**

Configured trunks.

**Acceptance Criteria**

Trunks are operational.

### Activity 03 — Validate

#### L10-03.10-004 — Test SIP Trunks

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h/trunk |
| Critical Path | CONDITIONAL |

**Description**

Test signalling, media, routing, capacity and failure conditions.

**Dependencies**

- L10-03.10-003

**Deliverable**

Trunk test evidence.

**Acceptance Criteria**

All required trunk tests pass.

## Capability-Level Dependencies

- Carrier
- Network
- BYOC architecture
- Number strategy

## Capability-Level Estimation Considerations

Estimate per trunk and carrier.

## Definition of Done

Required SIP trunks are configured, tested and ready for production.