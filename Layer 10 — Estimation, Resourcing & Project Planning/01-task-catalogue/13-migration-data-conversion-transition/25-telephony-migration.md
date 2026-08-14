# Layer 10 — 2.13.25 Telephony Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.25 |
| Capability | Telephony Migration |
| Task Catalogue ID | 13.25 |
| Primary Layer 1 Phases | P04, P06, P08, P10, P11 |

## Capability Objective

Migrate telephony configuration, numbers, sites, routing and carrier dependencies into Genesys Cloud.

## Implementation Tasks

### L10-13.25-001 — Inventory Telephony Assets

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Inventory numbers, carriers, sites, endpoints, trunks and telephony dependencies.

**Dependencies**

- Source inventory
- Voice architecture

**Deliverable**

Telephony migration inventory.

**Acceptance Criteria**

All required telephony assets are accounted for.

### L10-13.25-002 — Implement Telephony Migration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Configure target telephony and execute required number or carrier migration activities.

**Dependencies**

- L10-13.25-001
- Target voice configuration

**Deliverable**

Migrated telephony configuration.

**Acceptance Criteria**

Target telephony is operational.

### L10-13.25-003 — Validate Telephony Migration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Voice / Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Validate inbound, outbound, emergency, caller-ID and routing requirements.

**Dependencies**

- L10-13.25-002

**Deliverable**

Telephony validation report.

**Acceptance Criteria**

Approved telephony scenarios pass.

## Definition of Done

Telephony migration is operational and validated.

---