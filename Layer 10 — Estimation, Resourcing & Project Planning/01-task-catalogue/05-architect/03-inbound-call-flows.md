# Layer 10 — 2.05.03 Inbound Call Flows

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.03 |
| Capability | Inbound Call Flows |
| Task Catalogue ID | 05.03 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Design, build, test and deploy inbound voice flows supporting customer journeys, IVR treatment, data collection, self-service and routing.

## Source Implementation Activities

1. Discover inbound call journeys.
2. Design inbound flows.
3. Build inbound flows.
4. Test and deploy inbound flows.

## Implementation Tasks

### Activity 01 — Design Inbound Flows

#### L10-05.03-001 — Define Inbound Flow Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document inbound call journeys, entry conditions, customer inputs, business rules, self-service, routing and exit paths.

**Dependencies**

- Architect scope
- Voice and telephony requirements

**Deliverable**

Inbound flow requirements.

**Acceptance Criteria**

Customer journey and business requirements are approved.

---

#### L10-05.03-002 — Build Inbound Call Flow

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure the inbound flow according to the approved design.

**Dependencies**

- L10-05.03-001
- Required queues
- Required schedules
- Required prompts
- Required data dependencies

**Deliverable**

Configured inbound flow.

**Acceptance Criteria**

Flow implements all approved journey paths and failure paths.

---

#### L10-05.03-003 — Validate Inbound Call Flow

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute functional, negative-path, routing and integration validation for the inbound flow.

**Dependencies**

- L10-05.03-002

**Deliverable**

Inbound flow test evidence.

**Acceptance Criteria**

All agreed test scenarios pass and defects are resolved or accepted.