# Layer 10 — 2.05.26 Holiday & Closure Handling

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.26 |
| Capability | Holiday & Closure Handling |
| Task Catalogue ID | 05.26 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Implement predictable Architect behaviour for holidays, closures, emergency events and other exceptional operating conditions.

## Source Implementation Activities

1. Define closure requirements.
2. Configure holiday handling.
3. Validate closure behaviour.

## Implementation Tasks

### Activity 01 — Define Closure Model

#### L10-05.26-001 — Define Holiday and Closure Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define holiday calendars, closure messages, emergency handling and alternate routing.

**Dependencies**

- Business-hours requirements

**Deliverable**

Holiday and closure matrix.

**Acceptance Criteria**

Closure requirements are approved.

---

#### L10-05.26-002 — Configure Holiday Handling

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure holiday and closure behaviour in applicable flows.

**Dependencies**

- L10-05.26-001

**Deliverable**

Configured closure handling.

**Acceptance Criteria**

Approved closure behaviour is implemented.

---

#### L10-05.26-003 — Validate Holiday Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate holiday, emergency and closure scenarios.

**Dependencies**

- L10-05.26-002

**Deliverable**

Holiday validation evidence.

**Acceptance Criteria**

All closure scenarios operate correctly.