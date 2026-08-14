# Layer 10 — 2.12.15 Architect Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.15 — Architect Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.15 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Validate Genesys Cloud Architect flows, prompts, schedules, routing decisions, error handling and integrations.

## Source Implementation Activities

- Validate flow configuration.
- Test normal paths.
- Test exception paths.
- Test prompts and schedules.
- Test flow integrations.
- Validate published flow versions.

## Implementation Tasks

### Activity 01 — Validate Flow Configuration

#### L10-12.15-001 — Validate Architect Flow Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Validate flows, versions, dependencies, prompts, schedules and configuration.

**Dependencies**

Architect build.

**Deliverable**

Architect Configuration Validation.

**Acceptance Criteria**

Published flow versions match approved design.

### Activity 02 — Test Normal Paths

#### L10-12.15-002 — Execute Architect Happy Path Tests

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Execute normal customer journeys through Architect flows.

**Dependencies**

L10-12.15-001.

**Deliverable**

Architect Functional Test Results.

**Acceptance Criteria**

Expected flow outcomes are achieved.

### Activity 03 — Test Exceptions

#### L10-12.15-003 — Execute Architect Exception Tests

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Test invalid inputs, unavailable services, closed hours, errors and alternate routing.

**Dependencies**

L10-12.15-002.

**Deliverable**

Architect Exception Test Results.

**Acceptance Criteria**

Defined exception scenarios behave correctly.

## Capability-Level Dependencies

- Architect
- ACD & Routing
- Voice & Telephony
- Integrations

## Capability-Level Estimation Considerations

Flow count, complexity, menus, integrations, schedules and exception paths drive effort.

## Definition of Done

All critical Architect flows pass functional and exception testing.

---