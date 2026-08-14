# Layer 10 — 2.11.06 Authentication

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.06 |
| Capability | Authentication |
| Task Catalogue ID | 11.06 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10 |

## Capability Objective

Establish and validate the approved authentication model for Genesys Cloud users.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define authentication requirements |
| P04 | Design authentication |
| P05 | Configure authentication foundations |
| P08 | Test authentication |
| P10 | Validate production authentication |

## Implementation Tasks

### Activity 01 — Configure Authentication

#### L10-11.06-001 — Define Authentication Model

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

Define authentication methods, password policy requirements, federation requirements and administrative controls.

**Dependencies**

- Identity security requirements

**Deliverable**

Authentication design.

**Acceptance Criteria**

Authentication model is approved.

---

#### L10-11.06-002 — Validate Authentication

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

Test approved authentication methods using representative user accounts.

**Dependencies**

- L10-11.06-001
- Authentication configuration

**Deliverable**

Authentication test evidence.

**Acceptance Criteria**

Authorised users can authenticate and unauthorised access is rejected.