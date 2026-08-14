<!-- FILE: 27-fax-special-telephony-services.md -->

# Layer 10 — 2.03.27 Fax & Special Telephony Services

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.27 |
| Capability | Fax & Special Telephony Services |
| Task Catalogue ID | 03.27 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P10 |

## Capability Objective

Identify, design, implement and validate fax and other special telephony services required by the customer.

## Source Implementation Activities

1. Discover special services.
2. Define requirements.
3. Determine supported architecture.
4. Configure.
5. Test.

## Implementation Tasks

#### L10-03.27-001 — Inventory Special Telephony Services

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify fax and other special telephony services requiring migration or replacement.

**Dependencies**

- Telephony discovery

**Deliverable**

Special-service inventory.

**Acceptance Criteria**

Services are documented.

#### L10-03.27-002 — Define Special-Service Strategy

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Determine target architecture and supported approach.

**Dependencies**

- L10-03.27-001

**Deliverable**

Special-service design.

**Acceptance Criteria**

Approach approved.

#### L10-03.27-003 — Implement Special Telephony Services

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h/service |
| Critical Path | CONDITIONAL |

**Description**

Implement the approved service architecture.

**Dependencies**

- L10-03.27-002

**Deliverable**

Configured service.

**Acceptance Criteria**

Service operates as designed.

#### L10-03.27-004 — Test Special Services

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h/service |
| Critical Path | CONDITIONAL |

**Description**

Validate service operation and relevant edge cases.

**Dependencies**

- L10-03.27-003

**Deliverable**

Test evidence.

**Acceptance Criteria**

All required service scenarios pass.

## Capability-Level Dependencies

- Carrier
- Number strategy
- Integration requirements
- Compliance

## Capability-Level Estimation Considerations

Special services must be estimated individually because implementation varies substantially.

## Definition of Done

All in-scope special telephony services are implemented and validated.