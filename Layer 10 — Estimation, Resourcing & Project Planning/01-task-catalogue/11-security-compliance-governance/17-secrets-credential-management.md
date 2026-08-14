FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/17-secrets-credential-management.md

# Layer 10 — 2.11.17 Secrets & Credential Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.17 |
| Capability | Secrets & Credential Management |
| Task Catalogue ID | 11.17 |
| Primary Layer 1 Phases | P03, P04, P05, P07, P08, P09 |

## Capability Objective

Ensure credentials, secrets, certificates and tokens are securely stored, managed and rotated.

## Implementation Tasks

### Activity 01 — Establish Secret Management

#### L10-11.17-001 — Define Secret Management Requirements

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

Define approved secret stores, ownership, access, rotation and recovery requirements.

**Dependencies**

- API and integration inventory
- Enterprise security policy

**Deliverable**

Secret management design.

**Acceptance Criteria**

All credential types have an approved management approach.

---

#### L10-11.17-002 — Validate Credential Protection

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

Verify that credentials are not exposed in configuration, source code, logs or documentation.

**Dependencies**

- L10-11.17-001

**Deliverable**

Credential security validation.

**Acceptance Criteria**

Secrets are protected according to approved standards.