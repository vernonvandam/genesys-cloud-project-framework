# Layer 10 — 2.10.16 PCI & Sensitive Data Controls

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.16 |
| Capability | PCI & Sensitive Data Controls |
| Task Catalogue ID | 10.16 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Protect PCI, payment and other sensitive information from inappropriate recording or exposure.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define sensitive-data requirements |
| P04 | Design controls |
| P05 | Configure controls |
| P08 | Validate controls |
| P09 | Obtain compliance acceptance |

## Source Implementation Activities

1. Identify sensitive data.
2. Define protection requirements.
3. Configure controls.
4. Test sensitive-data scenarios.

## Implementation Tasks

### Activity 01 — Sensitive Data Analysis

#### L10-10.16-001 — Identify PCI and Sensitive Data Scenarios

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Compliance Lead |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify payment, authentication, personal and other sensitive data handled during interactions.

**Dependencies**

- Data classification

**Deliverable**

Sensitive-data scenario catalogue.

**Acceptance Criteria**

Sensitive scenarios are documented.

#### L10-10.16-002 — Design Sensitive Data Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define controls preventing sensitive data from being captured or exposed.

**Dependencies**

- L10-10.16-001

**Deliverable**

Sensitive-data control design.

**Acceptance Criteria**

Control design is approved.

### Activity 02 — Implement and Validate

#### L10-10.16-003 — Configure Sensitive Data Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Implement approved PCI and sensitive-data controls.

**Dependencies**

- L10-10.16-002

**Deliverable**

Configured sensitive-data controls.

**Acceptance Criteria**

Controls operate as designed.

#### L10-10.16-004 — Validate Sensitive Data Protection

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute sensitive-data scenarios and confirm expected protection.

**Dependencies**

- L10-10.16-003

**Deliverable**

Sensitive-data validation evidence.

**Acceptance Criteria**

PCI and sensitive-data test cases pass.

## Definition of Done

Sensitive-data protection is implemented and validated.

---
