FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/05-identity-security.md

# Layer 10 — 2.11.05 Identity Security

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.05 |
| Capability | Identity Security |
| Task Catalogue ID | 11.05 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P10 |

## Capability Objective

Define and implement secure identity controls for Genesys Cloud users and administrators.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover identity requirements |
| P03 | Define identity controls |
| P04 | Design identity security |
| P05 | Establish identity foundations |
| P08 | Validate access |
| P10 | Validate production access |

## Implementation Tasks

### Activity 01 — Define Identity Security

#### L10-11.05-001 — Assess Identity Security Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess identity lifecycle, authentication, access, privileged access and identity governance requirements.

**Dependencies**

- Identity and access strategy

**Deliverable**

Identity security assessment.

**Acceptance Criteria**

Identity requirements are documented.

---

#### L10-11.05-002 — Validate Identity Security Controls

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

Validate implemented identity controls against approved requirements.

**Dependencies**

- L10-11.05-001
- Identity configuration

**Deliverable**

Identity security validation.

**Acceptance Criteria**

Identity controls meet approved requirements.