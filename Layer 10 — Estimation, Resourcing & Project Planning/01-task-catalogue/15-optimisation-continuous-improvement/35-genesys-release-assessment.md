# Layer 10 — 2.15.35 Genesys Release Assessment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.35 |
| Capability | Genesys Release Assessment |
| Task Catalogue ID | 15.35 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P09, P12 |

## Capability Objective

Assess Genesys Cloud platform releases for business value, risk, impact, required action and opportunities.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Review release information |
| P03 | Assess business impact |
| P04 | Assess technical impact |
| P08 | Validate affected capabilities |
| P09 | Operationalise release changes |
| P12 | Maintain release governance |

## Source Implementation Activities

1. Review release information.
2. Identify affected customer capabilities.
3. Assess business and technical impact.
4. Define actions.
5. Communicate and govern changes.

## Implementation Tasks

### L10-15.35-001 — Review Genesys Release Information

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Review applicable Genesys Cloud release information and identify relevant changes.

**Dependencies**

- Current platform capability inventory

**Deliverable**

Release assessment input.

**Acceptance Criteria**

Relevant release changes are identified.

### L10-15.35-002 — Assess Customer Impact

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess impact to configuration, operations, integrations, security, users and business processes.

**Dependencies**

- L10-15.35-001

**Deliverable**

Release impact assessment.

**Acceptance Criteria**

Impacts and required actions are documented.

### L10-15.35-003 — Define Release Actions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define required remediation, adoption, testing, communication or configuration changes.

**Dependencies**

- L10-15.35-002

**Deliverable**

Release action plan.

**Acceptance Criteria**

Actions have owners and priorities.

### L10-15.35-004 — Validate Release Impact

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate impacted capabilities following the release.

**Dependencies**

- L10-15.35-003

**Deliverable**

Release validation evidence.

**Acceptance Criteria**

Impacted functionality remains acceptable.