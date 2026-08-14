# Layer 10 — 2.08.06 Data Classification

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.06 |
| Capability | Data Classification |
| Task Catalogue ID | 08.06 |
| Primary Layer 1 Phases | P02, P03, P04, P07, P08 |

## Capability Objective

Classify data exchanged through integrations and apply appropriate security, privacy and handling controls.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify sensitive data |
| P03 | Define classification requirements |
| P04 | Design controls |
| P07 | Implement data controls |
| P08 | Validate data handling |

## Implementation Tasks

### L10-08.06-001 — Identify Sensitive Data

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

Identify personal, confidential, regulated and sensitive data exchanged by integrations.

**Dependencies**

- Data inventory

**Deliverable**

Sensitive data register.

**Acceptance Criteria**

Relevant sensitive data classes are identified.

### L10-08.06-002 — Define Data Classification Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define classification rules and handling requirements for each data class.

**Dependencies**

- L10-08.06-001

**Deliverable**

Data classification matrix.

**Acceptance Criteria**

Classification requirements are approved.

### L10-08.06-003 — Validate Data Handling

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

Validate that integration flows handle sensitive data according to approved requirements.

**Dependencies**

- L10-08.06-002
- Integration testing

**Deliverable**

Data classification validation evidence.

**Acceptance Criteria**

Sensitive data is handled according to approved controls.