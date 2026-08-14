# Layer 10 — 2.11.14 Privileged Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.14 |
| Capability | Privileged Access |
| Task Catalogue ID | 11.14 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P10 |

## Capability Objective

Control administrative and privileged access to the Genesys Cloud environment.

## Implementation Tasks

### Activity 01 — Establish Privileged Access

#### L10-11.14-001 — Define Privileged Access Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define privileged roles, approval requirements, MFA, monitoring and emergency access.

**Dependencies**

- RBAC model
- MFA requirements

**Deliverable**

Privileged access model.

**Acceptance Criteria**

Privileged access requirements are approved.

---

#### L10-11.14-002 — Validate Privileged Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate privileged users, controls and auditability.

**Dependencies**

- L10-11.14-001

**Deliverable**

Privileged access validation.

**Acceptance Criteria**

Privileged access is restricted, authenticated and auditable.