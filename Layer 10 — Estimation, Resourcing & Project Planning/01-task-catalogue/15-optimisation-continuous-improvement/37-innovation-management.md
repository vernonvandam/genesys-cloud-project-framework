# Layer 10 — 2.15.37 Innovation Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.37 |
| Capability | Innovation Management |
| Task Catalogue ID | 15.37 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P09 |

## Capability Objective

Provide a controlled mechanism for identifying, evaluating and progressing innovative ideas that may improve customer, agent or operational outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify innovation opportunities |
| P03 | Assess value and feasibility |
| P04 | Define innovation approach |
| P08 | Validate experiments |
| P09 | Operationalise successful innovation |

## Source Implementation Activities

1. Capture innovation ideas.
2. Assess feasibility and value.
3. Prioritise innovation opportunities.
4. Experiment safely.
5. Evaluate results.

## Implementation Tasks

### L10-15.37-001 — Establish Innovation Intake

| Attribute | Value |
|---|---|
| Task Type | OPTIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Product Owner |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Establish the mechanism for capturing innovation ideas and opportunities.

**Dependencies**

- Innovation governance

**Deliverable**

Innovation intake process.

**Acceptance Criteria**

Ideas can be submitted and tracked.

### L10-15.37-002 — Assess Innovation Opportunity

| Attribute | Value |
|---|---|
| Task Type | OPTIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess value, feasibility, risk, cost and strategic alignment.

**Dependencies**

- L10-15.37-001

**Deliverable**

Innovation assessment.

**Acceptance Criteria**

Opportunity is assessed and dispositioned.

### L10-15.37-003 — Execute Innovation Experiment

| Attribute | Value |
|---|---|
| Task Type | OPTIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Execute a controlled experiment where approved.

**Dependencies**

- L10-15.37-002

**Deliverable**

Innovation experiment.

**Acceptance Criteria**

Experiment produces documented results.

### L10-15.37-004 — Evaluate Innovation Outcome

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Product Owner |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Evaluate experiment results and determine whether to progress, modify or terminate the idea.

**Dependencies**

- L10-15.37-003

**Deliverable**

Innovation decision.

**Acceptance Criteria**

Outcome and next action are approved.