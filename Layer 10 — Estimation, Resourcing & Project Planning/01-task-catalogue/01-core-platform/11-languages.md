# Layer 10 — 2.01.11 Languages

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.11 |
| Capability | Languages |
| Task Catalogue ID | 01.11 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define and establish the language model required across the Genesys Cloud solution, including user, routing, Architect, digital, and customer-experience requirements.

## Source Implementation Activities

1. Identify language requirements.
2. Define supported language model.
3. Configure language settings.
4. Validate language availability and behaviour.
5. Document language requirements.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.11-001 — Identify Required Languages

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Identify languages required for agents, customers, Architect flows, digital channels, reporting, and other applicable capabilities.

**Dependencies**

- Business requirements

**Deliverable**

Language requirements list.

**Acceptance Criteria**

Required languages are approved.

### Activity 02 — Design

#### L10-01.11-002 — Define Language Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define the target language configuration and identify dependencies such as translation, TTS, speech recognition, and digital content.

**Dependencies**

- L10-01.11-001

**Deliverable**

Language strategy.

**Acceptance Criteria**

Language strategy is approved.

### Activity 03 — Configure

#### L10-01.11-003 — Configure Supported Languages

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | 0.25h per language group |
| Critical Path | YES |

**Description**

Configure required language settings within the relevant Genesys Cloud components.

**Dependencies**

- L10-01.11-002

**Deliverable**

Language configuration.

**Acceptance Criteria**

Required language configuration is available.

### Activity 04 — Validate

#### L10-01.11-004 — Validate Language Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per language group |
| Critical Path | YES |

**Description**

Validate language selection and behaviour across applicable customer journeys.

**Dependencies**

- L10-01.11-003

**Deliverable**

Language validation evidence.

**Acceptance Criteria**

Required language scenarios pass validation.

## Estimation Considerations

Drivers include:

- number of languages
- digital and voice scope
- translation requirements
- speech capabilities
- content volume
- testing requirements

## Definition of Done

Required languages are identified, configured, validated, and documented.