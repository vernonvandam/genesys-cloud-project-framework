# Layer 10 — 2.10.15 Recording Compliance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.15 |
| Capability | Recording Compliance |
| Task Catalogue ID | 10.15 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P10 |

## Capability Objective

Ensure recording behaviour complies with applicable legal, regulatory, privacy and customer obligations.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Identify compliance requirements |
| P04 | Design compliance controls |
| P05 | Configure controls |
| P08 | Test compliance behaviour |
| P09 | Obtain compliance acceptance |
| P10 | Confirm production compliance |

## Source Implementation Activities

1. Identify regulatory obligations.
2. Map obligations to recording controls.
3. Implement controls.
4. Validate compliance.

## Implementation Tasks

### Activity 01 — Compliance Assessment

#### L10-10.15-001 — Identify Recording Compliance Requirements

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

Identify legal, regulatory, privacy and customer-specific recording obligations.

**Dependencies**

- Customer compliance assessment

**Deliverable**

Recording compliance requirements.

**Acceptance Criteria**

Applicable requirements are documented.

#### L10-10.15-002 — Map Compliance Requirements to Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map compliance obligations to recording, access, retention and security controls.

**Dependencies**

- L10-10.15-001

**Deliverable**

Compliance control matrix.

**Acceptance Criteria**

Compliance requirements have control coverage.

### Activity 02 — Implement and Validate

#### L10-10.15-003 — Implement Recording Compliance Controls

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

Implement approved compliance controls.

**Dependencies**

- L10-10.15-002

**Deliverable**

Configured compliance controls.

**Acceptance Criteria**

Controls are implemented.

#### L10-10.15-004 — Validate Recording Compliance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Compliance Lead |
| Customer Responsibility | YES |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate recording behaviour against compliance requirements.

**Dependencies**

- L10-10.15-003

**Deliverable**

Compliance validation record.

**Acceptance Criteria**

Customer compliance owner approves results.

## Definition of Done

Recording controls meet documented compliance obligations and have been accepted.

---
