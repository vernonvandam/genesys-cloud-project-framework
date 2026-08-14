# Layer 10 — 2.05.12 Prompt Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.12 |
| Capability | Prompt Management |
| Task Catalogue ID | 05.12 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Manage Architect prompts, recordings, naming, versioning and lifecycle requirements.

## Source Implementation Activities

1. Define prompt requirements.
2. Configure prompt resources.
3. Validate prompt usage.

## Implementation Tasks

### Activity 01 — Define Prompt Catalogue

#### L10-05.12-001 — Define Prompt Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define required prompts, languages, wording, ownership and recording requirements.

**Dependencies**

- Flow requirements

**Deliverable**

Prompt catalogue.

**Acceptance Criteria**

Prompt catalogue is approved.

---

#### L10-05.12-002 — Configure Prompt Resources

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Create or upload approved prompt resources and associate them with flows.

**Dependencies**

- L10-05.12-001

**Deliverable**

Configured prompt resources.

**Acceptance Criteria**

Approved prompts are available and correctly associated.

---

#### L10-05.12-003 — Validate Prompt Playback

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

Validate prompt playback, sequencing, language and failure behaviour.

**Dependencies**

- L10-05.12-002

**Deliverable**

Prompt validation evidence.

**Acceptance Criteria**

All required prompts play correctly.