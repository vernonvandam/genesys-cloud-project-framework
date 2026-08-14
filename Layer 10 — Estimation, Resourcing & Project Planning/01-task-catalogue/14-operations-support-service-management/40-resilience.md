# Layer 10 — 2.14.40 Resilience

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.40 |
| Capability | Resilience |
| Task Catalogue ID | 14.40 |
| Primary Layer 1 Phases | P04, P08, P09, P11 |

## Capability Objective

Ensure operational resilience is understood, documented and validated.

## Implementation Tasks

### L10-14.40-001 — Assess Resilience Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess service dependencies, failure modes and resilience requirements.

**Dependencies**

- Solution architecture
- Business continuity

**Deliverable**

Resilience assessment.

**Acceptance Criteria**

Material failure scenarios are documented.

### L10-14.40-002 — Define Resilience Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document response and recovery procedures for material service failures.

**Dependencies**

- L10-14.40-001

**Deliverable**

Resilience procedure.

**Acceptance Criteria**

Recovery responsibilities are documented.

### L10-14.40-003 — Validate Resilience Controls

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate resilience procedures against representative failure scenarios.

**Dependencies**

- L10-14.40-002

**Deliverable**

Resilience validation evidence.

**Acceptance Criteria**

Required resilience procedures are demonstrated.

## Definition of Done

Resilience requirements and response procedures are validated.

---
