<!-- FILE: 06-genesys-cloud-voice.md -->

# Layer 10 — 2.03.06 Genesys Cloud Voice

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.06 |
| Capability | Genesys Cloud Voice |
| Task Catalogue ID | 03.06 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10, P12 |

## Capability Objective

Implement Genesys Cloud Voice where Genesys Cloud provides the required carrier and PSTN service.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define requirements |
| P04 | Design Genesys Cloud Voice |
| P05 | Prepare platform |
| P06 | Configure voice |
| P08 | Validate |
| P10 | Deploy |
| P12 | Handover |

## Source Implementation Activities

1. Confirm Genesys Cloud Voice suitability.
2. Define geography and number requirements.
3. Configure voice services.
4. Configure numbers and routing.
5. Test.
6. Handover.

## Implementation Tasks

### Activity 01 — Suitability

#### L10-03.06-001 — Confirm Genesys Cloud Voice Eligibility

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Confirm geographic, licensing, carrier, regulatory and functional suitability.

**Dependencies**

- Telephony model selection

**Deliverable**

Eligibility assessment.

**Acceptance Criteria**

Genesys Cloud Voice is approved for the target deployment.

### Activity 02 — Configure

#### L10-03.06-002 — Configure Genesys Cloud Voice

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure required Genesys Cloud Voice services and associated telephony configuration.

**Dependencies**

- L10-03.06-001

**Deliverable**

Configured Genesys Cloud Voice service.

**Acceptance Criteria**

Voice service is available for testing.

### Activity 03 — Validate

#### L10-03.06-003 — Validate Genesys Cloud Voice

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Test inbound, outbound, caller ID, media and number behaviour.

**Dependencies**

- L10-03.06-002

**Deliverable**

Voice validation evidence.

**Acceptance Criteria**

Required test cases pass.

## Capability-Level Dependencies

- Region
- Licensing
- Number strategy
- Sites
- Routing

## Capability-Level Estimation Considerations

Effort depends on number volume, geography and provisioning complexity.

## Definition of Done

Genesys Cloud Voice is configured, tested and accepted for production.