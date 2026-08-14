# Layer 10 — 2.03.02 Telephony Model Selection

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.02 |
| Capability | Telephony Model Selection |
| Task Catalogue ID | 03.02 |
| Primary Layer 1 Phases | P02, P03, P04, P05 |

## Capability Objective

Select the appropriate Genesys Cloud telephony deployment model based on geography, carrier requirements, regulatory constraints, network architecture, endpoints and operational requirements.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess existing telephony model |
| P03 | Define selection criteria |
| P04 | Evaluate and approve target model |
| P05 | Establish selected model |

## Source Implementation Activities

1. Assess existing telephony.
2. Identify model requirements.
3. Evaluate supported models.
4. Select target model.
5. Document decision.

## Implementation Tasks

### Activity 01 — Assess Current Model

#### L10-03.02-001 — Assess Existing Telephony Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document the current telephony model and associated carrier, network and endpoint dependencies.

**Dependencies**

- Voice discovery

**Deliverable**

Current-state model assessment.

**Acceptance Criteria**

Existing model and constraints are documented.

### Activity 02 — Evaluate Options

#### L10-03.02-002 — Define Telephony Model Selection Criteria

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

Define technical, commercial, geographic, regulatory and operational selection criteria.

**Dependencies**

- L10-03.02-001

**Deliverable**

Selection criteria.

**Acceptance Criteria**

Criteria are agreed.

#### L10-03.02-003 — Evaluate Genesys Cloud Voice Options

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Evaluate Genesys Cloud Voice, BYOC Cloud and BYOC Premises against requirements.

**Dependencies**

- L10-03.02-002

**Deliverable**

Telephony model evaluation.

**Acceptance Criteria**

Options and trade-offs are documented.

### Activity 03 — Approve Model

#### L10-03.02-004 — Approve Telephony Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain customer approval for the selected telephony model.

**Dependencies**

- L10-03.02-003

**Deliverable**

Approved architecture decision.

**Acceptance Criteria**

Decision is formally approved.

## Capability-Level Dependencies

- Voice requirements
- Carrier requirements
- Geography
- Network architecture
- Security requirements

## Capability-Level Estimation Considerations

Model selection effort increases for multi-region or hybrid deployments.

## Definition of Done

The telephony model is selected, justified, approved and ready for implementation.