<!-- FILE: 09-network-firewall-media-requirements.md -->

# Layer 10 — 2.03.09 Network, Firewall & Media Requirements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.09 |
| Capability | Network, Firewall & Media Requirements |
| Task Catalogue ID | 03.09 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P09 |

## Capability Objective

Define and validate network, firewall, NAT, QoS and media-path requirements for Genesys Cloud voice.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess network |
| P03 | Define requirements |
| P04 | Design media architecture |
| P05 | Implement prerequisites |
| P08 | Validate |
| P09 | Operational readiness |

## Source Implementation Activities

1. Assess network.
2. Define firewall and media requirements.
3. Define QoS.
4. Implement changes.
5. Validate media paths.
6. Document operational requirements.

## Implementation Tasks

### Activity 01 — Assessment

#### L10-03.09-001 — Assess Voice Network Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Network Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess WAN, LAN, internet, NAT, firewall and QoS readiness.

**Dependencies**

- Network discovery

**Deliverable**

Network readiness assessment.

**Acceptance Criteria**

Gaps are documented.

### Activity 02 — Design

#### L10-03.09-002 — Define Voice Firewall and Media Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define required network flows, firewall rules, NAT behaviour and media paths.

**Dependencies**

- L10-03.09-001

**Deliverable**

Voice network design.

**Acceptance Criteria**

Network/security teams approve requirements.

### Activity 03 — Implementation

#### L10-03.09-003 — Implement Voice Network Changes

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Network Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Implement approved firewall, NAT, QoS and network changes.

**Dependencies**

- L10-03.09-002

**Deliverable**

Implemented network changes.

**Acceptance Criteria**

Approved changes are active.

### Activity 04 — Validate

#### L10-03.09-004 — Validate Voice Media Paths

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Network Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate signalling, RTP/media, latency, jitter, packet loss and QoS behaviour.

**Dependencies**

- L10-03.09-003

**Deliverable**

Media path validation evidence.

**Acceptance Criteria**

Voice quality and network requirements are met.

## Capability-Level Dependencies

- Network architecture
- Security
- Telephony model
- Sites
- Carrier

## Capability-Level Estimation Considerations

Customer network change windows and security approval cycles may affect duration.

## Definition of Done

Voice network prerequisites are implemented, tested and accepted.