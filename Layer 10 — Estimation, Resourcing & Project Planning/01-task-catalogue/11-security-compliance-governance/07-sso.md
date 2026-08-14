# Layer 10 — 2.11.07 SSO

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.07 |
| Capability | SSO |
| Task Catalogue ID | 11.07 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10 |

## Capability Objective

Design, configure and validate enterprise single sign-on for Genesys Cloud.

## Implementation Tasks

### Activity 01 — Configure SSO

#### L10-11.07-001 — Define SSO Integration Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define the identity provider, federation protocol, claims, certificates, redirect requirements and ownership.

**Dependencies**

- Authentication model
- Customer identity-provider requirements

**Deliverable**

SSO design.

**Acceptance Criteria**

SSO requirements are approved.

---

#### L10-11.07-002 — Configure and Test SSO

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure SSO and validate successful and failed authentication scenarios.

**Dependencies**

- L10-11.07-001
- Identity provider configuration

**Deliverable**

SSO configuration and test evidence.

**Acceptance Criteria**

Approved users can authenticate through SSO and failure handling operates as designed.