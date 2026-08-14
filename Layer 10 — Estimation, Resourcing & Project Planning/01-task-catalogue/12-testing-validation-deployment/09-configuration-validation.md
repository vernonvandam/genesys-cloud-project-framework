# Layer 10 — 2.12.09 Configuration Validation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.09 — Configuration Validation |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.09 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Validate that configured Genesys Cloud capabilities match approved design and requirements before formal end-to-end and acceptance testing.

## Source Implementation Activities

- Validate configuration against design.
- Identify configuration deviations.
- Correct configuration defects.
- Revalidate corrected configuration.

## Implementation Tasks

### Activity 01 — Establish Configuration Baseline

#### L10-12.09-001 — Compare Configuration to Approved Design

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Compare deployed configuration against approved solution design.

**Dependencies**

Solution design and build completion.

**Deliverable**

Configuration Validation Record.

**Acceptance Criteria**

Material deviations are identified.

### Activity 02 — Remediate Deviations

#### L10-12.09-002 — Correct Configuration Deviations

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Correct configuration deviations identified during baseline validation.

**Dependencies**

L10-12.09-001.

**Deliverable**

Corrected Configuration.

**Acceptance Criteria**

Approved configuration baseline is implemented.

### Activity 03 — Revalidate

#### L10-12.09-003 — Revalidate Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Confirm configuration remains aligned with approved design following remediation.

**Dependencies**

L10-12.09-002.

**Deliverable**

Configuration Validation Sign-Off.

**Acceptance Criteria**

No unresolved critical configuration deviations remain.

## Capability-Level Dependencies

- Solution Architecture
- Configuration and Development
- Core Platform
- Identity & Access

## Capability-Level Estimation Considerations

Number of configured objects, environments and deviations drives effort.

## Definition of Done

Configuration matches approved design and all critical deviations are resolved.

---