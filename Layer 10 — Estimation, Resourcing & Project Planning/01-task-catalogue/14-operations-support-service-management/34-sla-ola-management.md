# Layer 10 — 2.14.34 SLA / OLA Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.34 |
| Capability | SLA / OLA Management |
| Task Catalogue ID | 14.34 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Define measurable service and operational commitments.

## Implementation Tasks

### L10-14.34-001 — Define SLA and OLA Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define service targets for availability, incidents, requests, support and escalation.

**Dependencies**

- Support model
- Customer service requirements

**Deliverable**

SLA/OLA requirements.

**Acceptance Criteria**

Targets are agreed.

### L10-14.34-002 — Define SLA Measurement Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define how service targets will be measured and reported.

**Dependencies**

- L10-14.34-001
- KPI management

**Deliverable**

SLA measurement model.

**Acceptance Criteria**

Measures and calculation methods are documented.

### L10-14.34-003 — Validate SLA Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that SLA/OLA measures can be produced from operational data.

**Dependencies**

- L10-14.34-002

**Deliverable**

SLA validation report.

**Acceptance Criteria**

Required SLA measures are reproducible.

## Definition of Done

SLA/OLA commitments are defined, measurable and operational.

---