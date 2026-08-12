# Layer 2.14 — Operations, Support & Service Management

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 14 — Operations, Support & Service Management  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete operational model required to transition a Genesys Cloud implementation from project delivery into stable business-as-usual operations.

---

# 1. Purpose

This domain defines how Genesys Cloud is:

- Operated
- Supported
- Governed
- Monitored
- Maintained
- Changed
- Released
- Secured
- Optimised
- Transitioned into BAU

The objective is to establish a sustainable operating model throughout the Genesys Cloud lifecycle.

---

# 2. Capability Catalogue

| ID | Capability | Default Classification |
|---|---|---|
| 2.14.01 | Operating Model | Required |
| 2.14.02 | Service Ownership | Required |
| 2.14.03 | BAU Readiness | Required |
| 2.14.04 | Support Model | Required |
| 2.14.05 | Service Desk | Required |
| 2.14.06 | L1 Support | Required |
| 2.14.07 | L2 Support | Required |
| 2.14.08 | L3 Support | Conditional |
| 2.14.09 | Genesys / Vendor Escalation | Required |
| 2.14.10 | Incident Management | Required |
| 2.14.11 | Major Incident Management | Required |
| 2.14.12 | Problem Management | Required |
| 2.14.13 | Service Request Management | Required |
| 2.14.14 | Change Management | Required |
| 2.14.15 | Release Management | Required |
| 2.14.16 | Configuration Management | Required |
| 2.14.17 | Asset Management | Conditional |
| 2.14.18 | Knowledge Management | Required |
| 2.14.19 | Monitoring & Alerting | Required |
| 2.14.20 | Platform Health | Required |
| 2.14.21 | Integration Monitoring | Required |
| 2.14.22 | Telephony Operations | Required |
| 2.14.23 | Digital Operations | Conditional |
| 2.14.24 | Architect Operations | Required |
| 2.14.25 | Routing Administration | Required |
| 2.14.26 | Identity & Access Operations | Required |
| 2.14.27 | WFM Operations | Conditional |
| 2.14.28 | Quality & Recording Operations | Conditional |
| 2.14.29 | Analytics & Reporting Operations | Required |
| 2.14.30 | Data Operations | Required |
| 2.14.31 | Security Operations | Required |
| 2.14.32 | Compliance Operations | Required |
| 2.14.33 | Operational Dashboards | Required |
| 2.14.34 | SLA / OLA Management | Required |
| 2.14.35 | KPI Management | Required |
| 2.14.36 | Service Reporting | Required |
| 2.14.37 | Capacity Management | Required |
| 2.14.38 | Performance Management | Required |
| 2.14.39 | Availability Management | Required |
| 2.14.40 | Resilience | Required |
| 2.14.41 | Business Continuity | Required |
| 2.14.42 | Disaster Recovery | Conditional |
| 2.14.43 | Maintenance Management | Required |
| 2.14.44 | Certificate & Credential Lifecycle | Conditional |
| 2.14.45 | API / OAuth Lifecycle | Conditional |
| 2.14.46 | Licensing Management | Required |
| 2.14.47 | Vendor Management | Required |
| 2.14.48 | Governance | Required |
| 2.14.49 | Audit | Required |
| 2.14.50 | Operational Documentation | Required |
| 2.14.51 | Runbooks | Required |
| 2.14.52 | Standard Operating Procedures | Required |
| 2.14.53 | Training | Required |
| 2.14.54 | Administrator Enablement | Required |
| 2.14.55 | Knowledge Transfer | Required |
| 2.14.56 | Operational Handover | Required |
| 2.14.57 | Hypercare Exit | Required |
| 2.14.58 | BAU Transition | Required |
| 2.14.59 | Continual Service Improvement | Required |
| 2.14.60 | Optimisation Backlog | Required |
| 2.14.61 | Operational Closure | Required |

---

# 3. Operating Model

```text
Business Leadership
        │
        ▼
Service Owner
        │
        ├───────────────┐
        ▼               ▼
Platform Owner      Business Owner
        │               │
        └───────┬───────┘
                ▼
        Genesys Cloud Operations
                │
       ┌────────┼────────┐
       ▼        ▼        ▼
      L1       L2       L3
    Support  Platform  Specialist
                │
        ┌───────┼───────────────┐
        ▼       ▼               ▼
     Genesys  Network/Telephony Integration
     Vendor      Teams           Teams
```

The operating model must clearly identify business, technical, service desk, application, integration, security and vendor responsibilities.

---

# 4. Capability Classification

Capabilities shall be classified as:

- Required
- Conditional
- Optional
- Not Applicable

The default classification must be reviewed during project discovery and operational readiness.

---

# 5. Cross-Domain Dependencies

Operations depends on the implementation of:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD & Routing
- Architect
- Digital
- WFM
- Data, Integrations & APIs
- Analytics & Reporting
- Quality & Recording
- Security & Compliance
- Testing & Deployment
- Migration & Transition

Operations also provides the destination for the project transition.

---

# 6. Layer 1 Mapping

| Layer 1 Activity | Operations Contribution |
|---|---|
| Discovery | Identify operational requirements |
| Requirements | Define support and service requirements |
| Architecture | Define operating model |
| Design | Design monitoring and support processes |
| Build | Establish operational tooling |
| Testing | Validate support readiness |
| Operational Readiness | Complete BAU preparation |
| Deployment | Support production deployment |
| Hypercare | Operate enhanced support |
| Handover | Accept service ownership |
| BAU | Operate and support platform |

---

# 7. Roles

Typical roles include:

- Service Owner
- Platform Owner
- Service Manager
- Project Manager
- Genesys Cloud Administrator
- L1 Support
- L2 Support
- L3 Engineering
- Voice / Telephony Engineer
- Integration Engineer
- Security Team
- Compliance Team
- WFM Team
- Quality Team
- Reporting Team
- Business Owner
- Vendor / Genesys Support

---

# 8. Customer Responsibilities

The customer must establish:

- Service ownership
- Support ownership
- Service desk
- Escalation model
- Operational processes
- BAU resources
- Change authority
- Incident authority
- Business ownership
- Vendor relationship
- Operational approvals

---

# 9. Operational Deliverables

Typical deliverables include:

- Operating Model
- Support Model
- Service Catalogue
- Escalation Matrix
- Incident Process
- Problem Process
- Change Process
- Release Process
- Monitoring Model
- Operational Dashboard
- SLA / OLA Model
- KPI Catalogue
- Runbooks
- SOPs
- Knowledge Base
- Operational Architecture
- BAU Handover Pack
- Training
- Support Readiness Assessment
- Hypercare Exit Assessment
- Service Acceptance

---

# 10. Effort Drivers

Operational effort is influenced by:

- Number of users
- Support hours
- Number of channels
- Number of integrations
- Telephony complexity
- Architect complexity
- Digital scope
- WFM scope
- Quality scope
- Reporting requirements
- Security requirements
- Compliance requirements
- SLA requirements
- Support model
- Customer operating model
- Vendor escalation model
- Monitoring requirements

---

# 11. Definition of Done

The domain is complete when:

- Operating ownership is defined.
- Support model is approved.
- Service desk is ready.
- L1/L2/L3 responsibilities are defined.
- Escalation is defined.
- Incident management is ready.
- Change management is ready.
- Release management is ready.
- Configuration management is ready.
- Monitoring is ready.
- Operational dashboards are ready.
- Runbooks are complete.
- SOPs are complete.
- Knowledge transfer is complete.
- Training is complete.
- Operational handover is accepted.
- Hypercare exit criteria are achieved.
- BAU transition is complete.
- Operational closure is accepted.

---

# 12. Capability Document Catalogue

```text
01-Operating-Model.md
02-Service-Ownership.md
03-BAU-Readiness.md
04-Support-Model.md
05-Service-Desk.md
06-L1-Support.md
07-L2-Support.md
08-L3-Support.md
09-Genesys-Vendor-Escalation.md
10-Incident-Management.md
11-Major-Incident-Management.md
12-Problem-Management.md
13-Service-Request-Management.md
14-Change-Management.md
15-Release-Management.md
16-Configuration-Management.md
17-Asset-Management.md
18-Knowledge-Management.md
19-Monitoring-Alerting.md
20-Platform-Health.md
21-Integration-Monitoring.md
22-Telephony-Operations.md
23-Digital-Operations.md
24-Architect-Operations.md
25-Routing-Administration.md
26-Identity-Access-Operations.md
27-WFM-Operations.md
28-Quality-Recording-Operations.md
29-Analytics-Reporting-Operations.md
30-Data-Operations.md
31-Security-Operations.md
32-Compliance-Operations.md
33-Operational-Dashboards.md
34-SLA-OLA-Management.md
35-KPI-Management.md
36-Service-Reporting.md
37-Capacity-Management.md
38-Performance-Management.md
39-Availability-Management.md
40-Resilience.md
41-Business-Continuity.md
42-Disaster-Recovery.md
43-Maintenance-Management.md
44-Certificate-Credential-Lifecycle.md
45-API-OAuth-Lifecycle.md
46-Licensing-Management.md
47-Vendor-Management.md
48-Governance.md
49-Audit.md
50-Operational-Documentation.md
51-Runbooks.md
52-Standard-Operating-Procedures.md
53-Training.md
54-Administrator-Enablement.md
55-Knowledge-Transfer.md
56-Operational-Handover.md
57-Hypercare-Exit.md
58-BAU-Transition.md
59-Continual-Service-Improvement.md
60-Optimisation-Backlog.md
61-Operational-Closure.md
```

---

# 13. Domain Completion

The domain is complete when all applicable operational capabilities have been documented, accepted and decomposed into implementation and BAU tasks for the master project workbook.