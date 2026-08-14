# Layer 10 — 2.11.23 PII & Sensitive Data

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.23 |
| Capability | PII & Sensitive Data |
| Task Catalogue ID | 11.23 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P07, P08 |

## Capability Objective

Identify and protect personally identifiable information and sensitive data handled by the solution.

## Implementation Tasks

### Activity 01 — Identify Sensitive Data

#### L10-11.23-001 — Identify PII and Sensitive Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify PII, sensitive information and data flows requiring enhanced protection.

**Dependencies**

- Data inventory
- Privacy assessment

**Deliverable**

PII and sensitive-data register.

**Acceptance Criteria**

Relevant sensitive data is identified and classified.

---

#### L10-11.23-002 — Validate Sensitive Data Controls

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

Validate masking, access, retention, logging and handling controls for sensitive data.

**Dependencies**

- L10-11.23-001

**Deliverable**

Sensitive-data control validation.

**Acceptance Criteria**

Sensitive data is handled according to approved requirements.