FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/03-security-architecture.md

# Layer 10 — 2.11.03 Security Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.03 |
| Capability | Security Architecture |
| Task Catalogue ID | 11.03 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10 |

## Capability Objective

Define the target security architecture and controls for the Genesys Cloud solution.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Establish security architecture requirements |
| P04 | Design target security architecture |
| P05 | Establish security foundations |
| P06 | Implement controls |
| P08 | Validate controls |
| P10 | Validate production security |

## Source Implementation Activities

1. Define security architecture.
2. Define security boundaries.
3. Map security controls.
4. Validate architecture.

## Implementation Tasks

### Activity 01 — Design Security Architecture

#### L10-11.03-001 — Define Security Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define identity, access, data, integration, monitoring and administrative security architecture.

**Dependencies**

- Security requirements
- Solution architecture

**Deliverable**

Security architecture.

**Acceptance Criteria**

Security architecture is approved.

---

#### L10-11.03-002 — Validate Security Architecture

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

Validate that the implemented solution conforms to the approved security architecture.

**Dependencies**

- L10-11.03-001
- Security configuration

**Deliverable**

Architecture validation record.

**Acceptance Criteria**

No material security architecture deviations remain unresolved.

## Definition of Done

Security architecture is approved, implemented and validated.