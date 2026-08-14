# Layer 10 — 2.14.20 Platform Health

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.20 |
| Capability | Platform Health |
| Task Catalogue ID | 14.20 |
| Primary Layer 1 Phases | P08, P09, P11, P12 |

## Capability Objective

Establish repeatable assessment of Genesys Cloud platform health.

## Implementation Tasks

### L10-14.20-001 — Define Platform Health Checks

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define operational checks covering availability, configuration, integrations and key services.

**Dependencies**

- Monitoring
- Platform architecture

**Deliverable**

Platform health checklist.

**Acceptance Criteria**

Health checks are defined and measurable.

### L10-14.20-002 — Establish Health Assessment Procedure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define frequency, ownership, evidence and escalation for platform health checks.

**Dependencies**

- L10-14.20-001

**Deliverable**

Health assessment procedure.

**Acceptance Criteria**

Health checks have owners and schedules.

### L10-14.20-003 — Execute Baseline Health Assessment

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Execute the baseline health assessment after go-live.

**Dependencies**

- L10-14.20-002
- Production deployment

**Deliverable**

Platform health report.

**Acceptance Criteria**

No unresolved critical health conditions remain.

## Definition of Done

Platform health checks are defined, repeatable and operational.

---
