# Layer 10 — 2.05.31 Flow Security & Sensitive Data

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.31 |
| Capability | Flow Security & Sensitive Data |
| Task Catalogue ID | 05.31 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Ensure Architect flows protect sensitive data and conform to customer security, privacy and compliance requirements.

## Source Implementation Activities

1. Identify sensitive data.
2. Design secure flow behaviour.
3. Implement controls.
4. Validate security.

## Implementation Tasks

### Activity 01 — Define Flow Security

#### L10-05.31-001 — Classify Flow Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify sensitive, personal, financial and regulated information processed by Architect.

**Dependencies**

- Security architecture
- Data classification

**Deliverable**

Flow data classification.

**Acceptance Criteria**

Sensitive data requirements are approved.

---

#### L10-05.31-002 — Implement Flow Security Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Implement approved data protection, access, masking, authentication and retention controls.

**Dependencies**

- L10-05.31-001

**Deliverable**

Secured Architect flows.

**Acceptance Criteria**

Security requirements are implemented.

---

#### L10-05.31-003 — Validate Flow Security

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

Validate sensitive data exposure, authentication, logging and flow access behaviour.

**Dependencies**

- L10-05.31-002

**Deliverable**

Flow security validation evidence.

**Acceptance Criteria**

Security controls pass validation.