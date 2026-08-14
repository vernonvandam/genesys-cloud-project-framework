# Layer 2 — Genesys Cloud Capability Framework

## Capability Framework README

**Methodology:** Genesys Cloud Project Framework  
**Layer:** 2 — Capability Framework  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete Genesys Cloud capability catalogue that feeds the Layer 1 deployment lifecycle, detailed implementation task catalogue, project schedule, and effort estimation model.

---

# 1. Purpose

Layer 2 defines **what may need to be deployed, configured, integrated, migrated, tested, operated and optimised** within a Genesys Cloud implementation.

Layer 2 answers:

> **What are we deploying?**

Layer 1 defines the project lifecycle and sequencing.

Layer 2 defines the capabilities that must be considered within that lifecycle.

The two layers therefore work together:

```text
Layer 1
Deployment Lifecycle
        │
        │ When?
        ▼
Layer 2
Capability Framework
        │
        │ What?
        ▼
Implementation Task Catalogue
        │
        │ How?
        ▼
Master Project Schedule
        │
        ▼
Effort & Resource Model
```

The purpose of Layer 2 is to provide a comprehensive capability inventory so that significant Genesys Cloud functionality is not accidentally omitted from a project.

---

# 2. Objectives

The Layer 2 capability framework shall:

- Provide a comprehensive Genesys Cloud capability catalogue.
- Establish a consistent capability taxonomy.
- Identify required, conditional, optional and excluded capabilities.
- Map capabilities to Layer 1 project phases.
- Identify dependencies between capabilities.
- Identify implementation prerequisites.
- Identify architecture considerations.
- Identify security and compliance considerations.
- Identify integration requirements.
- Identify migration considerations.
- Identify testing requirements.
- Identify operational requirements.
- Identify BAU ownership.
- Provide the source material for implementation tasks.
- Support project estimation.
- Support solution architecture.
- Support scope definition.
- Support work breakdown structure development.
- Support testing strategy.
- Support operational readiness.
- Support transition to BAU.
- Support optimisation and continuous improvement.

---

# 3. Relationship to Layer 1

Layer 1 defines the **deployment sequence**.

Layer 2 defines the **capabilities deployed within that sequence**.

```text
Layer 1
───────────────
Phase 01
Phase 02
Phase 03
Phase 04
Phase 05
Phase 06
Phase 07
Phase 08
Phase 09
Phase 10
Phase 11
Phase 12
───────────────
        │
        ▼
Layer 2
──────────────────────────────────────────
01 Core Platform
02 Identity & Access
03 Voice & Telephony
04 ACD & Routing
05 Architect
06 Digital
07 WFM & Employee Engagement
08 Data, Integrations & APIs
09 Analytics, Reporting & Data Visualisation
10 Quality, Recording & Evaluation
11 Security, Compliance & Governance
12 Testing, Validation & Deployment
13 Migration, Data Conversion & Transition
14 Operations, Support & Service Management
15 Optimisation & Platform Evolution
──────────────────────────────────────────
```

A capability may participate in multiple Layer 1 phases.

---

# 4. Capability Domains

Layer 2 is divided into 15 capability domains.

| Domain | Capability Domain | Purpose |
|---|---|---|
| 01 | Core Platform | Core Genesys Cloud organisation and platform foundation |
| 02 | Identity & Access | Identity, authentication, authorisation and access |
| 03 | Voice & Telephony | Voice architecture, telephony, numbering and carrier services |
| 04 | ACD & Routing | Queues, skills, routing and interaction distribution |
| 05 | Architect | Interaction flows, logic, orchestration and automation |
| 06 | Digital | Digital channels, routing and digital experience |
| 07 | Workforce Management & Employee Engagement | Forecasting, scheduling, adherence and employee engagement |
| 08 | Data, Integrations & APIs | External systems, data exchange and extensibility |
| 09 | Analytics, Reporting & Data Visualisation | Operational, business and analytical reporting |
| 10 | Quality Management, Recording & Evaluation | Recording, quality, evaluation and coaching |
| 11 | Security, Compliance & Governance | Security controls, compliance and governance |
| 12 | Testing, Validation & Deployment | Validation, testing, release and deployment controls |
| 13 | Migration, Data Conversion & Transition | Migration, conversion, cutover and transition |
| 14 | Operations, Support & Service Management | BAU operations, support and service management |
| 15 | Optimisation, Continuous Improvement & Platform Evolution | Optimisation, maturity, innovation and lifecycle evolution |

---

# 5. Domain 01 — Core Platform

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 01-Core-Platform/
```

Core Platform covers the foundational Genesys Cloud organisation and configuration model.

Typical capabilities include:

- Genesys Cloud organisation
- Region
- Divisions
- Users
- Groups
- Roles
- Permissions
- Locations
- Sites
- Work teams
- Policies
- Configuration
- Platform settings
- Environment standards
- Naming standards
- Configuration governance

The individual capability documents within this domain provide the detailed implementation methodology.

---

# 6. Domain 02 — Identity & Access

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 02-Identity-Access/
```

Identity & Access covers:

- SSO
- SAML
- Identity providers
- OAuth
- MFA
- SCIM
- User provisioning
- User deprovisioning
- Role mapping
- Permission management
- Access governance
- Privileged access
- Service identities
- Authentication lifecycle

---

# 7. Domain 03 — Voice & Telephony

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 03-Voice-Telephony/
```

Voice & Telephony covers:

- Genesys Cloud Voice
- BYOC Cloud
- BYOC Premises
- SIP
- Carrier services
- DID
- Toll-free numbers
- Number porting
- Sites
- Edges
- Phones
- Network requirements
- Emergency services
- Number plans
- Outbound routes
- Caller ID
- Telephony testing
- Voice quality
- Carrier management

---

# 8. Domain 04 — ACD & Routing

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 04-ACD-Routing/
```

ACD & Routing covers:

- Queues
- Skills
- Languages
- Routing methods
- Bullseye routing
- Priority
- Preferred agents
- Queue membership
- Overflow
- Callback
- Transfer
- Utilisation
- Routing rules
- Business rules
- Routing optimisation

---

# 9. Domain 05 — Architect

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 05-Architect/
```

Architect covers interaction orchestration including:

- Inbound voice flows
- Inbound messaging flows
- Chat flows
- Email flows
- Callback
- Outbound flows
- In-queue flows
- Secure flows
- Bot flows
- Common modules
- Data Actions
- Data Tables
- Prompts
- Schedules
- Business hours
- Holiday schedules
- Error handling
- Flow versioning
- Flow deployment

---

# 10. Domain 06 — Digital

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 06-Digital/
```

Digital covers:

- Web messaging
- Web chat
- Email
- SMS
- Open messaging
- Social messaging
- Digital routing
- Digital bots
- Digital Architect flows
- Digital queues
- Digital skills
- Digital reporting
- Digital customer experience

---

# 11. Domain 07 — Workforce Management & Employee Engagement

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 07-Workforce-Management-Employee-Engagement/
```

This domain covers:

- Business units
- Management units
- Planning groups
- Forecasting
- Scheduling
- Time off
- Adherence
- Intraday management
- WFM integrations
- WFM reporting
- Employee engagement
- Performance management
- Workforce optimisation

---

# 12. Domain 08 — Data, Integrations & APIs

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 08-Data-Integrations-APIs/
```

This domain covers:

- CRM
- IAM
- ERP
- ITSM
- WFM integrations
- QM integrations
- Middleware
- Customer databases
- Custom applications
- Platform APIs
- Data exchange
- Webhooks
- Data Actions
- Eventing
- Integration security
- Integration monitoring

---

# 13. Domain 09 — Analytics, Reporting & Data Visualisation

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 09-Analytics-Reporting-Data-Visualisation/
```

This domain covers:

- Performance views
- Interaction analytics
- Speech and text analytics
- Dashboards
- Reports
- Scheduled reports
- Data exports
- APIs
- KPI reporting
- Operational reporting
- Management reporting
- Executive reporting
- Data visualisation
- Analytics governance

---

# 14. Domain 10 — Quality Management, Recording & Evaluation

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 10-Quality-Management-Recording-Evaluation/
```

This domain covers:

- Recording
- Evaluation forms
- Evaluation policies
- Quality programs
- Calibration
- Coaching
- Quality reporting
- Recording policies
- Recording retention
- Recording access
- Secure pause
- Playback
- Export
- Recording search
- Compliance
- Quality governance

---

# 15. Domain 11 — Security, Compliance & Governance

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 11-Security-Compliance-Governance/
```

This domain covers:

- Security architecture
- Authentication
- Authorisation
- Permission governance
- Data protection
- Privacy
- Compliance
- Audit
- Logging
- Data retention
- Recording compliance
- Access reviews
- Regulatory requirements
- Security monitoring
- Governance

---

# 16. Domain 12 — Testing, Validation & Deployment

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 12-Testing-Validation-Deployment/
```

This domain covers:

- Test strategy
- Test planning
- Unit testing
- Configuration testing
- Integration testing
- System integration testing
- User acceptance testing
- Regression testing
- Performance testing
- Security testing
- Operational testing
- Deployment validation
- Release management
- Production deployment
- Rollback
- Validation

---

# 17. Domain 13 — Migration, Data Conversion & Transition

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 13-Migration-Data-Conversion-Transition/
```

This domain covers:

- Migration strategy
- Data discovery
- Data mapping
- Data cleansing
- Data conversion
- Configuration migration
- User migration
- Number migration
- Historical data
- Recording migration
- Integration transition
- Cutover
- Transition
- Hypercare
- Legacy decommissioning

---

# 18. Domain 14 — Operations, Support & Service Management

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 14-Operations-Support-Service-Management/
```

This domain covers:

- Operational ownership
- Service management
- Incident management
- Major incident management
- Problem management
- Change management
- Request fulfilment
- Release management
- Configuration management
- Platform monitoring
- Alerting
- Service level management
- Service reporting
- Operational KPIs
- Runbooks
- Knowledge management
- BAU support
- Service desk
- Escalation management
- Vendor management
- Operational readiness
- Hypercare
- BAU handover
- Service review

---

# 19. Domain 15 — Optimisation, Continuous Improvement & Platform Evolution

**Directory:**

```text
Layer 2 — Genesys Cloud Capability Framework/
└── 15-Optimisation-Continuous-Improvement-Platform-Evolution/
```

This domain covers the post-implementation lifecycle and ensures Genesys Cloud remains aligned with business strategy.

Capabilities include:

- Continuous improvement strategy
- Optimisation governance
- Platform roadmap
- Business value realisation
- Capability maturity
- KPI-driven optimisation
- Customer experience optimisation
- Agent experience optimisation
- Voice optimisation
- Routing optimisation
- Architect optimisation
- Digital optimisation
- WFM optimisation
- Quality optimisation
- Recording optimisation
- Analytics optimisation
- Reporting optimisation
- Data optimisation
- Integration optimisation
- API optimisation
- Automation
- Infrastructure as Code
- Security optimisation
- Compliance optimisation
- Performance optimisation
- Capacity optimisation
- Resilience optimisation
- Business continuity optimisation
- Licensing optimisation
- Cost optimisation
- Configuration hygiene
- Technical debt management
- Architecture evolution
- Feature adoption
- Genesys release assessment
- Product capability assessment
- Innovation management
- Proof of Concept
- Pilot management
- Controlled rollout
- Benefits tracking
- Backlog management
- Prioritisation
- Change portfolio management
- Continuous training
- Operational maturity
- Lessons learned
- Legacy reduction
- Capability retirement
- Platform lifecycle management
- Methodology improvement

---

# 20. Capability Classification

Every capability shall be classified as one of the following:

- Required
- Conditional
- Optional
- Not Applicable

---

## 20.1 Required

A capability is **Required** when it is necessary to satisfy the project's agreed business, technical, operational, security or compliance requirements.

Required does not necessarily mean every customer must implement the capability.

It means that the capability is required **for the specific project**.

---

## 20.2 Conditional

A capability is **Conditional** when its applicability depends on:

- Customer requirements
- Business process
- Geography
- Regulatory requirements
- Architecture
- Licensing
- Existing technology
- Integration requirements
- Channel strategy
- User population
- Deployment model

Examples include:

- WFM
- Digital channels
- BYOC Premises
- API development
- Custom applications
- Advanced integrations
- Recording migration
- Terraform
- Proof of Concept
- Pilot deployment

---

## 20.3 Optional

An **Optional** capability may provide additional business or technical value but is not necessary to satisfy the defined project scope.

Examples may include:

- Innovation initiatives
- Advanced automation
- Experimental capabilities
- Additional analytics
- Additional visualisation
- Advanced optimisation

---

## 20.4 Not Applicable

A capability is **Not Applicable** when it has been explicitly assessed and excluded from the project.

The reason for exclusion should be documented.

---

# 21. Capability Documentation Standard

Every capability should eventually have its own Markdown document.

The standard structure is:

```text
# Layer 2.xx.xx — Capability Name

## Capability Definition

---
