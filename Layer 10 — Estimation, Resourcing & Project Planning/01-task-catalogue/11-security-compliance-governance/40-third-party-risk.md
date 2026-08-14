# Layer 10 — 2.11.40 Third-Party Risk

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.40 |
| Capability | Third-Party Risk |
| Task Catalogue ID | 11.40 |
| Primary Layer 1 Phases | P02, P03, P04, P07, P08 |

## Capability Objective

Assess security risks introduced by third-party applications, providers and integrations.

## Implementation Tasks

### Activity 01 — Assess Third-Party Risk

#### L10-11.40-001 — Identify Third-Party Security Dependencies

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify third parties that process, access or exchange Genesys Cloud data.

**Dependencies**

- Integration inventory

**Deliverable**

Third-party dependency register.

**Acceptance Criteria**

Relevant third parties are identified.

---

#### L10-11.40-002 — Complete Third-Party Security Assessment

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Review third-party security controls, contractual obligations and risk acceptance.

**Dependencies**

- L10-11.40-001

**Deliverable**

Third-party risk assessment.

**Acceptance Criteria**

Third-party risks are accepted, mitigated or rejected.