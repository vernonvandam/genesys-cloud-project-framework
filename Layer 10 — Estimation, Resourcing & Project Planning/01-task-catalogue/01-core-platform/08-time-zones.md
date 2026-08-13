# Layer 10 — 2.01.08 Time Zones

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.08 |
| Capability | Time Zones |
| Task Catalogue ID | 01.08 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08 |

## Capability Objective

Establish the time-zone model required for accurate scheduling, routing, reporting, workforce management, and operational configuration.

## Source Implementation Activities

1. Identify time-zone requirements.
2. Design time-zone model.
3. Configure time zones.
4. Validate time-zone behaviour.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.08-001 — Identify Required Time Zones

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Identify all time zones required by locations, sites, users, schedules, routing, reporting, and workforce management.

**Dependencies**

- Location requirements
- Site requirements

**Deliverable**

Time-zone requirements list.

**Acceptance Criteria**

Required time zones are confirmed.

### Activity 02 — Design

#### L10-01.08-002 — Define Time-Zone Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define the standard time-zone configuration and default time zone.

**Dependencies**

- L10-01.08-001

**Deliverable**

Time-zone design.

**Acceptance Criteria**

Time-zone standards are approved.

### Activity 03 — Configure

#### L10-01.08-003 — Configure Time-Zone Settings

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

Configure the required default and supporting time-zone settings.

**Dependencies**

- L10-01.08-002

**Deliverable**

Configured time-zone settings.

**Acceptance Criteria**

Configuration matches approved design.

### Activity 04 — Validate

#### L10-01.08-004 — Validate Time-Zone Behaviour

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

Validate time-zone behaviour across relevant schedules, sites, routing, reporting, and other dependent capabilities.

**Dependencies**

- L10-01.08-003

**Deliverable**

Time-zone validation evidence.

**Acceptance Criteria**

Time-zone behaviour is correct across defined use cases.

## Estimation Considerations

Drivers include:

- number of time zones
- geographic spread
- daylight-saving requirements
- number of dependent schedules
- number of environments

## Definition of Done

Required time zones are defined, configured, validated, and documented.