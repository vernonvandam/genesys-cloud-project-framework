# Layer 10 — 2.14.06 L1 Support

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.06 |
| Capability | L1 Support |
| Task Catalogue ID | 14.06 |
| Primary Layer 1 Phases | P09, P11, P12 |

## Capability Objective

Establish first-line operational support for common user, platform and service issues.

## Source Implementation Activities

1. Define L1 responsibilities.
2. Establish triage procedures.
3. Provide knowledge and runbooks.
4. Validate L1 support readiness.

## Implementation Tasks

### L10-14.06-001 — Define L1 Support Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the issues L1 can resolve, diagnose or escalate.

**Dependencies**

- Support model
- Service desk

**Deliverable**

L1 responsibility matrix.

**Acceptance Criteria**

L1 boundaries are approved.

### L10-14.06-002 — Develop L1 Triage Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Genesys Cloud Administrator |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Create procedures for common operational incidents and first-line diagnostics.

**Dependencies**

- L10-14.06-001
- Runbooks

**Deliverable**

L1 triage procedures.

**Acceptance Criteria**

Common scenarios have documented diagnostic and escalation paths.

### L10-14.06-003 — Validate L1 Support Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate L1 support during hypercare.

**Dependencies**

- L10-14.06-002
- Go-live

**Deliverable**

L1 readiness validation.

**Acceptance Criteria**

L1 can triage and escalate representative incidents.

## Definition of Done

L1 support is staffed, trained, documented and validated.

---
