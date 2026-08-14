# Layer 10 — 2.15.07 Customer Experience Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.07 |
| Capability | Customer Experience Optimisation |
| Task Catalogue ID | 15.07 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P11 |

## Capability Objective

Identify and implement improvements that reduce customer effort and improve customer outcomes across Genesys Cloud journeys and channels.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Analyse customer experience baseline |
| P03 | Define experience improvement objectives |
| P04 | Design target customer journeys |
| P08 | Validate experience changes |
| P11 | Validate production customer outcomes |

## Source Implementation Activities

1. Assess customer journey performance.
2. Identify customer pain points.
3. Define improvement opportunities.
4. Design experience improvements.
5. Validate customer outcomes.

## Implementation Tasks

### L10-15.07-001 — Assess Customer Experience Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess customer experience measures, journeys, transfers, abandonment, containment, satisfaction and customer effort.

**Dependencies**

- Analytics availability
- Customer journey data

**Deliverable**

Customer experience baseline.

**Acceptance Criteria**

Current experience performance is documented.

### L10-15.07-002 — Identify Customer Experience Opportunities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify measurable opportunities to reduce customer effort or improve outcomes.

**Dependencies**

- L10-15.07-001

**Deliverable**

CX optimisation opportunity register.

**Acceptance Criteria**

Opportunities are documented and prioritised.

### L10-15.07-003 — Design Customer Experience Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Design the target-state customer journey and supporting platform changes.

**Dependencies**

- L10-15.07-002

**Deliverable**

CX improvement design.

**Acceptance Criteria**

Target experience is documented and approved.

### L10-15.07-004 — Validate Customer Experience Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Measure customer outcomes following implementation.

**Dependencies**

- L10-15.07-003
- Production deployment

**Deliverable**

CX outcome validation.

**Acceptance Criteria**

Expected customer experience outcomes are measured.