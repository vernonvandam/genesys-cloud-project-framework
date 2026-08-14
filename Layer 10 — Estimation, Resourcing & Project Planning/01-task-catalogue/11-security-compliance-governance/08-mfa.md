# Layer 10 — 2.11.08 MFA

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.08 |
| Capability | MFA |
| Task Catalogue ID | 11.08 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10 |

## Capability Objective

Define and validate multi-factor authentication requirements for Genesys Cloud access.

## Implementation Tasks

### Activity 01 — Establish MFA

#### L10-11.08-001 — Define MFA Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Determine MFA requirements for users, administrators and privileged access.

**Dependencies**

- Authentication requirements
- Customer security policy

**Deliverable**

MFA requirements.

**Acceptance Criteria**

MFA requirements are documented and approved.

---

#### L10-11.08-002 — Validate MFA Enforcement

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate MFA configuration and enforcement for representative user types.

**Dependencies**

- L10-11.08-001
- MFA configuration

**Deliverable**

MFA validation evidence.

**Acceptance Criteria**

MFA is enforced according to approved requirements.