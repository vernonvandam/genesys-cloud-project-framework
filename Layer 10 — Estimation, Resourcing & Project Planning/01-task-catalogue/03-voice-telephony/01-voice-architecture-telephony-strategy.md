# Layer 10 — 2.03.01 Voice Architecture & Telephony Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.01 |
| Capability | Voice Architecture & Telephony Strategy |
| Task Catalogue ID | 03.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P08, P09, P10, P12 |

## Capability Objective

Define the target voice architecture, telephony operating model, carrier strategy, number strategy, network requirements, endpoint approach, resilience model and operational ownership.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish telephony scope and ownership |
| P02 | Assess current-state voice architecture |
| P03 | Define voice requirements |
| P04 | Produce target voice architecture |
| P08 | Validate architecture through testing |
| P09 | Confirm operational readiness |
| P10 | Approve production deployment |
| P12 | Complete voice architecture handover |

## Source Implementation Activities

1. Establish voice scope and ownership.
2. Assess current-state telephony.
3. Define target-state voice architecture.
4. Define carrier, number, network and endpoint strategy.
5. Validate architecture.
6. Document and obtain approval.

## Implementation Tasks

### Activity 01 — Establish Voice Scope

#### L10-03.01-001 — Confirm Voice Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm inbound, outbound, internal, emergency, endpoint and telephony integration scope.

**Dependencies**

- Project initiation
- Business requirements

**Deliverable**

Voice scope definition.

**Acceptance Criteria**

Voice scope is documented and approved.

### Activity 02 — Assess Current State

#### L10-03.01-002 — Assess Existing Telephony Architecture

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess carriers, PBX, SIP, numbers, sites, endpoints, routing and network dependencies.

**Dependencies**

- L10-03.01-001

**Deliverable**

Current-state telephony assessment.

**Acceptance Criteria**

Existing architecture and dependencies are documented.

### Activity 03 — Define Target Architecture

#### L10-03.01-003 — Define Target Voice Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define the target Genesys Cloud voice architecture and major telephony components.

**Dependencies**

- L10-03.01-002
- Telephony requirements

**Deliverable**

Voice architecture design.

**Acceptance Criteria**

Architecture is documented and approved.

#### L10-03.01-004 — Define Carrier and Number Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define carrier ownership, number ownership, porting requirements, DID strategy and outbound presentation requirements.

**Dependencies**

- L10-03.01-003

**Deliverable**

Carrier and numbering strategy.

**Acceptance Criteria**

Carrier and numbering model is approved.

### Activity 04 — Architecture Validation

#### L10-03.01-005 — Validate Voice Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate the implemented voice architecture against approved design.

**Dependencies**

- L10-03.01-003
- Voice configuration
- Voice testing

**Deliverable**

Architecture validation record.

**Acceptance Criteria**

Implemented architecture conforms to approved design.

### Activity 05 — Handover

#### L10-03.01-006 — Complete Voice Architecture Handover

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Document final architecture, ownership, dependencies and support requirements.

**Dependencies**

- L10-03.01-005

**Deliverable**

Voice architecture handover pack.

**Acceptance Criteria**

BAU owner accepts the documentation.

## Capability-Level Dependencies

- Core Platform
- Identity and Access
- Network architecture
- Carrier requirements
- Routing requirements
- Recording requirements

## Capability-Level Estimation Considerations

Effort increases with:

- Multiple countries
- Multiple carriers
- Existing PBX complexity
- Hybrid architecture
- Number migration
- High availability requirements
- Complex network topology

## Definition of Done

The voice architecture is approved, implemented consistently, validated and handed over.