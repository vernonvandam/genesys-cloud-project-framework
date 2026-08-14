# Layer 10 — 2.05.22 Authentication & Verification

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.22 |
| Capability | Authentication & Verification |
| Task Catalogue ID | 05.22 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Implement customer authentication and verification journeys within Architect.

## Source Implementation Activities

1. Define verification requirements.
2. Design authentication journey.
3. Configure verification.
4. Validate security outcomes.

## Implementation Tasks

### Activity 01 — Define Verification

#### L10-05.22-001 — Define Authentication Requirements

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

Define authentication factors, verification rules, failure handling and security requirements.

**Dependencies**

- Security requirements
- Customer identity requirements

**Deliverable**

Authentication specification.

**Acceptance Criteria**

Authentication requirements are approved.

---

#### L10-05.22-002 — Configure Authentication Flow

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure authentication and verification steps, including failure and retry handling.

**Dependencies**

- L10-05.22-001

**Deliverable**

Configured authentication flow.

**Acceptance Criteria**

Approved authentication methods operate correctly.

---

#### L10-05.22-003 — Validate Authentication

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Test successful, failed, repeated and suspicious verification scenarios.

**Dependencies**

- L10-05.22-002

**Deliverable**

Authentication validation evidence.

**Acceptance Criteria**

Security and customer verification requirements pass.