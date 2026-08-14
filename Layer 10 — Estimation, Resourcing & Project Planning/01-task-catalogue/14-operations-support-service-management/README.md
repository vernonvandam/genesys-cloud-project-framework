# Layer 10 — 14 Operations, Support & Service Management Task Catalogue

## Purpose

This directory contains the Layer 10 implementation task catalogue for the **Layer 2 — 14 Operations, Support & Service Management** capability domain.

The catalogue translates the Layer 2 operational capabilities and implementation activities into discrete, estimable, assignable, schedulable and traceable implementation tasks.

The catalogue is designed to support:

- project planning
- effort estimation
- resource planning
- dependency modelling
- project scheduling
- customer responsibility assignment
- operational readiness
- BAU transition
- implementation tracking
- acceptance management
- master project workbook generation

---

# Domain Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Task Catalogue Domain | 14 — Operations, Support & Service Management |
| Layer 2 Domain | 14 — Operations, Support & Service Management |
| Domain Type | Operations / BAU |
| Capability Count | 61 |
| Task Catalogue Prefix | L10-14 |
| Primary Layer 1 Phases | P01–P12 |
| Task Catalogue Status | Baseline Task Catalogue |

---

# Relationship to Layer 2

The authoritative capability definitions are maintained within:

```text
Layer 2 — Genesys Cloud Capability Framework
└── 14-Operations-Support-Service-Management
```

Layer 10 does not redefine the Layer 2 capability catalogue.

Instead, it decomposes the Layer 2 implementation activities into individual project and operational tasks.

```text
Layer 2 Capability
        │
        ▼
Implementation Activity
        │
        ▼
Layer 10 Capability Task File
        │
        ├── Implementation Task
        ├── Implementation Task
        └── Validation / Handover Task
        │
        ▼
Project Schedule
        │
        ▼
Effort Estimate
        │
        ▼
Resource Plan
        │
        ▼
BAU Operating Model
```

---

# Capability Catalogue

| Capability ID | Capability | Task Catalogue File | Classification |
|---|---|---|---|
| 2.14.01 | Operating Model | `01-operating-model.md` | Required |
| 2.14.02 | Service Ownership | `02-service-ownership.md` | Required |
| 2.14.03 | BAU Readiness | `03-bau-readiness.md` | Required |
| 2.14.04 | Support Model | `04-support-model.md` | Required |
| 2.14.05 | Service Desk | `05-service-desk.md` | Required |
| 2.14.06 | L1 Support | `06-l1-support.md` | Required |
| 2.14.07 | L2 Support | `07-l2-support.md` | Required |
| 2.14.08 | L3 Support | `08-l3-support.md` | Conditional |
| 2.14.09 | Genesys / Vendor Escalation | `09-genesys-vendor-escalation.md` | Required |
| 2.14.10 | Incident Management | `10-incident-management.md` | Required |
| 2.14.11 | Major Incident Management | `11-major-incident-management.md` | Required |
| 2.14.12 | Problem Management | `12-problem-management.md` | Required |
| 2.14.13 | Service Request Management | `13-service-request-management.md` | Required |
| 2.14.14 | Change Management | `14-change-management.md` | Required |
| 2.14.15 | Release Management | `15-release-management.md` | Required |
| 2.14.16 | Configuration Management | `16-configuration-management.md` | Required |
| 2.14.17 | Asset Management | `17-asset-management.md` | Conditional |
| 2.14.18 | Knowledge Management | `18-knowledge-management.md` | Required |
| 2.14.19 | Monitoring & Alerting | `19-monitoring-alerting.md` | Required |
| 2.14.20 | Platform Health | `20-platform-health.md` | Required |
| 2.14.21 | Integration Monitoring | `21-integration-monitoring.md` | Required |
| 2.14.22 | Telephony Operations | `22-telephony-operations.md` | Required |
| 2.14.23 | Digital Operations | `23-digital-operations.md` | Conditional |
| 2.14.24 | Architect Operations | `24-architect-operations.md` | Required |
| 2.14.25 | Routing Administration | `25-routing-administration.md` | Required |
| 2.14.26 | Identity & Access Operations | `26-identity-access-operations.md` | Required |
| 2.14.27 | WFM Operations | `27-wfm-operations.md` | Conditional |
| 2.14.28 | Quality & Recording Operations | `28-quality-recording-operations.md` | Conditional |
| 2.14.29 | Analytics & Reporting Operations | `29-analytics-reporting-operations.md` | Required |
| 2.14.30 | Data Operations | `30-data-operations.md` | Required |
| 2.14.31 | Security Operations | `31-security-operations.md` | Required |
| 2.14.32 | Compliance Operations | `32-compliance-operations.md` | Required |
| 2.14.33 | Operational Dashboards | `33-operational-dashboards.md` | Required |
| 2.14.34 | SLA / OLA Management | `34-sla-ola-management.md` | Required |
| 2.14.35 | KPI Management | `35-kpi-management.md` | Required |
| 2.14.36 | Service Reporting | `36-service-reporting.md` | Required |
| 2.14.37 | Capacity Management | `37-capacity-management.md` | Required |
| 2.14.38 | Performance Management | `38-performance-management.md` | Required |
| 2.14.39 | Availability Management | `39-availability-management.md` | Required |
| 2.14.40 | Resilience | `40-resilience.md` | Required |
| 2.14.41 | Business Continuity | `41-business-continuity.md` | Required |
| 2.14.42 | Disaster Recovery | `42-disaster-recovery.md` | Conditional |
| 2.14.43 | Maintenance Management | `43-maintenance-management.md` | Required |
| 2.14.44 | Certificate & Credential Lifecycle | `44-certificate-credential-lifecycle.md` | Conditional |
| 2.14.45 | API / OAuth Lifecycle | `45-api-oauth-lifecycle.md` | Conditional |
| 2.14.46 | Licensing Management | `46-licensing-management.md` | Required |
| 2.14.47 | Vendor Management | `47-vendor-management.md` | Required |
| 2.14.48 | Governance | `48-governance.md` | Required |
| 2.14.49 | Audit | `49-audit.md` | Required |
| 2.14.50 | Operational Documentation | `50-operational-documentation.md` | Required |
| 2.14.51 | Runbooks | `51-runbooks.md` | Required |
| 2.14.52 | Standard Operating Procedures | `52-standard-operating-procedures.md` | Required |
| 2.14.53 | Training | `53-training.md` | Required |
| 2.14.54 | Administrator Enablement | `54-administrator-enablement.md` | Required |
| 2.14.55 | Knowledge Transfer | `55-knowledge-transfer.md` | Required |
| 2.14.56 | Operational Handover | `56-operational-handover.md` | Required |
| 2.14.57 | Hypercare Exit | `57-hypercare-exit.md` | Required |
| 2.14.58 | BAU Transition | `58-bau-transition.md` | Required |
| 2.14.59 | Continual Service Improvement | `59-continual-service-improvement.md` | Required |
| 2.14.60 | Optimisation Backlog | `60-optimisation-backlog.md` | Required |
| 2.14.61 | Operational Closure | `61-operational-closure.md` | Required |

---

# Task ID Convention

Operations tasks use:

```text
L10-14.CC-TTT
```

Where:

| Component | Meaning |
|---|---|
| `L10` | Layer 10 |
| `14` | Operations, Support & Service Management |
| `CC` | Capability number |
| `TTT` | Sequential task number |

Examples:

```text
L10-14.01-001
L10-14.01-002
L10-14.02-001
L10-14.61-001
```

---

# Layer 1 Mapping

Operations activities may span the complete Layer 1 lifecycle.

| Phase | Operations Application |
|---|---|
| P01 — Project Initiation & Mobilisation | Establish operational stakeholders and ownership |
| P02 — Discovery & Current-State Assessment | Assess current support and operating model |
| P03 — Requirements & Solution Definition | Define operational requirements |
| P04 — Solution Architecture & Detailed Design | Design operating model and service controls |
| P05 — Platform Foundation & Environment Build | Establish operational foundations |
| P06 — Configuration & Development | Configure operational capabilities |
| P07 — Integration & Data Enablement | Establish operational integration dependencies |
| P08 — Testing, Validation & Defect Resolution | Validate operational processes |
| P09 — Operational Readiness & Training | Prepare BAU operations |
| P10 — Go-Live Preparation & Cutover | Confirm production operational readiness |
| P11 — Go-Live & Hypercare | Operate and stabilise the service |
| P12 — BAU Handover & Project Closure | Complete service acceptance and transition |

---

# Standard Task Attributes

Every task follows the established Layer 10 task-file model.

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

---

# Task Design Principle

Tasks must be atomic enough to become individual project schedule rows.

Each task must contain:

- unique Task ID
- single implementation outcome
- explicit dependencies
- accountable delivery role
- customer responsibility
- environment
- automation classification
- baseline effort
- deliverable
- acceptance criteria
- critical-path classification

---

# Definition of Done

Section 14 is complete when:

- all 61 capabilities have task files
- every capability references its Layer 2 capability
- implementation activities are decomposed into tasks
- every task has a Layer 1 mapping
- dependencies are defined
- delivery roles are assigned
- customer responsibilities are identified
- environments are identified
- automation classification is defined
- baseline effort can be estimated
- deliverables are defined
- acceptance criteria are defined
- critical-path tasks are identified
- operational readiness is measurable
- BAU transition is measurable
- the catalogue can be converted into the master project schedule and estimation model

---

# Capability Files

The following files are required in this directory:

```text
01-operating-model.md
02-service-ownership.md
03-bau-readiness.md
04-support-model.md
05-service-desk.md
06-l1-support.md
07-l2-support.md
08-l3-support.md
09-genesys-vendor-escalation.md
10-incident-management.md
11-major-incident-management.md
12-problem-management.md
13-service-request-management.md
14-change-management.md
15-release-management.md
16-configuration-management.md
17-asset-management.md
18-knowledge-management.md
19-monitoring-alerting.md
20-platform-health.md
21-integration-monitoring.md
22-telephony-operations.md
23-digital-operations.md
24-architect-operations.md
25-routing-administration.md
26-identity-access-operations.md
27-wfm-operations.md
28-quality-recording-operations.md
29-analytics-reporting-operations.md
30-data-operations.md
31-security-operations.md
32-compliance-operations.md
33-operational-dashboards.md
34-sla-ola-management.md
35-kpi-management.md
36-service-reporting.md
37-capacity-management.md
38-performance-management.md
39-availability-management.md
40-resilience.md
41-business-continuity.md
42-disaster-recovery.md
43-maintenance-management.md
44-certificate-credential-lifecycle.md
45-api-oauth-lifecycle.md
46-licensing-management.md
47-vendor-management.md
48-governance.md
49-audit.md
50-operational-documentation.md
51-runbooks.md
52-standard-operating-procedures.md
53-training.md
54-administrator-enablement.md
55-knowledge-transfer.md
56-operational-handover.md
57-hypercare-exit.md
58-bau-transition.md
59-continual-service-improvement.md
60-optimisation-backlog.md
61-operational-closure.md
```

---

# Layer 2 Traceability

```text
Layer 2 Capability
        ↓
Layer 2 Implementation Activities
        ↓
Layer 10 Capability Task File
        ↓
L10-14.CC-TTT
        ↓
Project Schedule
        ↓
Effort Estimate
        ↓
Resource Plan
        ↓
Operational Readiness
        ↓
BAU Service
```

---
