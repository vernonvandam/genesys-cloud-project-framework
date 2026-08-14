FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/21-data-residency.md

# Layer 10 — 2.11.21 Data Residency

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.21 |
| Capability | Data Residency |
| Task Catalogue ID | 11.21 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P10 |

## Capability Objective

Ensure regional hosting and data residency requirements are understood, approved and validated.

## Implementation Tasks

### Activity 01 — Establish Data Residency

#### L10-11.21-001 — Confirm Data Residency Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm regulatory, contractual and customer requirements for data location.

**Dependencies**

- Customer requirements
- Regulatory requirements

**Deliverable**

Data residency decision.

**Acceptance Criteria**

Approved data residency requirements are documented.

---

#### L10-11.21-002 — Validate Regional Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that the production organisation and applicable services comply with approved residency requirements.

**Dependencies**

- L10-11.21-001
- Organisation configuration

**Deliverable**

Data residency validation.

**Acceptance Criteria**

Production residency requirements are satisfied.