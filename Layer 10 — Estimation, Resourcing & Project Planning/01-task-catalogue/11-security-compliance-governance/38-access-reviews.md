# Layer 10 — 2.11.38 Access Reviews

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.38 |
| Capability | Access Reviews |
| Task Catalogue ID | 11.38 |
| Primary Layer 1 Phases | P08, P09, P10, P11, P12 |

## Capability Objective

Validate user, role and privileged access before and after production deployment.

## Implementation Tasks

### Activity 01 — Conduct Access Review

#### L10-11.38-001 — Conduct Pre-Production Access Review

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review production users, roles, permissions, divisions and privileged access.

**Dependencies**

- RBAC validation
- Production configuration

**Deliverable**

Pre-production access review.

**Acceptance Criteria**

Production access is approved.

---

#### L10-11.38-002 — Conduct Post-Cutover Access Review

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate access following production cutover.

**Dependencies**

- L10-11.38-001
- Production deployment

**Deliverable**

Post-cutover access review.

**Acceptance Criteria**

No unexpected access exists after cutover.