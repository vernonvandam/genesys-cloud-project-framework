# Layer 10 — 2.03.13 Dial Plans & Number Normalisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.13 |
| Capability | Dial Plans & Number Normalisation |
| Task Catalogue ID | 03.13 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define and implement consistent telephone-number normalisation and dial-plan behaviour.

## Source Implementation Activities

1. Discover existing dial plans.
2. Define normalisation standards.
3. Design dial rules.
4. Configure.
5. Test.

## Implementation Tasks

### Activity 01 — Discovery

#### L10-03.13-001 — Inventory Existing Dial Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document existing local, national, international, extension and service-number dialling behaviour.

**Dependencies**

- Voice discovery

**Deliverable**

Dial-rule inventory.

**Acceptance Criteria**

Relevant dial rules are documented.

### Activity 02 — Design

#### L10-03.13-002 — Define Number Normalisation Standard

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

Define target number formats and normalisation rules.

**Dependencies**

- L10-03.13-001

**Deliverable**

Normalisation standard.

**Acceptance Criteria**

Standard is approved.

### Activity 03 — Configure

#### L10-03.13-003 — Configure Dial Plans

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Implement required dial-plan and number-normalisation configuration.

**Dependencies**

- L10-03.13-002

**Deliverable**

Configured dial plans.

**Acceptance Criteria**

Configuration conforms to design.

### Activity 04 — Validate

#### L10-03.13-004 — Test Number Normalisation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test all supported number formats and edge cases.

**Dependencies**

- L10-03.13-003

**Deliverable**

Normalisation test results.

**Acceptance Criteria**

All approved formats produce expected results.

## Capability-Level Dependencies

- Number strategy
- Caller ID
- Outbound routing
- Inbound routing

## Capability-Level Estimation Considerations

Complexity increases with countries, numbering schemes and legacy dialling conventions.

## Definition of Done

Dial plans and normalisation rules are configured, tested and documented.