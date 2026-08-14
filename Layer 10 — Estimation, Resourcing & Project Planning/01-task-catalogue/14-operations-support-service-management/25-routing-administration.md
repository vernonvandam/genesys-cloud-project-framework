# Layer 10 — 2.14.25 Routing Administration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.25 |
| Capability | Routing Administration |
| Task Catalogue ID | 14.25 |
| Primary Layer 1 Phases | P06, P09, P11, P12 |

## Capability Objective

Establish BAU administration and support of queues, routing, skills and related ACD configuration.

## Implementation Tasks

### L10-14.25-001 — Define Routing Administration Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define ownership of queues, skills, priorities, routing rules and operational changes.

**Dependencies**

- ACD routing implementation
- Change management

**Deliverable**

Routing administration model.

**Acceptance Criteria**

Responsibilities are documented.

### L10-14.25-002 — Develop Routing Administration Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Document procedures for common routing administration and troubleshooting.

**Dependencies**

- L10-14.25-001

**Deliverable**

Routing procedures.

**Acceptance Criteria**

Priority routing tasks have documented procedures.

### L10-14.25-003 — Validate Routing Administration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate routing administration and troubleshooting.

**Dependencies**

- L10-14.25-002

**Deliverable**

Routing operations validation.

**Acceptance Criteria**

Operational teams can manage representative routing scenarios.

## Definition of Done

Routing administration is controlled and operationally supported.

---