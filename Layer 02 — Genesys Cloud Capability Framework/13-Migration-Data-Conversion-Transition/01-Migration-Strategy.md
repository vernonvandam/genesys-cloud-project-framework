# Layer 2.13.01 — Migration Strategy

## Capability Definition

The Migration Strategy defines the overall approach for moving the existing contact centre platform, configuration, users, data, integrations and operational dependencies into Genesys Cloud.

---

# 1. Scope

- Migration objectives and outcomes
- Migration scope and exclusions
- Migration waves
- Migration sequencing
- Migration dependencies
- Migration risks and assumptions
- Data migration strategy
- Configuration migration strategy
- Cutover strategy
- Coexistence strategy
- Rollback strategy
- Legacy transition strategy

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify all migration objects and source platforms.
- Determine what must be migrated, recreated, transformed or retired.
- Identify source-system owners and SMEs.
- Determine migration constraints and business blackout periods.
- Identify historical data and recording requirements.
- Identify coexistence requirements.
- Identify dependencies on telephony, integrations, CRM, WFM, reporting and security.
- Identify migration waves and business priorities.
- Determine customer acceptance requirements.

---

# 4. Design Activities

- Define migration principles.
- Define migration scope boundaries.
- Define migration waves.
- Define sequencing and dependencies.
- Define migration methods.
- Define data conversion principles.
- Define configuration migration approach.
- Define cutover and rollback strategy.
- Define coexistence approach where required.
- Define migration validation and reconciliation approach.
- Define legacy transition strategy.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.13.01-T01 | Review current-state migration scope | Phase 2 | Migration Lead | 4h |
| 2.13.01-T02 | Identify migration objects and source systems | Phase 2 | Migration Lead | 4h |
| 2.13.01-T03 | Define migration principles and scope boundaries | Phase 3 | Migration Lead | 4h |
| 2.13.01-T04 | Define migration waves and sequencing | Phase 3 | Migration Lead | 6h |
| 2.13.01-T05 | Define cutover, rollback and coexistence strategy | Phase 4 | Migration Lead | 6h |
| 2.13.01-T06 | Document and baseline Migration Strategy | Phase 4 | Migration Lead | 4h |
| 2.13.01-T07 | Obtain customer approval | Phase 4 | Project Manager | 2h |

---

# 6. Dependencies

Prerequisites:

- Discovery
- Current-state assessment
- Requirements
- Solution architecture
- Source inventory

Downstream:

- Migration Architecture
- Migration Mapping
- Migration Tooling
- Mock Migration
- Migration Rehearsal
- Cutover Migration
- Legacy Transition

---

# 7. Layer 1 Mapping

Primary:

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 7 — Integration & Data Migration
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Project Manager
- Migration Lead
- Solution Architect
- Technical Architect
- Data Architect
- Genesys Cloud Architect
- Business SME
- Data Owner

---

# 9. Customer Responsibilities

- Confirm migration objectives.
- Identify source systems.
- Identify data owners.
- Confirm migration scope.
- Approve migration waves.
- Approve cutover and rollback strategy.

---

# 10. Testing

Validate that all migration scope, sequencing, dependencies, validation and rollback requirements are represented in the project test and deployment strategy.

---

# 11. Deliverables

- Migration Strategy
- Migration Scope
- Migration Wave Plan
- Migration Dependency Register
- Cutover Strategy
- Rollback Strategy
- Legacy Transition Strategy

---

# 12. Effort Drivers

Source complexity, number of migration objects, number of waves, data volume, integrations, coexistence, historical data and cutover complexity.

---

# 13. Acceptance Criteria

- Migration scope is documented.
- Migration approach is approved.
- Migration waves are defined.
- Dependencies are identified.
- Cutover and rollback approaches are documented.
- Customer approval is obtained.

---

# 14. Definition of Done

The Migration Strategy is approved, baselined and used as the governing migration framework for the project.