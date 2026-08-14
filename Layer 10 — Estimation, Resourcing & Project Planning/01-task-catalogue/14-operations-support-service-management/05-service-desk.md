# Layer 10 — 2.14.05 Service Desk

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.05 |
| Capability | Service Desk |
| Task Catalogue ID | 14.05 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Establish the service desk as the controlled entry point for operational incidents and requests.

## Source Implementation Activities

1. Define service desk responsibilities.
2. Configure ticket categorisation.
3. Define routing and escalation.
4. Validate service desk readiness.

## Implementation Tasks

### L10-14.05-001 — Define Service Desk Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define how Genesys Cloud incidents and requests enter and are managed by the service desk.

**Dependencies**

- Support model

**Deliverable**

Service desk process.

**Acceptance Criteria**

Process is documented and approved.

### L10-14.05-002 — Configure Service Desk Categories and Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define ticket categories, priorities, routing and escalation rules.

**Dependencies**

- L10-14.05-001

**Deliverable**

Service desk configuration.

**Acceptance Criteria**

Tickets can be correctly categorised and routed.

### L10-14.05-003 — Validate Service Desk Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Execute representative incident and request scenarios through the service desk.

**Dependencies**

- L10-14.05-002

**Deliverable**

Service desk validation evidence.

**Acceptance Criteria**

Priority, routing and escalation operate as designed.

## Definition of Done

The service desk process is documented, configured, tested and ready for BAU.

---