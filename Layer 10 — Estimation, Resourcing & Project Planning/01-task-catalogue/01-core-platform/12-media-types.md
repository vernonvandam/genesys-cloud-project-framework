# Layer 10 — 2.01.12 Media Types

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.12 |
| Capability | Media Types |
| Task Catalogue ID | 01.12 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define the media types in scope for the Genesys Cloud deployment and establish the foundation required for voice, digital, messaging, callback, email, and other supported interaction models.

## Source Implementation Activities

1. Identify media requirements.
2. Confirm channel scope.
3. Design media-type strategy.
4. Configure required media capabilities.
5. Validate media availability.
6. Document media scope.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.12-001 — Identify Required Media Types

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify all interaction media types required by the solution.

**Dependencies**

- Customer channel strategy

**Deliverable**

Media-type requirements.

**Acceptance Criteria**

Required media types are confirmed.

### Activity 02 — Design

#### L10-01.12-002 — Define Media-Type Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define how each media type will be used and identify dependencies on ACD, Architect, digital, recording, analytics, and integrations.

**Dependencies**

- L10-01.12-001

**Deliverable**

Media strategy.

**Acceptance Criteria**

Media strategy is approved.

### Activity 03 — Configure

#### L10-01.12-003 — Configure Media-Type Foundation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Establish required media-type configuration and supporting platform settings.

**Dependencies**

- L10-01.12-002

**Deliverable**

Media-type configuration.

**Acceptance Criteria**

Required media types are available to dependent configuration.

### Activity 04 — Validate

#### L10-01.12-004 — Validate Media-Type Availability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that required media types are available and operate correctly within the target solution.

**Dependencies**

- L10-01.12-003

**Deliverable**

Media validation evidence.

**Acceptance Criteria**

Required media types pass defined validation scenarios.

## Estimation Considerations

Drivers include:

- number of media types
- channel complexity
- digital dependencies
- recording requirements
- integration requirements
- testing complexity

## Definition of Done

Required media types are confirmed, configured, validated, and available to dependent capabilities.