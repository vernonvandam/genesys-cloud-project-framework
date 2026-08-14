# Layer 10 — 2.13.13 Migration Mapping

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.13 |
| Capability | Migration Mapping |
| Task Catalogue ID | 13.13 |
| Primary Layer 1 Phases | P03, P04, P06 |

## Capability Objective

Define source-to-target mappings for migration data and configuration.

## Source Implementation Activities

1. Identify source fields and objects.
2. Map source to target.
3. Obtain mapping approval.

## Implementation Tasks

### L10-13.13-001 — Define Source-to-Target Mapping

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define source-to-target mappings for each migration object.

**Dependencies**

- Data discovery
- Target architecture

**Deliverable**

Migration mapping specification.

**Acceptance Criteria**

Required source fields and target destinations are mapped.

### L10-13.13-002 — Define Mapping Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define defaulting, lookup, conversion, exclusion and exception rules.

**Dependencies**

- L10-13.13-001

**Deliverable**

Mapping rule specification.

**Acceptance Criteria**

Transformation and exception rules are documented.

### L10-13.13-003 — Approve Migration Mapping

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Owner |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Obtain business and technical approval for mappings.

**Dependencies**

- L10-13.13-002

**Deliverable**

Approved migration mapping.

**Acceptance Criteria**

All material mappings are approved.

## Definition of Done

Source-to-target mappings and conversion rules are approved.

---
