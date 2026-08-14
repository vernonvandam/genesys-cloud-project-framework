# Layer 10 — 2.14.07 L2 Support

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.07 |
| Capability | L2 Support |
| Task Catalogue ID | 14.07 |
| Primary Layer 1 Phases | P09, P11, P12 |

## Capability Objective

Establish technical L2 support for Genesys Cloud configuration and operational issues.

## Source Implementation Activities

1. Define L2 responsibilities.
2. Establish diagnostic procedures.
3. Establish escalation to L3/vendor.
4. Validate L2 capability.

## Implementation Tasks

### L10-14.07-001 — Define L2 Support Scope

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

Define technical issues L2 will investigate and resolve.

**Dependencies**

- L1 support
- Operating model

**Deliverable**

L2 responsibility matrix.

**Acceptance Criteria**

L2 responsibilities and boundaries are approved.

### L10-14.07-002 — Establish L2 Diagnostic Procedures

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

Document technical diagnostics for platform, routing, Architect, telephony, integration and digital issues.

**Dependencies**

- L10-14.07-001
- Runbooks

**Deliverable**

L2 diagnostic procedures.

**Acceptance Criteria**

Common L2 scenarios have documented diagnostic paths.

### L10-14.07-003 — Validate L2 Support

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

Validate L2 resolution and escalation capability during hypercare.

**Dependencies**

- L10-14.07-002
- Go-live

**Deliverable**

L2 validation evidence.

**Acceptance Criteria**

L2 can diagnose, resolve or escalate representative issues.

## Definition of Done

L2 support is operationally capable and validated.

---
