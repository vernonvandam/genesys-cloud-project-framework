# Layer 10 — 2.04.23 Voice ACD Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.23 |
| Capability | Voice ACD Routing |
| Task Catalogue ID | 04.23 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11 |

## Capability Objective

Implement voice interaction routing from entry point through queue selection and agent delivery.

## Source Implementation Activities

1. Define voice routing requirements.
2. Map voice entry points to queues.
3. Configure voice routing.
4. Validate voice delivery.
5. Validate cutover.

## Implementation Tasks

### L10-04.23-001 — Define Voice Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define voice routing requirements by number, entry point, queue, language, skill and business process.

**Dependencies**

- Telephony architecture
- Queue architecture

**Deliverable**

Voice routing matrix.

**Acceptance Criteria**

All voice routing requirements are approved.

### L10-04.23-002 — Configure Voice ACD Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | YES |

**Description**

Configure voice routing from entry point through queue and agent selection.

**Dependencies**

- L10-04.23-001
- Voice telephony configuration
- Queue configuration

**Deliverable**

Configured voice ACD routing.

**Acceptance Criteria**

Voice interactions reach the correct queues and agents.

### L10-04.23-003 — Validate Voice ACD Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h per routing model |
| Critical Path | YES |

**Description**

Validate voice routing across normal, exception, overflow and closed-hours scenarios.

**Dependencies**

- L10-04.23-002

**Deliverable**

Voice routing test evidence.

**Acceptance Criteria**

Voice routing scenarios pass.

### L10-04.23-004 — Validate Production Voice Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate production voice routing immediately after cutover.

**Dependencies**

- Production cutover

**Deliverable**

Production routing validation.

**Acceptance Criteria**

Production calls route correctly.

## Definition of Done

Voice ACD routing is implemented, tested and validated after production cutover.

---
