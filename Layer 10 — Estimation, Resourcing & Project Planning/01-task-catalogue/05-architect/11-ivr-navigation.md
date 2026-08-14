# Layer 10 — 2.05.11 IVR Navigation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.11 |
| Capability | IVR Navigation |
| Task Catalogue ID | 05.11 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Implement IVR navigation supporting clear, efficient and accessible customer interaction paths.

## Source Implementation Activities

1. Define navigation model.
2. Configure navigation.
3. Validate customer paths.

## Implementation Tasks

### Activity 01 — Design IVR Navigation

#### L10-05.11-001 — Define IVR Navigation Requirements

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

Define IVR navigation, entry points, prompts, selections, fallback and transfer paths.

**Dependencies**

- Menu requirements

**Deliverable**

IVR navigation design.

**Acceptance Criteria**

Navigation requirements are approved.

---

#### L10-05.11-002 — Configure IVR Navigation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Implement the approved IVR navigation structure.

**Dependencies**

- L10-05.11-001

**Deliverable**

Configured IVR navigation.

**Acceptance Criteria**

Navigation paths match approved design.

---

#### L10-05.11-003 — Validate IVR Navigation

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

Validate navigation, fallback, timeout, invalid input and transfer scenarios.

**Dependencies**

- L10-05.11-002

**Deliverable**

IVR navigation test evidence.

**Acceptance Criteria**

All defined navigation scenarios pass.