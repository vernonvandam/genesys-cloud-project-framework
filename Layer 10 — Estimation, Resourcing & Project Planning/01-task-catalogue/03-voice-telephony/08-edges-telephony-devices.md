<!-- FILE: 08-edges-telephony-devices.md -->

# Layer 10 — 2.03.08 Edges & Telephony Devices

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.08 |
| Capability | Edges & Telephony Devices |
| Task Catalogue ID | 03.08 |
| Primary Layer 1 Phases | P02, P04, P05, P06, P08, P09, P12 |

## Capability Objective

Design, deploy, configure and validate Edges and associated telephony devices where the selected architecture requires them.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess existing Edge/device estate |
| P04 | Design Edge/device architecture |
| P05 | Prepare infrastructure |
| P06 | Configure devices |
| P08 | Test |
| P09 | Operational readiness |
| P12 | Handover |

## Source Implementation Activities

1. Inventory Edges and devices.
2. Define requirements.
3. Design architecture.
4. Provision and configure.
5. Validate.
6. Document.

## Implementation Tasks

### Activity 01 — Inventory

#### L10-03.08-001 — Inventory Existing Edges and Devices

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Inventory existing Edge appliances, phones and associated devices.

**Dependencies**

- Current-state discovery

**Deliverable**

Device inventory.

**Acceptance Criteria**

Relevant device estate is documented.

### Activity 02 — Design

#### L10-03.08-002 — Define Edge and Device Architecture

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Define Edge placement, device types, connectivity and resilience.

**Dependencies**

- L10-03.08-001

**Deliverable**

Edge/device design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Build

#### L10-03.08-003 — Provision and Configure Edges

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h/Edge |
| Critical Path | CONDITIONAL |

**Description**

Provision and configure required Edge infrastructure.

**Dependencies**

- L10-03.08-002
- Network readiness

**Deliverable**

Configured Edges.

**Acceptance Criteria**

Edges are online and healthy.

### Activity 04 — Validate

#### L10-03.08-004 — Validate Telephony Devices

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h/device |
| Critical Path | CONDITIONAL |

**Description**

Validate device registration, calling, media and failure behaviour.

**Dependencies**

- L10-03.08-003

**Deliverable**

Device validation results.

**Acceptance Criteria**

Devices meet approved test criteria.

## Capability-Level Dependencies

- BYOC Premises
- Sites
- Network
- Device standards

## Capability-Level Estimation Considerations

Estimate per Edge and device quantity.

## Definition of Done

All required Edges and devices are configured, validated and documented.