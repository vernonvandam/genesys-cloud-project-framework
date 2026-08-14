<!-- FILE: 22-emergency-services-e911.md -->

# Layer 10 — 2.03.22 Emergency Services / E911

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.22 |
| Capability | Emergency Services / E911 |
| Task Catalogue ID | 03.22 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09, P10 |

## Capability Objective

Define and validate emergency calling requirements appropriate to the deployment geography and regulatory environment.

## Source Implementation Activities

1. Determine emergency calling requirements.
2. Assess geographic/regulatory obligations.
3. Design emergency routing.
4. Configure.
5. Test.
6. Document emergency procedures.

## Implementation Tasks

#### L10-03.22-001 — Assess Emergency Calling Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Determine applicable emergency-service requirements for each deployment geography.

**Dependencies**

- Geography
- Compliance requirements

**Deliverable**

Emergency calling assessment.

**Acceptance Criteria**

Requirements and obligations are documented.

#### L10-03.22-002 — Design Emergency Calling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Design emergency routing, location information and operational procedures.

**Dependencies**

- L10-03.22-001

**Deliverable**

Emergency calling design.

**Acceptance Criteria**

Design approved.

#### L10-03.22-003 — Configure Emergency Calling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure supported emergency calling functionality.

**Dependencies**

- L10-03.22-002

**Deliverable**

Emergency configuration.

**Acceptance Criteria**

Configuration matches approved design.

#### L10-03.22-004 — Validate Emergency Calling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute approved emergency-call validation using safe and authorised test procedures.

**Dependencies**

- L10-03.22-003

**Deliverable**

Emergency calling validation evidence.

**Acceptance Criteria**

Emergency calling requirements are demonstrated.

## Capability-Level Dependencies

- Geography
- Carrier
- Compliance
- Site/location strategy

## Capability-Level Estimation Considerations

Regulatory requirements vary significantly by geography.

## Definition of Done

Emergency calling is implemented where required, tested appropriately and operationally documented.