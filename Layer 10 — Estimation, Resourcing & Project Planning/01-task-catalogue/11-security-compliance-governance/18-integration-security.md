FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/18-integration-security.md

# Layer 10 — 2.11.18 Integration Security

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.18 |
| Capability | Integration Security |
| Task Catalogue ID | 11.18 |
| Primary Layer 1 Phases | P03, P04, P07, P08, P10 |

## Capability Objective

Ensure all Genesys Cloud integrations meet approved authentication, data, network and security requirements.

## Implementation Tasks

### Activity 01 — Assess Integrations

#### L10-11.18-001 — Perform Integration Security Assessment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess integration authentication, data exchange, endpoints, credentials, logging and trust boundaries.

**Dependencies**

- Integration inventory
- Security architecture

**Deliverable**

Integration security assessment.

**Acceptance Criteria**

All integrations have documented security controls.

---

#### L10-11.18-002 — Validate Integration Security

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate authentication, authorisation, data protection and failure handling for integrations.

**Dependencies**

- L10-11.18-001

**Deliverable**

Integration security test evidence.

**Acceptance Criteria**

Integrations meet approved security requirements.