# Layer 10 — 2.05.15 DTMF & Keypad Input

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.15 |
| Capability | DTMF & Keypad Input |
| Task Catalogue ID | 05.15 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Implement reliable DTMF and keypad input for IVR navigation, customer identification and data collection.

## Source Implementation Activities

1. Define DTMF requirements.
2. Configure keypad handling.
3. Validate input and error handling.

## Implementation Tasks

### Activity 01 — Configure DTMF

#### L10-05.15-001 — Define DTMF Input Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define expected keypad inputs, formats, lengths, retries, timeouts and invalid-input handling.

**Dependencies**

- IVR requirements

**Deliverable**

DTMF requirements.

**Acceptance Criteria**

DTMF behaviour is approved.

---

#### L10-05.15-002 — Configure DTMF Handling

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

Configure DTMF collection and validation in applicable flows.

**Dependencies**

- L10-05.15-001

**Deliverable**

Configured DTMF handling.

**Acceptance Criteria**

Valid inputs are accepted and invalid inputs are handled correctly.

---

#### L10-05.15-003 — Validate DTMF Behaviour

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

Test valid, invalid, incomplete, timeout and retry scenarios.

**Dependencies**

- L10-05.15-002

**Deliverable**

DTMF validation evidence.

**Acceptance Criteria**

All agreed DTMF scenarios pass.