# Layer 10 — 2.15.23 Security Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.23 |
| Capability | Security Optimisation |
| Task Catalogue ID | 15.23 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09, P11 |

## Capability Objective

Continuously improve the security posture of the Genesys Cloud environment, including identity, access, data, integrations, configuration and operational controls.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess security posture |
| P03 | Define security improvements |
| P04 | Design controls |
| P06 | Implement controls |
| P08 | Validate security |
| P09 | Operationalise security |
| P11 | Validate production security |

## Source Implementation Activities

1. Assess security posture.
2. Identify control gaps.
3. Prioritise security improvements.
4. Implement improvements.
5. Validate controls.

## Implementation Tasks

### L10-15.23-001 — Assess Security Posture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Assess identity, access, configuration, data protection, integrations and operational security controls.

**Dependencies**

- Security requirements
- Current-state configuration

**Deliverable**

Security optimisation assessment.

**Acceptance Criteria**

Security gaps and risks are documented.

### L10-15.23-002 — Define Security Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define improvements based on risk, compliance, architecture and operational requirements.

**Dependencies**

- L10-15.23-001

**Deliverable**

Security improvement plan.

**Acceptance Criteria**

Actions are prioritised and approved.

### L10-15.23-003 — Implement Security Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Implement approved security improvements.

**Dependencies**

- L10-15.23-002

**Deliverable**

Updated security controls.

**Acceptance Criteria**

Controls are implemented without unacceptable service impact.

### L10-15.23-004 — Validate Security Controls

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate production operation of improved security controls.

**Dependencies**

- L10-15.23-003

**Deliverable**

Security validation evidence.

**Acceptance Criteria**

Security controls operate as designed.