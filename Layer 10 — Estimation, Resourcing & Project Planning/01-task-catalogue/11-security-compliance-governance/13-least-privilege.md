# Layer 10 — 2.11.13 Least Privilege

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.13 |
| Capability | Least Privilege |
| Task Catalogue ID | 11.13 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Ensure users and administrators receive only the access required to perform their responsibilities.

## Implementation Tasks

### Activity 01 — Implement Least Privilege

#### L10-11.13-001 — Assess Access Against Least Privilege

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

Review roles and permissions against the minimum required business access.

**Dependencies**

- RBAC model
- Permission matrix

**Deliverable**

Least-privilege assessment.

**Acceptance Criteria**

Excess permissions are identified and resolved.

---

#### L10-11.13-002 — Validate Least Privilege

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

Test representative roles for prohibited access.

**Dependencies**

- L10-11.13-001

**Deliverable**

Least-privilege validation.

**Acceptance Criteria**

No unauthorised access paths remain.