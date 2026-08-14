# Layer 10 — 2.11.15 Service Accounts

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.15 |
| Capability | Service Accounts |
| Task Catalogue ID | 11.15 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Govern non-human identities used by Genesys Cloud integrations and automation.

## Implementation Tasks

### Activity 01 — Govern Service Accounts

#### L10-11.15-001 — Identify Service Accounts

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify required service accounts, ownership, purpose and access requirements.

**Dependencies**

- Integration inventory

**Deliverable**

Service-account register.

**Acceptance Criteria**

All required service accounts have documented ownership.

---

#### L10-11.15-002 — Validate Service Account Controls

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate service-account permissions, authentication, ownership and lifecycle controls.

**Dependencies**

- L10-11.15-001

**Deliverable**

Service-account validation.

**Acceptance Criteria**

Service accounts have only approved access and documented owners.