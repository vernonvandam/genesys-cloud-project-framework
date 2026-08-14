<!-- FILE: 18-extensions-internal-dialling.md -->

# Layer 10 — 2.03.18 Extensions & Internal Dialling

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.18 |
| Capability | Extensions & Internal Dialling |
| Task Catalogue ID | 03.18 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define and implement internal extensions and internal voice-dialling requirements where required.

## Source Implementation Activities

1. Define extension requirements.
2. Establish numbering scheme.
3. Configure.
4. Test.

## Implementation Tasks

#### L10-03.18-001 — Define Extension Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define extension length, assignment and internal-dialling requirements.

**Dependencies**

- User requirements

**Deliverable**

Extension requirements.

**Acceptance Criteria**

Requirements approved.

#### L10-03.18-002 — Define Extension Numbering Scheme

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define extension numbering and conflict rules.

**Dependencies**

- L10-03.18-001

**Deliverable**

Extension numbering design.

**Acceptance Criteria**

Design approved.

#### L10-03.18-003 — Configure Internal Dialling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure required extension and internal-dialling behaviour.

**Dependencies**

- L10-03.18-002

**Deliverable**

Internal dialling configuration.

**Acceptance Criteria**

Internal dialling operates as designed.

#### L10-03.18-004 — Test Extensions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Test extension-to-extension and extension-to-PSTN behaviour.

**Dependencies**

- L10-03.18-003

**Deliverable**

Extension test evidence.

**Acceptance Criteria**

All approved scenarios pass.

## Capability-Level Dependencies

- Users
- Number plan
- Telephony model

## Capability-Level Estimation Considerations

Estimate based on user population and numbering complexity.

## Definition of Done

Internal dialling and extensions operate as designed.