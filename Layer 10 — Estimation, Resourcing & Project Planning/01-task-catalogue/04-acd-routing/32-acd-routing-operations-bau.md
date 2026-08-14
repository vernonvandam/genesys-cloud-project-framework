# Layer 10 — 2.04.32 ACD & Routing Operations / BAU

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.32 |
| Capability | ACD & Routing Operations / BAU |
| Task Catalogue ID | 04.32 |
| Primary Layer 1 Phases | P10, P11, P12 |

## Capability Objective

Transition ACD and routing configuration into supported business-as-usual operations with appropriate ownership, documentation, monitoring and change processes.

## Source Implementation Activities

1. Define routing operational ownership.
2. Document support procedures.
3. Establish routing monitoring.
4. Complete operational handover.
5. Validate BAU readiness.

## Implementation Tasks

### Activity 01 — Operational Readiness

#### L10-04.32-001 — Define ACD and Routing Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define operational ownership for queues, routing, skills, schedules, routing rules and associated dependencies.

**Dependencies**

- Routing architecture

**Deliverable**

Routing ownership matrix.

**Acceptance Criteria**

Operational ownership is formally accepted.

### L10-04.32-002 — Document Routing Support Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Document operational procedures for routing changes, troubleshooting, escalation and support.

**Dependencies**

- L10-04.32-001

**Deliverable**

Routing support procedures.

**Acceptance Criteria**

Support documentation is complete and accepted.

### Activity 02 — Monitoring and Handover

#### L10-04.32-003 — Define Routing Monitoring Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Operations Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define monitoring requirements for queue performance, service levels, routing failures and operational anomalies.

**Dependencies**

- L10-04.32-001

**Deliverable**

Routing monitoring requirements.

**Acceptance Criteria**

Monitoring ownership and thresholds are approved.

#### L10-04.32-004 — Complete ACD and Routing Handover

| Attribute | Value |
|---|---|
| Task Type | OPERATIONAL |
| Layer 1 Phase | P12 |
| Primary Role | Operations Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Transfer configuration knowledge, documentation, support procedures and outstanding issues to the operational team.

**Dependencies**

- L10-04.32-002
- L10-04.32-003
- Production validation

**Deliverable**

Operational handover package.

**Acceptance Criteria**

Operations formally accepts ownership.

#### L10-04.32-005 — Validate BAU Routing Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Operations Lead |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm that the operational team can support, monitor and modify ACD and routing configuration.

**Dependencies**

- L10-04.32-004

**Deliverable**

BAU readiness sign-off.

**Acceptance Criteria**

BAU support capability is demonstrated and accepted.

## Capability-Level Dependencies

- Routing architecture
- Queue configuration
- Skills
- Production cutover
- Operational support model
- Documentation

## Capability-Level Estimation Considerations

Effort varies according to:

- number of routing components
- operational maturity
- support model
- documentation requirements
- monitoring complexity
- customer handover requirements

## Definition of Done

ACD and routing are fully transitioned to BAU with:

- defined ownership
- support procedures
- monitoring requirements
- configuration documentation
- known issues recorded
- operational handover completed
- BAU readiness accepted

---
