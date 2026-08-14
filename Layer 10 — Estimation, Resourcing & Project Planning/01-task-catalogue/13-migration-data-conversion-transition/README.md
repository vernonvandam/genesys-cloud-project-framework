# FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/13-migration-data-conversion-transition/README.md

# 13 — Migration, Data Conversion & Transition Task Catalogue

## Layer 10 — Estimation, Resourcing & Project Planning

## 1. Purpose

This directory contains the Layer 10 implementation task catalogue for the Migration, Data Conversion & Transition capability domain.

The catalogue decomposes the Layer 2 migration capabilities and implementation activities into discrete, estimable, assignable, dependency-aware, and schedulable implementation tasks.

The catalogue covers:

- migration strategy and governance
- source-system discovery
- data profiling and classification
- data ownership and retention
- migration architecture
- mapping and transformation
- data extraction, staging and loading
- Genesys Cloud configuration migration
- user, queue, skill, routing and Architect migration
- telephony and digital migration
- CRM and integration migration
- historical interaction, recording, quality, WFM and reporting data
- migration tooling and automation
- mock migrations and rehearsals
- cutover and delta migration
- coexistence
- rollback and recovery
- reconciliation and validation
- hypercare
- operational handover
- legacy transition
- archival and decommissioning
- migration closure

---

# 2. Domain Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Task Catalogue Domain | 13 — Migration, Data Conversion & Transition |
| Layer 2 Domain | 13 — Migration, Data Conversion & Transition |
| Domain Type | Migration / Transition |
| Capability Count | 53 |
| Task Catalogue Prefix | L10-13 |
| Primary Delivery Roles | Migration Lead, Solution Architect, Data Architect, Genesys Cloud Architect, Genesys Cloud Engineer |
| Primary Customer Roles | Data Owner, Business SME, Customer Technical Lead, Customer Project Manager |
| Primary Environments | DESIGN, DEV, TEST, UAT, PROD, MULTI |
| Primary Layer 1 Phases | P01–P12 |
| Task Catalogue Status | Baseline Task Catalogue |

---

# 3. Relationship to Layer 2

The authoritative capability definitions are maintained within:

```text
Layer 2
└── 13 — Migration, Data Conversion & Transition
```

Layer 10 does not redefine the capability catalogue.

Instead, it takes the Layer 2 implementation activities and decomposes them into individual implementation tasks.

```text
Layer 2 Capability
        │
        ├── Implementation Activity
        │          │
        │          ▼
        │     Layer 10 Task
        │          │
        │          ├── Task
        │          ├── Task
        │          └── Task
        │
        ▼
Project Schedule
        │
        ▼
Effort Estimate
        │
        ▼
Resource Plan
```

---

# 4. Capability Catalogue

| Capability ID | Capability | Task Catalogue File | Classification |
|---|---|---|---|
| 2.13.01 | Migration Strategy | `01-migration-strategy.md` | REQUIRED |
| 2.13.02 | Migration Governance | `02-migration-governance.md` | REQUIRED |
| 2.13.03 | Migration Scope & Assessment | `03-migration-scope-assessment.md` | REQUIRED |
| 2.13.04 | Source System Inventory | `04-source-system-inventory.md` | REQUIRED |
| 2.13.05 | Data Discovery | `05-data-discovery.md` | REQUIRED |
| 2.13.06 | Data Profiling | `06-data-profiling.md` | REQUIRED |
| 2.13.07 | Data Classification | `07-data-classification.md` | REQUIRED |
| 2.13.08 | Data Ownership | `08-data-ownership.md` | REQUIRED |
| 2.13.09 | Data Retention | `09-data-retention.md` | REQUIRED |
| 2.13.10 | Privacy & Compliance | `10-privacy-compliance.md` | REQUIRED |
| 2.13.11 | Migration Architecture | `11-migration-architecture.md` | REQUIRED |
| 2.13.12 | Migration Approach | `12-migration-approach.md` | REQUIRED |
| 2.13.13 | Migration Mapping | `13-migration-mapping.md` | REQUIRED |
| 2.13.14 | Data Transformation | `14-data-transformation.md` | CONDITIONAL |
| 2.13.15 | Data Cleansing | `15-data-cleansing.md` | REQUIRED |
| 2.13.16 | Data Extraction | `16-data-extraction.md` | REQUIRED |
| 2.13.17 | Data Staging | `17-data-staging.md` | CONDITIONAL |
| 2.13.18 | Data Loading | `18-data-loading.md` | REQUIRED |
| 2.13.19 | Configuration Migration | `19-configuration-migration.md` | REQUIRED |
| 2.13.20 | User Migration | `20-user-migration.md` | REQUIRED |
| 2.13.21 | Queue Migration | `21-queue-migration.md` | REQUIRED |
| 2.13.22 | Skill & Language Migration | `22-skill-language-migration.md` | REQUIRED |
| 2.13.23 | Routing Migration | `23-routing-migration.md` | REQUIRED |
| 2.13.24 | Architect Migration | `24-architect-migration.md` | REQUIRED |
| 2.13.25 | Telephony Migration | `25-telephony-migration.md` | REQUIRED |
| 2.13.26 | Digital Migration | `26-digital-migration.md` | CONDITIONAL |
| 2.13.27 | CRM / Customer Data Migration | `27-crm-customer-data-migration.md` | CONDITIONAL |
| 2.13.28 | Integration Migration | `28-integration-migration.md` | REQUIRED |
| 2.13.29 | API Migration | `29-api-migration.md` | CONDITIONAL |
| 2.13.30 | Historical Interaction Data | `30-historical-interaction-data.md` | CONDITIONAL |
| 2.13.31 | Recording Migration | `31-recording-migration.md` | CONDITIONAL |
| 2.13.32 | Quality Data Migration | `32-quality-data-migration.md` | CONDITIONAL |
| 2.13.33 | WFM Data Migration | `33-wfm-data-migration.md` | CONDITIONAL |
| 2.13.34 | Reporting Data Migration | `34-reporting-data-migration.md` | CONDITIONAL |
| 2.13.35 | Migration Tooling | `35-migration-tooling.md` | REQUIRED |
| 2.13.36 | Migration Automation | `36-migration-automation.md` | CONDITIONAL |
| 2.13.37 | Mock Migration | `37-mock-migration.md` | REQUIRED |
| 2.13.38 | Migration Rehearsal | `38-migration-rehearsal.md` | REQUIRED |
| 2.13.39 | Cutover Migration | `39-cutover-migration.md` | REQUIRED |
| 2.13.40 | Delta Migration | `40-delta-migration.md` | CONDITIONAL |
| 2.13.41 | Data Freeze | `41-data-freeze.md` | CONDITIONAL |
| 2.13.42 | Coexistence | `42-coexistence.md` | CONDITIONAL |
| 2.13.43 | Transition Management | `43-transition-management.md` | REQUIRED |
| 2.13.44 | Rollback & Recovery | `44-rollback-recovery.md` | REQUIRED |
| 2.13.45 | Migration Validation | `45-migration-validation.md` | REQUIRED |
| 2.13.46 | Data Reconciliation | `46-data-reconciliation.md` | REQUIRED |
| 2.13.47 | Post-Migration Validation | `47-post-migration-validation.md` | REQUIRED |
| 2.13.48 | Hypercare | `48-hypercare.md` | REQUIRED |
| 2.13.49 | Operational Handover | `49-operational-handover.md` | REQUIRED |
| 2.13.50 | Legacy Platform Transition | `50-legacy-platform-transition.md` | REQUIRED |
| 2.13.51 | Data Archival | `51-data-archival.md` | CONDITIONAL |
| 2.13.52 | Legacy Decommissioning | `52-legacy-decommissioning.md` | CONDITIONAL |
| 2.13.53 | Migration Closure | `53-migration-closure.md` | REQUIRED |

---

# 5. Task ID Convention

Migration tasks use:

```text
L10-13.CC-TTT
```

Where:

| Component | Meaning |
|---|---|
| `L10` | Layer 10 |
| `13` | Migration domain |
| `CC` | Capability number |
| `TTT` | Sequential task number |

Examples:

```text
L10-13.01-001
L10-13.01-002
L10-13.01-003
L10-13.13-001
L10-13.53-001
```

---

# 6. Standard Task Attributes

Every implementation task must contain:

| Attribute | Requirement |
|---|---|
| Task Type | REQUIRED / CONDITIONAL / VALIDATION |
| Layer 1 Phase | P01–P12 |
| Primary Role | Delivery role |
| Customer Responsibility | YES / NO / JOINT |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / AUTOMATED / HYBRID |
| Baseline Effort | Initial estimate |
| Critical Path | YES / NO / CONDITIONAL |

Every task must also contain:

- Description
- Dependencies
- Deliverable
- Acceptance Criteria

---

# 7. Layer 1 Mapping

Migration activities span the full deployment lifecycle.

| Layer 1 Phase | Migration Application |
|---|---|
| P01 | Establish migration ownership, scope and governance |
| P02 | Discover source systems, data and current-state dependencies |
| P03 | Define migration requirements and acceptance criteria |
| P04 | Design migration architecture, mapping and transition approach |
| P05 | Establish migration environments, access and tooling |
| P06 | Build migration configuration, transformation and tooling |
| P07 | Execute migration integration and data enablement activities |
| P08 | Execute mock migrations, validation, reconciliation and defect resolution |
| P09 | Establish operational transition and migration readiness |
| P10 | Prepare production cutover, freeze, delta and rollback |
| P11 | Execute migration, validate production and manage hypercare |
| P12 | Complete handover, legacy transition, archival and migration closure |

The exact Layer 1 phase must be recorded on each task.

---

# 8. Migration Task Lifecycle

```text
Strategy
   ↓
Governance
   ↓
Scope & Assessment
   ↓
Source Discovery
   ↓
Data Profiling
   ↓
Classification & Ownership
   ↓
Migration Architecture
   ↓
Mapping
   ↓
Transformation / Cleansing
   ↓
Extraction
   ↓
Staging / Loading
   ↓
Mock Migration
   ↓
Migration Rehearsal
   ↓
Cutover Preparation
   ↓
Production Migration
   ↓
Validation
   ↓
Reconciliation
   ↓
Transition
   ↓
Hypercare
   ↓
Legacy Transition
   ↓
Closure
```

---

# 9. Domain Dependencies

Migration may depend on:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD & Routing
- Architect
- Digital
- WFM & Employee Engagement
- Data, Integrations & APIs
- Analytics & Reporting
- Quality Management
- Security, Compliance & Governance
- Testing, Validation & Deployment
- Operations, Support & Service Management

---

# 10. Estimation Considerations

Migration effort is influenced by:

- number of source platforms
- number of source systems
- data volume
- data quality
- number of users
- number of queues
- number of skills
- number of Architect flows
- number of telephone numbers
- number of integrations
- number of APIs
- historical data volume
- recording volume
- quality data volume
- WFM history
- reporting history
- number of migration waves
- coexistence duration
- cutover complexity
- data transformation complexity
- automation requirements
- customer availability
- regulatory requirements
- reconciliation requirements
- rollback complexity
- legacy decommissioning requirements

The estimation model should distinguish:

```text
Fixed Effort
+
Volume Effort
+
Transformation Effort
+
Migration-Wave Effort
+
Cutover Effort
+
Validation / Reconciliation Effort
+
Complexity Adjustment
```

---

# 11. Definition of Done

Section 13 is complete when:

- all 53 capabilities have task files
- every capability maps to Layer 1
- implementation activities are decomposed into tasks
- task dependencies are documented
- customer responsibilities are identified
- delivery roles are assigned
- environments are identified
- automation approach is identified
- baseline effort can be estimated
- migration deliverables are identified
- acceptance criteria are defined
- critical-path tasks are identified
- migration validation is covered
- reconciliation is covered
- rollback is covered
- cutover is covered
- operational handover is covered
- legacy transition is covered
- the catalogue can be converted into a project schedule and estimation model

---

# 12. Capability File Structure

Each capability follows the Layer 10 Core Platform pattern:

```text
Capability Reference
        ↓
Capability Objective
        ↓
Layer 1 Mapping
        ↓
Source Implementation Activities
        ↓
Implementation Tasks
        ↓
Capability-Level Dependencies
        ↓
Capability-Level Estimation Considerations
        ↓
Definition of Done
```

---