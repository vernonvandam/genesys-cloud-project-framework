# Layer 10 — 2.10.40 Agent Scorecards

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.40 |
| Capability | Agent Scorecards |
| Task Catalogue ID | 10.40 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P12 |

## Capability Objective

Establish agent-level quality scorecards that combine approved quality measures into meaningful performance views.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define scorecard requirements |
| P04 | Design scorecard model |
| P05 | Configure scorecards |
| P08 | Validate calculations |
| P09 | Obtain business acceptance |
| P12 | Handover scorecard governance |

## Source Implementation Activities

1. Define scorecard objectives.
2. Define scorecard measures.
3. Configure scorecards.
4. Validate scorecard results.
5. Handover scorecard governance.

## Implementation Tasks

### Activity 01 — Define Scorecards

#### L10-10.40-001 — Define Agent Scorecard Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Quality Lead |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define the purpose, audience, measures and use of agent scorecards.

**Dependencies**

- Quality strategy
- Evaluation framework

**Deliverable**

Scorecard requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-10.40-002 — Design Agent Scorecard Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define measures, aggregation, scoring, thresholds and audience-specific views.

**Dependencies**

- L10-10.40-001

**Deliverable**

Scorecard design.

**Acceptance Criteria**

Scorecard model is approved.

### Activity 02 — Configure and Validate

#### L10-10.40-003 — Configure Agent Scorecards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Configure scorecard components and required reporting access.

**Dependencies**

- L10-10.40-002

**Deliverable**

Configured agent scorecards.

**Acceptance Criteria**

Scorecards are available to authorised users.

#### L10-10.40-004 — Validate Agent Scorecard Results

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate scorecard calculations, data inputs, visibility and interpretation.

**Dependencies**

- L10-10.40-003

**Deliverable**

Scorecard validation evidence.

**Acceptance Criteria**

Scorecard results reconcile to approved test scenarios.

### Activity 03 — Operational Handover

#### L10-10.40-005 — Handover Agent Scorecard Governance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Quality Lead |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Transfer scorecard ownership, maintenance and review responsibilities to the operational quality team.

**Dependencies**

- L10-10.40-004

**Deliverable**

Scorecard governance handover.

**Acceptance Criteria**

Operational owner accepts responsibility for ongoing scorecard management.

## Capability-Level Dependencies

- Quality management strategy
- Quality evaluation framework
- Evaluation forms
- Evaluation scoring
- Recording and interaction capabilities
- Identity and access controls
- Analytics and reporting capabilities

## Capability-Level Estimation Considerations

Effort is influenced by:

- number of business units
- number of quality programmes
- number of evaluation forms
- number of questions and scoring rules
- number of recording types
- recording volume
- retention requirements
- compliance complexity
- PCI and sensitive-data requirements
- evaluator populations
- analytics languages and interaction volumes
- dashboard and reporting requirements
- integration requirements
- customer approval cycles
- testing data availability

## Definition of Done

The Section 10 capability catalogue is complete when:

- all required quality capabilities are assessed
- quality and recording requirements are approved
- recording controls are implemented
- recording security and compliance controls are validated
- evaluation framework components are configured
- quality analytics are validated
- dashboards and reporting are operational
- evaluator processes are established
- operational ownership is transferred
- all applicable capability task records are available for project scheduling and estimation