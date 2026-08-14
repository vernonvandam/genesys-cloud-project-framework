# Layer 10 — 2.11.45 Production Security Validation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.45 |
| Capability | Production Security Validation |
| Task Catalogue ID | 11.45 |
| Primary Layer 1 Phases | P08, P09, P10, P11 |

## Capability Objective

Confirm the production environment satisfies approved security requirements before and after go-live.

## Implementation Tasks

### Activity 01 — Validate Production Security

#### L10-11.45-001 — Complete Production Security Checklist

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate production identity, permissions, data, integrations, logging and governance controls.

**Dependencies**

- Security testing
- Compliance testing
- Production configuration

**Deliverable**

Production security checklist.

**Acceptance Criteria**

All mandatory production security controls pass.

---

#### L10-11.45-002 — Perform Post-Cutover Security Validation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate security controls after production cutover and data migration.

**Dependencies**

- L10-11.45-001
- Production cutover

**Deliverable**

Post-cutover security validation.

**Acceptance Criteria**

Production security remains compliant after cutover.