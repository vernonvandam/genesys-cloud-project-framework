# Layer 2.13 — Migration, Data Conversion & Transition

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 13 — Migration, Data Conversion & Transition  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete migration, data conversion, transition, coexistence, cutover, reconciliation, archival and decommissioning capabilities required to move a contact centre solution, its supporting data and operational processes into Genesys Cloud.

---

# 1. Purpose

Migration must be treated as a controlled transformation rather than a simple data movement exercise.

The domain covers:

- Source discovery
- Data discovery
- Data quality
- Data classification
- Data ownership
- Data transformation
- Configuration migration
- User migration
- Telephony migration
- Routing migration
- Architect migration
- Digital migration
- Integration migration
- Historical data
- Recordings
- Quality data
- WFM data
- Reporting data
- Migration tooling
- Mock migrations
- Rehearsals
- Cutover
- Coexistence
- Reconciliation
- Rollback
- Hypercare
- Legacy transition
- Archival
- Decommissioning

---

# 2. Capability Catalogue

| ID | Capability | Default Classification |
|---|---|---|
| 2.13.01 | Migration Strategy | Required |
| 2.13.02 | Migration Governance | Required |
| 2.13.03 | Migration Scope & Assessment | Required |
| 2.13.04 | Source System Inventory | Required |
| 2.13.05 | Data Discovery | Required |
| 2.13.06 | Data Profiling | Required |
| 2.13.07 | Data Classification | Required |
| 2.13.08 | Data Ownership | Required |
| 2.13.09 | Data Retention | Required |
| 2.13.10 | Privacy & Compliance | Required |
| 2.13.11 | Migration Architecture | Required |
| 2.13.12 | Migration Approach | Required |
| 2.13.13 | Migration Mapping | Required |
| 2.13.14 | Data Transformation | Conditional |
| 2.13.15 | Data Cleansing | Required |
| 2.13.16 | Data Extraction | Required |
| 2.13.17 | Data Staging | Conditional |
| 2.13.18 | Data Loading | Required |
| 2.13.19 | Configuration Migration | Required |
| 2.13.20 | User Migration | Required |
| 2.13.21 | Queue Migration | Required |
| 2.13.22 | Skill & Language Migration | Required |
| 2.13.23 | Routing Migration | Required |
| 2.13.24 | Architect Migration | Required |
| 2.13.25 | Telephony Migration | Required |
| 2.13.26 | Digital Migration | Conditional |
| 2.13.27 | CRM / Customer Data Migration | Conditional |
| 2.13.28 | Integration Migration | Required |
| 2.13.29 | API Migration | Conditional |
| 2.13.30 | Historical Interaction Data | Conditional |
| 2.13.31 | Recording Migration | Conditional |
| 2.13.32 | Quality Data Migration | Conditional |
| 2.13.33 | WFM Data Migration | Conditional |
| 2.13.34 | Reporting Data Migration | Conditional |
| 2.13.35 | Migration Tooling | Required |
| 2.13.36 | Migration Automation | Conditional |
| 2.13.37 | Mock Migration | Required |
| 2.13.38 | Migration Rehearsal | Required |
| 2.13.39 | Cutover Migration | Required |
| 2.13.40 | Delta Migration | Conditional |
| 2.13.41 | Data Freeze | Conditional |
| 2.13.42 | Coexistence | Conditional |
| 2.13.43 | Transition Management | Required |
| 2.13.44 | Rollback & Recovery | Required |
| 2.13.45 | Migration Validation | Required |
| 2.13.46 | Data Reconciliation | Required |
| 2.13.47 | Post-Migration Validation | Required |
| 2.13.48 | Hypercare | Required |
| 2.13.49 | Operational Handover | Required |
| 2.13.50 | Legacy Platform Transition | Required |
| 2.13.51 | Data Archival | Conditional |
| 2.13.52 | Legacy Decommissioning | Conditional |
| 2.13.53 | Migration Closure | Required |

---

# 3. Migration Lifecycle

```text
Current State
      ↓
Discovery
      ↓
Assessment
      ↓
Migration Architecture
      ↓
Mapping
      ↓
Transformation / Cleansing
      ↓
Mock Migration
      ↓
Migration Rehearsal
      ↓
Cutover Preparation
      ↓
Cutover Migration
      ↓
Validation
      ↓
Reconciliation
      ↓
Transition
      ↓
Hypercare
      ↓
Legacy Transition / Retirement
      ↓
Migration Closure
```

---

# 4. Migration Principles

The project shall:

1. Define what will and will not be migrated.
2. Establish ownership of every material data set.
3. Validate source data before migration.
4. Protect sensitive and personal information.
5. Maintain source-to-target traceability.
6. Define transformation rules.
7. Reconcile migrated data.
8. Perform mock migrations for material migrations.
9. Rehearse complex cutovers.
10. Define rollback before production migration.
11. Define coexistence where required.
12. Obtain business acceptance before legacy retirement.

---

# 5. Capability Classification

Capabilities shall be classified as:

- Required
- Conditional
- Optional
- Not Applicable

The default classifications above must be reviewed during discovery.

---

# 6. Cross-Domain Dependencies

Migration may depend on:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD & Routing
- Architect
- Digital
- WFM
- Data, Integrations & APIs
- Analytics & Reporting
- Quality Management
- Security & Compliance
- Testing & Deployment
- Operations & Support

---

# 7. Layer 1 Mapping

Migration activities typically span:

| Layer 1 Activity | Migration Contribution |
|---|---|
| Discovery | Assess source environment |
| Requirements | Define migration requirements |
| Architecture | Define migration architecture |
| Design | Define mappings and conversion |
| Build | Build migration tooling |
| Integration | Validate dependent systems |
| Testing | Execute mock migrations |
| Migration | Execute production migration |
| Deployment | Execute cutover |
| Hypercare | Validate migrated environment |
| Handover | Transfer operational ownership |
| Closure | Complete reconciliation and retirement |

---

# 8. Roles

Typical roles include:

- Project Manager
- Migration Lead
- Solution Architect
- Technical Architect
- Data Architect
- Data Engineer
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Integration Engineer
- Voice / Telephony Engineer
- WFM Specialist
- Quality Specialist
- Reporting Specialist
- Security Specialist
- Compliance Specialist
- Business SME
- Data Owner
- Service Manager
- Operations Team

---

# 9. Customer Responsibilities

The customer provides:

- Source system information
- Data owners
- Data extracts
- Data classification
- Retention requirements
- Privacy requirements
- Migration approvals
- Business SMEs
- Migration acceptance
- Cutover approval
- Legacy retirement approval

---

# 10. Migration Deliverables

Typical deliverables include:

- Migration Strategy
- Migration Assessment
- Source Inventory
- Data Inventory
- Data Classification
- Data Mapping
- Transformation Rules
- Migration Architecture
- Migration Tooling
- Migration Runbook
- Mock Migration Results
- Migration Rehearsal Results
- Cutover Plan
- Rollback Plan
- Reconciliation Report
- Migration Validation Report
- Operational Handover
- Legacy Transition Plan
- Migration Closure Report

---

# 11. Effort Drivers

Migration effort is influenced by:

- Source platform complexity
- Number of source systems
- Number of users
- Number of queues
- Number of skills
- Number of Architect flows
- Number of telephone numbers
- Number of integrations
- Data volume
- Data quality
- Historical data requirements
- Recording volume
- Compliance requirements
- Number of migration waves
- Coexistence requirements
- Custom migration tooling
- Cutover complexity

---

# 12. Definition of Done

The domain is complete when:

- Migration scope is approved.
- Source systems are inventoried.
- Data ownership is defined.
- Data classification is complete.
- Migration architecture is approved.
- Mappings are approved.
- Transformation rules are documented.
- Migration tooling is validated.
- Mock migration is complete where required.
- Rehearsal is complete where required.
- Cutover is approved.
- Rollback is defined.
- Migration is executed.
- Reconciliation is complete.
- Business acceptance is obtained.
- Operational handover is complete.
- Legacy transition is approved.
- Migration closure is completed.

---

# 13. Capability Document Catalogue

```text
01-Migration-Strategy.md
02-Migration-Governance.md
03-Migration-Scope-Assessment.md
04-Source-System-Inventory.md
05-Data-Discovery.md
06-Data-Profiling.md
07-Data-Classification.md
08-Data-Ownership.md
09-Data-Retention.md
10-Privacy-Compliance.md
11-Migration-Architecture.md
12-Migration-Approach.md
13-Migration-Mapping.md
14-Data-Transformation.md
15-Data-Cleansing.md
16-Data-Extraction.md
17-Data-Staging.md
18-Data-Loading.md
19-Configuration-Migration.md
20-User-Migration.md
21-Queue-Migration.md
22-Skill-Language-Migration.md
23-Routing-Migration.md
24-Architect-Migration.md
25-Telephony-Migration.md
26-Digital-Migration.md
27-CRM-Customer-Data-Migration.md
28-Integration-Migration.md
29-API-Migration.md
30-Historical-Interaction-Data.md
31-Recording-Migration.md
32-Quality-Data-Migration.md
33-WFM-Data-Migration.md
34-Reporting-Data-Migration.md
35-Migration-Tooling.md
36-Migration-Automation.md
37-Mock-Migration.md
38-Migration-Rehearsal.md
39-Cutover-Migration.md
40-Delta-Migration.md
41-Data-Freeze.md
42-Coexistence.md
43-Transition-Management.md
44-Rollback-Recovery.md
45-Migration-Validation.md
46-Data-Reconciliation.md
47-Post-Migration-Validation.md
48-Hypercare.md
49-Operational-Handover.md
50-Legacy-Platform-Transition.md
51-Data-Archival.md
52-Legacy-Decommissioning.md
53-Migration-Closure.md
```

---

# 14. Domain Completion

The domain is complete when all applicable migration capabilities have been documented and can be decomposed into implementation tasks for the master project workbook.