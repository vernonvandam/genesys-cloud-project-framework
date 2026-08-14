# Layer 10 — 2.11.09 Role-Based Access Control

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.09 |
| Capability | Role-Based Access Control |
| Task Catalogue ID | 11.09 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10 |

## Capability Objective

Implement a least-privilege role model aligned with business responsibilities.

## Implementation Tasks

### Activity 01 — Design RBAC

#### L10-11.09-001 — Define RBAC Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define roles, role ownership, access boundaries and business responsibilities.

**Dependencies**

- Identity security
- Organisation structure

**Deliverable**

RBAC matrix.

**Acceptance Criteria**

Roles and ownership are approved.

---

#### L10-11.09-002 — Implement and Validate RBAC

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure roles and validate representative access scenarios.

**Dependencies**

- L10-11.09-001

**Deliverable**

RBAC configuration and validation evidence.

**Acceptance Criteria**

Users receive only approved role-based access.