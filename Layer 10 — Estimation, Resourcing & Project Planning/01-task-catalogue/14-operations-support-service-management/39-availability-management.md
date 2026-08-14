# Layer 10 — 2.14.39 Availability Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.39 |
| Capability | Availability Management |
| Task Catalogue ID | 14.39 |
| Primary Layer 1 Phases | P03, P04, P09, P11, P12 |

## Capability Objective

Establish operational management of service availability.

## Implementation Tasks

### L10-14.39-001 — Define Availability Requirements

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

Define service availability expectations, measurement and reporting.

**Dependencies**

- SLA/OLA management

**Deliverable**

Availability requirements.

**Acceptance Criteria**

Availability targets are approved.

### L10-14.39-002 — Establish Availability Monitoring

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Define monitoring, outage recording and availability calculation.

**Dependencies**

- L10-14.39-001
- Monitoring

**Deliverable**

Availability monitoring model.

**Acceptance Criteria**

Availability can be measured consistently.

### L10-14.39-003 — Validate Availability Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate availability measurement and reporting.

**Dependencies**

- L10-14.39-002

**Deliverable**

Availability validation report.

**Acceptance Criteria**

Availability reporting is accepted.

## Definition of Done

Availability requirements, monitoring and reporting are operational.

---
