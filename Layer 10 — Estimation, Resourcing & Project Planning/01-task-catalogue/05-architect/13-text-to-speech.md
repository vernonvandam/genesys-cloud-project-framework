# Layer 10 — 2.05.13 Text-to-Speech

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.13 |
| Capability | Text-to-Speech |
| Task Catalogue ID | 05.13 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Configure Text-to-Speech for dynamic and static Architect messaging while maintaining intelligibility and customer experience.

## Source Implementation Activities

1. Identify TTS requirements.
2. Configure TTS.
3. Validate speech output.

## Implementation Tasks

### Activity 01 — Define TTS Requirements

#### L10-05.13-001 — Define Text-to-Speech Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define where TTS is required, including language, voice, dynamic content and pronunciation requirements.

**Dependencies**

- Prompt requirements

**Deliverable**

TTS requirements.

**Acceptance Criteria**

TTS requirements are approved.

---

#### L10-05.13-002 — Configure Text-to-Speech

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Configure TTS prompts and dynamic speech content within applicable flows.

**Dependencies**

- L10-05.13-001

**Deliverable**

Configured TTS implementation.

**Acceptance Criteria**

TTS operates using approved language and voice settings.

---

#### L10-05.13-003 — Validate TTS Output

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Validate pronunciation, clarity, dynamic values and customer experience.

**Dependencies**

- L10-05.13-002

**Deliverable**

TTS validation evidence.

**Acceptance Criteria**

TTS output is intelligible and meets requirements.