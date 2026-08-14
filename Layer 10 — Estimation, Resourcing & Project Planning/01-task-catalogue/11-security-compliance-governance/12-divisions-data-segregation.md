FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/12-divisions-data-segregation.md

# Layer 10 — 2.11.12 Divisions & Data Segregation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.12 |
| Capability | Divisions & Data Segregation |
| Task Catalogue ID | 11.12 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10 |

## Capability Objective

Establish organisational divisions and resource segregation appropriate to the customer security model.

## Implementation Tasks

### Activity 01 — Design Segregation

#### L10-11.12-001 — Define Division and Segregation Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define divisions, ownership and resource segregation requirements.

**Dependencies**

- Organisation architecture
- Security requirements

**Deliverable**

Division and segregation design.

**Acceptance Criteria**

Segregation model is approved.

---

#### L10-11.12-002 — Validate Resource Segregation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that users and roles cannot access resources outside approved boundaries.

**Dependencies**

- L10-11.12-001
- Division configuration

**Deliverable**

Segregation validation evidence.

**Acceptance Criteria**

Cross-division access behaves according to design.