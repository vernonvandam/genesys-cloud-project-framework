<!-- FILE: 32-voice-operations-bau.md -->

# Layer 10 — 2.03.32 Voice Operations & BAU

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.32 |
| Capability | Voice Operations & BAU |
| Task Catalogue ID | 03.32 |
| Primary Layer 1 Phases | P09, P10, P11, P12 |

## Capability Objective

Establish the operational model required to support Genesys Cloud voice services following production deployment.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P09 | Prepare operational support |
| P10 | Support go-live |
| P11 | Operate hypercare |
| P12 | Complete BAU handover |

## Source Implementation Activities

1. Define voice operational ownership.
2. Establish monitoring.
3. Create support procedures.
4. Prepare carrier escalation.
5. Support hypercare.
6. Complete BAU handover.

## Implementation Tasks

### Activity 01 — Operational Design

#### L10-03.32-001 — Define Voice BAU Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Management Lead |
| Customer Responsibility | YES |
| Environment | BAU |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define ownership for Genesys Cloud, carriers, numbers, network, endpoints and voice incidents.

**Dependencies**

- Voice architecture
- Support model

**Deliverable**

Voice ownership model.

**Acceptance Criteria**

Responsibilities are approved.

### Activity 02 — Support Readiness

#### L10-03.32-002 — Establish Voice Monitoring Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Management Lead |
| Customer Responsibility | JOINT |
| Environment | BAU |
| Automation | CONDITIONAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define monitoring, alerting and quality-monitoring requirements for voice services.

**Dependencies**

- Call quality requirements

**Deliverable**

Voice monitoring design.

**Acceptance Criteria**

Monitoring requirements are accepted.

#### L10-03.32-003 — Create Voice Support Runbook

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | BAU |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Document common voice incidents, diagnostics, escalation paths, carrier contacts and recovery procedures.

**Dependencies**

- L10-03.32-001
- L10-03.32-002

**Deliverable**

Voice support runbook.

**Acceptance Criteria**

BAU support team accepts the runbook.

### Activity 03 — Hypercare

#### L10-03.32-004 — Provide Voice Hypercare

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h/day |
| Critical Path | YES |

**Description**

Monitor voice service during the agreed hypercare period and resolve production issues.

**Dependencies**

- Production deployment

**Deliverable**

Voice hypercare report.

**Acceptance Criteria**

Critical voice issues are resolved or formally accepted.

### Activity 04 — Handover

#### L10-03.32-005 — Complete Voice BAU Handover

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Management Lead |
| Customer Responsibility | YES |
| Environment | BAU |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Transfer voice operational ownership, documentation, contacts, monitoring and outstanding issues to BAU.

**Dependencies**

- L10-03.32-004
- Operational readiness

**Deliverable**

Voice BAU handover pack.

**Acceptance Criteria**

BAU owner formally accepts operational responsibility.

## Capability-Level Dependencies

- Voice architecture
- Monitoring
- Service management
- Carrier support
- Operational readiness

## Capability-Level Estimation Considerations

Hypercare effort should be estimated separately from permanent BAU support.

## Definition of Done

Voice services have:

- Defined BAU ownership
- Monitoring requirements
- Support procedures
- Carrier escalation paths
- Operational documentation
- Hypercare completion
- Accepted BAU handover

---