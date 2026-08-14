# Layer 10 — 2.14.22 Telephony Operations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.22 |
| Capability | Telephony Operations |
| Task Catalogue ID | 14.22 |
| Primary Layer 1 Phases | P08, P09, P11, P12 |

## Capability Objective

Establish operational processes for Genesys Cloud telephony services.

## Implementation Tasks

### L10-14.22-001 — Define Telephony Operational Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define operational responsibilities for numbers, sites, trunks, routing, devices and carrier dependencies.

**Dependencies**

- Telephony architecture
- Support model

**Deliverable**

Telephony operations model.

**Acceptance Criteria**

Operational ownership is documented.

### L10-14.22-002 — Develop Telephony Runbooks

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Create procedures for common telephony incidents and administrative activities.

**Dependencies**

- L10-14.22-001

**Deliverable**

Telephony runbook set.

**Acceptance Criteria**

Priority telephony scenarios have documented procedures.

### L10-14.22-003 — Validate Telephony Operations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate telephony operational procedures after production deployment.

**Dependencies**

- L10-14.22-002
- Go-live

**Deliverable**

Telephony operations validation.

**Acceptance Criteria**

Representative telephony incidents can be diagnosed and escalated.

## Definition of Done

Telephony operations are documented, owned and validated.

---