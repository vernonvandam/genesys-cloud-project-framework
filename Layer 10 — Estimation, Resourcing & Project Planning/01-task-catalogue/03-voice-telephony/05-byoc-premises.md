# Layer 10 — 2.03.05 BYOC Premises

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.05 |
| Capability | BYOC Premises |
| Task Catalogue ID | 03.05 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P09, P10, P12 |

## Capability Objective

Design and implement BYOC Premises where customer-managed on-premises telephony infrastructure is required.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess existing premises telephony |
| P03 | Confirm requirements |
| P04 | Design BYOC Premises |
| P05 | Prepare infrastructure |
| P06 | Configure Edges and telephony |
| P08 | Validate |
| P09 | Operational readiness |
| P10 | Production deployment |
| P12 | BAU handover |

## Source Implementation Activities

1. Assess premises requirements.
2. Design Edge architecture.
3. Prepare infrastructure.
4. Configure Edges and trunks.
5. Validate voice.
6. Establish support.

## Implementation Tasks

### Activity 01 — Assess and Design

#### L10-03.05-001 — Confirm BYOC Premises Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Confirm the requirements that justify customer-managed telephony infrastructure.

**Dependencies**

- Telephony model selection

**Deliverable**

BYOC Premises requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-03.05-002 — Design BYOC Premises Architecture

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Design Edges, sites, trunks, network paths, survivability and carrier integration.

**Dependencies**

- L10-03.05-001

**Deliverable**

BYOC Premises architecture.

**Acceptance Criteria**

Architecture is approved.

### Activity 02 — Implement

#### L10-03.05-003 — Prepare Edge Infrastructure

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Network Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Prepare required physical, network, power and security prerequisites.

**Dependencies**

- L10-03.05-002

**Deliverable**

Edge infrastructure readiness.

**Acceptance Criteria**

Infrastructure passes readiness checks.

#### L10-03.05-004 — Configure BYOC Premises Telephony

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure Edges, trunks and associated telephony settings.

**Dependencies**

- L10-03.05-003

**Deliverable**

Configured BYOC Premises environment.

**Acceptance Criteria**

Configuration matches approved design.

### Activity 03 — Validate

#### L10-03.05-005 — Validate BYOC Premises Voice

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate signalling, media, routing, failover and recovery.

**Dependencies**

- L10-03.05-004

**Deliverable**

BYOC Premises test evidence.

**Acceptance Criteria**

All agreed scenarios pass.

## Capability-Level Dependencies

- Network
- Carrier
- Edge infrastructure
- Security
- Sites

## Capability-Level Estimation Considerations

Premises infrastructure materially increases installation, coordination and operational effort.

## Definition of Done

BYOC Premises is implemented, tested, resilient where required and operationally accepted.