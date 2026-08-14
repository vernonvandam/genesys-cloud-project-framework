# Layer 10 — 2.05.06 Workflow Automation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.06 |
| Capability | Workflow Automation |
| Task Catalogue ID | 05.06 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Implement Architect-based workflow automation for business processes that require system actions, data retrieval, routing decisions or downstream updates.

## Source Implementation Activities

1. Identify automation opportunities.
2. Design workflow logic.
3. Configure workflow automation.
4. Validate outcomes.

## Implementation Tasks

### Activity 01 — Define Workflow Automation

#### L10-05.06-001 — Identify Workflow Automation Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify business processes suitable for Architect workflow automation and define expected inputs, outputs and outcomes.

**Dependencies**

- Business process discovery

**Deliverable**

Workflow automation requirements.

**Acceptance Criteria**

Automation scope and expected outcomes are approved.

---

#### L10-05.06-002 — Configure Workflow Automation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure the workflow, including decision logic, data dependencies, error handling and downstream actions.

**Dependencies**

- L10-05.06-001
- Required integrations

**Deliverable**

Configured workflow.

**Acceptance Criteria**

Workflow implements approved business logic and failure handling.

---

#### L10-05.06-003 — Validate Workflow Automation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate successful, failed and exception workflow paths.

**Dependencies**

- L10-05.06-002

**Deliverable**

Workflow validation evidence.

**Acceptance Criteria**

All approved workflow scenarios pass.