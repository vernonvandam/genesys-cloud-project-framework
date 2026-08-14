# Layer 10 — 2.05.10 Menu Design

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.10 |
| Capability | Menu Design |
| Task Catalogue ID | 05.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Design and configure intuitive IVR menu structures that minimise customer effort and provide clear routing paths.

## Source Implementation Activities

1. Define menu requirements.
2. Design menu hierarchy.
3. Configure menus.
4. Validate navigation.

## Implementation Tasks

### Activity 01 — Define Menu Structure

#### L10-05.10-001 — Define Menu Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define menu options, routing outcomes, language requirements and customer journey expectations.

**Dependencies**

- Customer journey requirements

**Deliverable**

Menu requirements.

**Acceptance Criteria**

Menu structure is approved.

---

#### L10-05.10-002 — Configure Menu Structure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the approved menu hierarchy and routing paths.

**Dependencies**

- L10-05.10-001

**Deliverable**

Configured menu.

**Acceptance Criteria**

Menu options route to approved destinations.

---

#### L10-05.10-003 — Validate Menu Navigation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate valid, invalid and incomplete menu selections.

**Dependencies**

- L10-05.10-002

**Deliverable**

Menu test evidence.

**Acceptance Criteria**

All menu paths operate correctly.