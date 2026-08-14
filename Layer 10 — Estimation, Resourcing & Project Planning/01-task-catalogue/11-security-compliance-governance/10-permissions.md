FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/10-permissions.md

# Layer 10 — 2.11.10 Permissions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.10 |
| Capability | Permissions |
| Task Catalogue ID | 11.10 |
| Primary Layer 1 Phases | P04, P05, P06, P08, P10 |

## Capability Objective

Define and validate the permission model supporting Genesys Cloud roles and business functions.

## Implementation Tasks

### Activity 01 — Define Permissions

#### L10-11.10-001 — Build Permission Matrix

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map business functions to required Genesys Cloud permissions.

**Dependencies**

- RBAC model
- Business role catalogue

**Deliverable**

Permission matrix.

**Acceptance Criteria**

Permissions are mapped to approved roles.

---

#### L10-11.10-002 — Validate Permissions

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate positive and negative access scenarios.

**Dependencies**

- L10-11.10-001
- RBAC configuration

**Deliverable**

Permission validation evidence.

**Acceptance Criteria**

Permissions match approved access requirements.