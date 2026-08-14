# Layer 10 — 2.14.41 Business Continuity

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.41 |
| Capability | Business Continuity |
| Task Catalogue ID | 14.41 |
| Primary Layer 1 Phases | P03, P04, P09, P11, P12 |

## Capability Objective

Define how business operations continue during material Genesys Cloud disruption.

## Implementation Tasks

### L10-14.41-001 — Identify Business Continuity Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify critical business services, tolerances and continuity requirements.

**Dependencies**

- Business requirements
- Resilience assessment

**Deliverable**

Business continuity requirements.

**Acceptance Criteria**

Continuity requirements are approved.

### L10-14.41-002 — Define Genesys Cloud Continuity Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define operational procedures for maintaining or restoring critical service during disruption.

**Dependencies**

- L10-14.41-001

**Deliverable**

Business continuity procedure.

**Acceptance Criteria**

Continuity procedures are approved.

### L10-14.41-003 — Exercise Business Continuity

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Conduct a continuity exercise or tabletop.

**Dependencies**

- L10-14.41-002

**Deliverable**

Continuity exercise results.

**Acceptance Criteria**

Critical roles and procedures are validated.

## Definition of Done

Business continuity requirements and procedures are documented and exercised.

---