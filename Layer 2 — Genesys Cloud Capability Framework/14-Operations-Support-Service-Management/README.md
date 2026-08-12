# Layer 2.14 — Operations, Support & Service Management

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 14 — Operations, Support & Service Management  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete operational model required to transition a Genesys Cloud implementation from project delivery into stable business-as-usual operations, including support, service management, monitoring, governance, maintenance, incident management, change management, continual improvement and operational ownership.

---

# 1. Purpose

The Operations, Support & Service Management domain defines how the Genesys Cloud platform will be operated, supported, governed, maintained and continuously improved after implementation.

A successful Genesys Cloud deployment is not complete when production cutover occurs.

The project must establish the operating model required to support:

- Genesys Cloud administration
- User administration
- Identity and access
- Voice and telephony
- ACD and routing
- Architect
- Digital channels
- Workforce Management
- Quality Management
- Recording
- Analytics
- Reporting
- Integrations
- APIs
- Data
- Security
- Compliance
- Configuration
- Change
- Release management
- Incident management
- Problem management
- Service requests
- Monitoring
- Capacity
- Availability
- Business continuity
- Disaster recovery
- Vendor management
- Licensing
- Operational governance
- Continual improvement

The objective is to create a sustainable BAU operating model that can support the Genesys Cloud platform throughout its lifecycle.

---

# 2. Scope

```text
14 Operations, Support & Service Management
│
├── 01 Operating Model
├── 02 Service Ownership
├── 03 BAU Readiness
├── 04 Support Model
├── 05 Service Desk
├── 06 L1 Support
├── 07 L2 Support
├── 08 L3 Support
├── 09 Genesys / Vendor Escalation
├── 10 Incident Management
├── 11 Major Incident Management
├── 12 Problem Management
├── 13 Service Request Management
├── 14 Change Management
├── 15 Release Management
├── 16 Configuration Management
├── 17 Asset Management
├── 18 Knowledge Management
├── 19 Monitoring & Alerting
├── 20 Platform Health
├── 21 Integration Monitoring
├── 22 Telephony Operations
├── 23 Digital Operations
├── 24 Architect Operations
├── 25 Routing Administration
├── 26 Identity & Access Operations
├── 27 WFM Operations
├── 28 Quality & Recording Operations
├── 29 Analytics & Reporting Operations
├── 30 Data Operations
├── 31 Security Operations
├── 32 Compliance Operations
├── 33 Operational Dashboards
├── 34 SLA / OLA Management
├── 35 KPI Management
├── 36 Service Reporting
├── 37 Capacity Management
├── 38 Performance Management
├── 39 Availability Management
├── 40 Resilience
├── 41 Business Continuity
├── 42 Disaster Recovery
├── 43 Maintenance Management
├── 44 Certificate & Credential Lifecycle
├── 45 API / OAuth Lifecycle
├── 46 Licensing Management
├── 47 Vendor Management
├── 48 Governance
├── 49 Audit
├── 50 Operational Documentation
├── 51 Runbooks
├── 52 Standard Operating Procedures
├── 53 Training
├── 54 Administrator Enablement
├── 55 Knowledge Transfer
├── 56 Operational Handover
├── 57 Hypercare Exit
├── 58 BAU Transition
├── 59 Continual Service Improvement
├── 60 Optimisation Backlog
└── 61 Operational Closure
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Operating Model | Required |
| Service Ownership | Required |
| BAU Readiness | Required |
| Support Model | Required |
| Service Desk | Required |
| L1 Support | Required |
| L2 Support | Required |
| L3 Support | Conditional |
| Genesys / Vendor Escalation | Required |
| Incident Management | Required |
| Major Incident Management | Required |
| Problem Management | Required |
| Service Request Management | Required |
| Change Management | Required |
| Release Management | Required |
| Configuration Management | Required |
| Asset Management | Conditional |
| Knowledge Management | Required |
| Monitoring & Alerting | Required |
| Platform Health | Required |
| Integration Monitoring | Required |
| Telephony Operations | Required |
| Digital Operations | Conditional |
| Architect Operations | Required |
| Routing Administration | Required |
| Identity & Access Operations | Required |
| WFM Operations | Conditional |
| Quality & Recording Operations | Conditional |
| Analytics & Reporting Operations | Required |
| Data Operations | Required |
| Security Operations | Required |
| Compliance Operations | Required |
| Operational Dashboards | Required |
| SLA / OLA Management | Required |
| KPI Management | Required |
| Service Reporting | Required |
| Capacity Management | Required |
| Performance Management | Required |
| Availability Management | Required |
| Resilience | Required |
| Business Continuity | Required |
| Disaster Recovery | Conditional |
| Maintenance Management | Required |
| Certificate & Credential Lifecycle | Conditional |
| API / OAuth Lifecycle | Conditional |
| Licensing Management | Required |
| Vendor Management | Required |
| Governance | Required |
| Audit | Required |
| Operational Documentation | Required |
| Runbooks | Required |
| Standard Operating Procedures | Required |
| Training | Required |
| Administrator Enablement | Required |
| Knowledge Transfer | Required |
| Operational Handover | Required |
| Hypercare Exit | Required |
| BAU Transition | Required |
| Continual Service Improvement | Required |
| Optimisation Backlog | Required |
| Operational Closure | Required |

---

# 4. Operating Model

The operating model defines who is responsible for operating Genesys Cloud after project completion.

A typical model should include:

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

The operating model must clearly distinguish:

- Business ownership
- Platform ownership
- Technical administration
- Service desk responsibilities
- Application support
- Infrastructure support
- Integration support
- Security support
- Vendor escalation

---

# 5. Service Ownership

The project must establish a named owner for the Genesys Cloud service.

The service owner is accountable for:

- Service performance
- Service availability
- Service governance
- Service reporting
- Operational risks
- Service improvements
- Major incidents
- Business alignment
- Vendor relationship
- Service roadmap

---

# 6. BAU Readiness

BAU readiness should be assessed across:

### People

- Support team
- Administrators
- Service desk
- Platform specialists
- Integration specialists
- Security
- Business owners

### Process

- Incident
- Problem
- Change
- Request
- Release
- Escalation
- Maintenance
- Reporting

### Technology

- Monitoring
- Logging
- Integration monitoring
- Operational dashboards
- Administration
- Backup/restore strategy where applicable

### Documentation

- Architecture
- Configuration
- Runbooks
- SOPs
- Support procedures
- Escalation procedures

---

# 7. Support Model

The support model should define:

| Level | Responsibility |
|---|---|
| L0 | Self-service / knowledge |
| L1 | Service desk / first-line support |
| L2 | Genesys Cloud platform support |
| L3 | Specialist engineering |
| Vendor | Genesys support / specialist escalation |

Support boundaries must be documented.

---

# 8. Service Desk

The service desk should be capable of handling:

- User access issues
- Login issues
- Basic agent issues
- Device issues
- Queue issues
- Service requests
- Incident logging
- Initial triage
- Categorisation
- Prioritisation
- Escalation

The service desk must have access to appropriate knowledge articles and diagnostic procedures.

---

# 9. L1 Support

L1 should handle:

- Basic user access
- Agent login
- Browser/device checks
- Basic telephony troubleshooting
- Basic queue issues
- Known incidents
- Password/identity workflow where applicable
- Standard requests

L1 should not modify complex platform configuration without appropriate authorisation.

---

# 10. L2 Support

L2 should handle:

- Genesys Cloud configuration
- Routing
- Architect
- Queue configuration
- Skills
- User configuration
- Telephony configuration
- Digital configuration
- WFM configuration where applicable
- Reporting
- Integration troubleshooting

---

# 11. L3 Support

L3 support is generally required for complex enterprise environments.

Responsibilities may include:

- Advanced troubleshooting
- API analysis
- Integration engineering
- Complex Architect defects
- Performance investigation
- Advanced routing analysis
- Platform architecture
- Automation
- Custom tooling
- Engineering changes

---

# 12. Genesys / Vendor Escalation

The operating model must define when issues are escalated to Genesys.

Examples:

- Suspected platform defect
- Service outage
- Platform performance issue
- API platform issue
- Carrier issue where Genesys support is required
- Service limitation
- Security issue
- Product defect

The escalation process must define:

- Required evidence
- Severity
- Contact mechanism
- Ownership
- Communication
- Escalation timing
- Case tracking

---

# 13. Incident Management

Incident management must define:

- Incident identification
- Logging
- Categorisation
- Priority
- Assignment
- Investigation
- Escalation
- Resolution
- Validation
- Closure

Incident categories should include:

- Voice
- Digital
- Routing
- Architect
- User
- Identity
- Integration
- WFM
- Quality
- Recording
- Reporting
- Security
- Platform

---

# 14. Major Incident Management

Major incidents require a dedicated process.

```text
Incident Detected
       ↓
Severity Assessment
       ↓
Major Incident Declared
       ↓
Incident Manager Assigned
       ↓
Technical Bridge
       ↓
Business Communications
       ↓
Vendor Escalation
       ↓
Workaround / Resolution
       ↓
Service Validation
       ↓
Business Acceptance
       ↓
Incident Closed
       ↓
Problem / RCA
```

---

# 15. Problem Management

Problem management addresses recurring or systemic incidents.

Activities include:

- Trend analysis
- Root cause analysis
- Known error management
- Corrective action
- Preventative action
- Permanent resolution
- Knowledge article creation

---

# 16. Root Cause Analysis

For significant incidents, conduct RCA covering:

- What happened?
- When did it happen?
- What was affected?
- Why did it happen?
- Why was it not detected earlier?
- What was the impact?
- What resolved it?
- What will prevent recurrence?

---

# 17. Service Request Management

Standard service requests may include:

- User creation
- User modification
- Queue membership
- Skill assignment
- Permission changes
- Schedule changes
- Routing changes
- Reporting requests
- WFM requests
- Digital configuration requests

Requests should have:

- Standard workflow
- Approval
- SLA
- Fulfilment process
- Validation
- Closure

---

# 18. Change Management

Changes should be classified as:

- Standard
- Normal
- Emergency

Examples:

- Routing changes
- Architect changes
- Queue changes
- Skill changes
- User permissions
- Telephony
- Integrations
- APIs
- Reporting
- Security

---

# 19. Change Assessment

Each change should assess:

- Business impact
- Technical impact
- Risk
- Dependencies
- Testing
- Rollback
- Communications
- Maintenance window
- Approvals

---

# 20. Release Management

Release management should coordinate:

- Genesys platform changes
- Customer configuration
- Architect changes
- Integrations
- APIs
- Scripts
- Terraform
- Reporting
- Digital changes

Where configuration is managed through infrastructure-as-code, releases should use controlled versioning and promotion.

---

# 21. Configuration Management

Maintain an authoritative configuration baseline covering:

- Organisation
- Divisions
- Users
- Roles
- Groups
- Queues
- Skills
- Languages
- Routing
- Architect
- Data Tables
- Integrations
- Data Actions
- Scripts
- Schedules
- Telephony
- Digital
- WFM
- Quality
- Recording
- Analytics

---

# 22. Configuration Drift

The operational model should detect and manage configuration drift.

```text
Approved Baseline
       │
       ▼
Current Environment
       │
       ▼
Comparison
       │
   ┌───┴────┐
   ▼        ▼
Match     Drift
            │
            ▼
        Investigation
            │
       ┌────┴────┐
       ▼         ▼
Approved      Unapproved
 Change         Change
       │         │
       ▼         ▼
Retain       Remediate
```

---

# 23. Asset Management

Where applicable, track:

- Telephone numbers
- Devices
- Headsets
- Network components
- Edge appliances
- Integrations
- Certificates
- Credentials
- Licenses
- Service accounts
- Applications

---

# 24. Knowledge Management

Create a searchable knowledge base containing:

- User procedures
- Administrator procedures
- Troubleshooting
- Known errors
- FAQs
- Runbooks
- SOPs
- Escalation procedures
- Vendor procedures

Knowledge articles should have:

- Owner
- Review date
- Version
- Applicability
- Approval

---

# 25. Monitoring & Alerting

Monitoring should cover:

- Platform availability
- Voice
- Digital
- Routing
- Architect
- Integrations
- APIs
- Data
- Security
- Reporting
- WFM
- Recording

Alerting should be actionable rather than simply generating noise.

---

# 26. Platform Health

Operational teams should monitor:

- Service availability
- Known incidents
- Service status
- API behaviour
- Integration health
- Configuration failures
- Authentication failures
- User-impacting events

---

# 27. Integration Monitoring

Monitor:

- API calls
- Authentication
- Token expiry
- Errors
- Timeouts
- Data failures
- Queue/backlog
- Integration availability
- External dependency health

---

# 28. Telephony Operations

Operational responsibilities include:

- Number management
- Number assignment
- Carrier management
- DID changes
- Call routing
- SIP/BYOC
- Emergency services
- Caller ID
- Call quality
- Telephony incidents
- Porting

---

# 29. Digital Operations

Where deployed:

- Email
- Chat
- Messaging
- Web messaging
- SMS
- Social channels
- Digital routing
- Digital queues
- Bots
- Digital integrations

---

# 30. Architect Operations

Operational administration includes:

- Flow changes
- Prompt changes
- Schedules
- Holidays
- Data Tables
- Data Actions
- Variables
- Error handling
- Version management
- Flow publication
- Rollback

Architect changes should be subject to change management.

---

# 31. Routing Administration

Manage:

- Queues
- Skills
- Languages
- Routing methods
- Bullseye configuration
- Priority
- Overflow
- Callback
- Business rules
- Agent assignment

Routing changes must be tested before production.

---

# 32. Identity & Access Operations

Operational responsibilities include:

- User lifecycle
- Roles
- Permissions
- Groups
- SSO
- MFA
- Identity provider
- Service accounts
- OAuth clients
- Access reviews
- Privileged access

---

# 33. WFM Operations

Where applicable:

- Forecasting
- Scheduling
- Adherence
- Time off
- Intraday management
- WFM administration
- User configuration
- Management units
- Operational reporting

---

# 34. Quality & Recording Operations

Where applicable:

- Recording configuration
- Retention
- Quality policies
- Evaluation forms
- Evaluations
- Calibration
- Coaching
- Recording access
- Recording incidents

---

# 35. Analytics & Reporting Operations

Manage:

- Dashboards
- Reports
- Scheduled reports
- Analytics views
- Performance metrics
- Historical reporting
- Data exports
- Reporting access

---

# 36. Data Operations

Data operations should cover:

- Data quality
- Data access
- Data exports
- Data retention
- Data reconciliation
- Data integrations
- Data warehouse feeds
- Data privacy

---

# 37. Security Operations

Security operations include:

- Access reviews
- Privileged access
- Security events
- Authentication
- OAuth clients
- Service accounts
- Suspicious activity
- Security incidents
- Configuration review

---

# 38. Compliance Operations

Where applicable, manage:

- Privacy
- Recording requirements
- Retention
- Audit
- Data access
- Data residency
- Regulatory requirements
- Evidence collection

---

# 39. Operational Dashboards

Dashboards should provide visibility into:

- Service availability
- Incidents
- Queue performance
- Agent performance
- Integration health
- Platform health
- Service requests
- Changes
- Problems
- Capacity
- SLA performance

---

# 40. SLA / OLA Management

Define:

- Service availability target
- Incident response
- Incident resolution
- Service request fulfilment
- Escalation targets
- Vendor response
- Business support

OLAs should define internal responsibilities between support teams.

---

# 41. KPI Management

KPIs should include appropriate measures such as:

- Availability
- Incident volume
- Mean time to acknowledge
- Mean time to resolve
- First-contact resolution
- Change success rate
- Change failure rate
- Service request completion
- Problem recurrence
- SLA compliance
- Integration availability
- Platform utilisation

---

# 42. Service Reporting

Operational reporting should be produced on an agreed cadence.

Typical reporting:

- Weekly operational summary
- Monthly service report
- Quarterly governance report
- Incident report
- Change report
- Problem report
- Capacity report
- Security report

---

# 43. Capacity Management

Assess:

- User growth
- Interaction volume
- Queue growth
- Digital volume
- API consumption
- Integration throughput
- Reporting volume
- Data growth
- Recording growth

Capacity planning should feed into the service roadmap.

---

# 44. Performance Management

Monitor:

- Agent performance
- Queue performance
- Routing
- API response
- Integration performance
- Reporting performance
- Digital performance

Performance issues should have defined thresholds and escalation paths.

---

# 45. Availability Management

Define:

- Availability targets
- Monitoring
- Incident thresholds
- Planned maintenance
- Unplanned outage process
- Vendor escalation
- Reporting

---

# 46. Resilience

Assess resilience across:

- Platform
- Telephony
- Network
- Identity
- Integrations
- Data
- Business processes

Document single points of failure.

---

# 47. Business Continuity

The business continuity strategy should define:

- Critical services
- Critical processes
- Recovery priorities
- Manual workarounds
- Communications
- Escalation
- Business owner
- Recovery expectations

---

# 48. Disaster Recovery

Where required, define:

- Disaster scenarios
- Recovery procedures
- Service dependencies
- Vendor responsibilities
- Integration dependencies
- Data dependencies
- Recovery testing
- Recovery evidence

Genesys Cloud service-level resilience and customer-managed dependency recovery must be clearly distinguished.

---

# 49. Maintenance Management

Define:

- Maintenance windows
- Change freezes
- Planned upgrades
- Integration maintenance
- Certificate renewal
- Credential rotation
- Carrier maintenance
- Network maintenance

---

# 50. Certificate & Credential Lifecycle

Where applicable manage:

- Certificates
- OAuth clients
- Client secrets
- API credentials
- Service accounts
- Integration credentials
- Expiry dates
- Rotation procedures

Operational ownership must be explicit.

---

# 51. API / OAuth Lifecycle

Manage:

- OAuth clients
- Scopes
- Client credentials
- Token lifecycle
- Secrets
- API consumers
- API usage
- Rate limits
- Application retirement

---

# 52. Licensing Management

Track:

- User licenses
- Feature licenses
- WFM
- Quality
- Digital
- Analytics
- Add-ons
- Usage
- Forecast
- Renewal

License management should identify unused or underutilised licences.

---

# 53. Vendor Management

Vendor management may include:

- Genesys
- Carrier
- Network providers
- Identity providers
- CRM providers
- Integration vendors
- WFM providers
- Recording/archive vendors

Track:

- Contracts
- SLAs
- Contacts
- Escalation
- Renewal
- Performance
- Open cases

---

# 54. Governance

Governance should include:

- Service review
- Change review
- Security review
- Architecture review
- Vendor review
- Performance review
- Capacity review
- Roadmap review
- Risk review

---

# 55. Audit

Operational audit evidence should include:

- Access reviews
- Change records
- Incident records
- Problem records
- Configuration history
- Security events
- Vendor cases
- Data access
- Compliance evidence

---

# 56. Operational Documentation

Documentation should include:

- Architecture
- Configuration
- Network
- Telephony
- Integrations
- APIs
- Security
- Data
- Support
- Administration
- Troubleshooting
- Recovery
- Change

---

# 57. Runbooks

Runbooks should cover repeatable operational procedures.

Examples:

- User provisioning
- User deprovisioning
- Queue changes
- Skill changes
- Routing changes
- Architect deployment
- Telephony changes
- Integration failure
- OAuth credential rotation
- Incident escalation
- Service outage
- Recovery

---

# 58. Standard Operating Procedures

SOPs should define:

- Purpose
- Scope
- Preconditions
- Procedure
- Validation
- Rollback
- Evidence
- Escalation
- Owner
- Review frequency

---

# 59. Training

Training should cover:

### Service Desk

- Basic troubleshooting
- Incident categorisation
- Escalation

### Administrators

- User management
- Queues
- Skills
- Routing
- Architect
- Reporting

### Technical Teams

- Integrations
- APIs
- Monitoring
- Troubleshooting

### Business

- Operational procedures
- Escalation
- Reporting
- Change process

---

# 60. Administrator Enablement

Administrators should demonstrate competency in:

- Genesys Cloud administration
- Users
- Roles
- Queues
- Skills
- Routing
- Architect
- Telephony
- Digital
- Analytics
- Reporting
- Integrations
- Troubleshooting

---

# 61. Knowledge Transfer

Knowledge transfer should include:

- Formal training
- Demonstrations
- Shadowing
- Reverse shadowing
- Runbook review
- Troubleshooting exercises
- Operational simulation

---

# 62. Operational Handover

The project must formally transfer:

- Platform ownership
- Support ownership
- Documentation
- Runbooks
- Configuration baseline
- Monitoring
- Service management
- Vendor contacts
- Open issues
- Risks
- Improvement backlog

---

# 63. Hypercare Exit

Hypercare exit should be based on measurable criteria.

Example:

```text
Critical Defects = 0
       +
Major Incidents = 0
       +
Stable Service Performance
       +
Support Team Ready
       +
Documentation Complete
       +
Monitoring Operational
       +
Business Acceptance
       ↓
HYPERCARE EXIT
```

---

# 64. BAU Transition

BAU transition should confirm:

- Support teams are operational.
- Escalation paths work.
- Monitoring is active.
- Knowledge is available.
- Documentation is complete.
- Change process is active.
- Service reporting is active.
- Vendor management is transferred.

---

# 65. Continual Service Improvement

The service should maintain a continual improvement backlog.

Potential improvement sources:

- Incidents
- Problems
- User feedback
- Agent feedback
- Business changes
- Platform releases
- New Genesys capabilities
- Analytics
- Performance
- Cost
- Automation opportunities

---

# 66. Optimisation Backlog

Backlog items should include:

- Problem
- Opportunity
- Business benefit
- Technical benefit
- Complexity
- Effort
- Priority
- Dependency
- Owner
- Target release

---

# 67. Operational Governance Cadence

A typical cadence:

```text
Daily
 └── Operational monitoring

Weekly
 ├── Incident review
 ├── Change review
 └── Operational issues

Monthly
 ├── Service review
 ├── KPI review
 ├── Capacity review
 └── Vendor review

Quarterly
 ├── Governance
 ├── Architecture
 ├── Security
 ├── Roadmap
 └── Continual improvement
```

---

# 68. Cross-Domain Dependencies

| Domain | Operational Dependency |
|---|---|
| 01 — Core Platform | Platform administration |
| 02 — Identity & Access | User and access operations |
| 03 — Voice & Telephony | Telephony support |
| 04 — ACD Routing | Routing administration |
| 05 — Architect | Flow administration |
| 06 — Digital | Digital support |
| 07 — WFM | WFM operations |
| 08 — Data & Integrations | Integration support |
| 09 — Analytics | Reporting operations |
| 10 — Quality | Recording / quality operations |
| 11 — Security | Security operations |
| 12 — Testing | Operational validation |
| 13 — Migration | Transition from legacy |
| 14 — Operations | Current domain |
| 15 — Optimisation | Continual improvement |

---

# 69. Layer 1 Mapping

| Layer 1 Phase | Operations Activities |
|---|---|
| Phase 1 — Initiation | Define operational ownership |
| Phase 2 — Discovery | Assess current support model |
| Phase 3 — Requirements | Define operational requirements |
| Phase 4 — Architecture | Design operating model |
| Phase 5 — Platform Foundation | Establish operational foundations |
| Phase 6 — Solution Build | Build administration and monitoring |
| Phase 7 — Integration & Migration | Establish operational integration support |
| Phase 8 — Testing | Test operational procedures |
| Phase 9 — Operational Readiness | Complete BAU readiness |
| Phase 10 — Production Deployment | Activate production support |
| Phase 11 — Hypercare | Stabilise service |
| Phase 12 — BAU Handover | Complete operational transition |

---

# 70. Operational Risk Management

| Risk | Impact | Mitigation |
|---|---|---|
| No clear service owner | High | Establish ownership early |
| Insufficient support capability | Critical | Training and knowledge transfer |
| Poor incident process | High | Define ITSM procedures |
| Inadequate monitoring | High | Build operational monitoring |
| Configuration drift | High | Configuration baseline |
| Uncontrolled changes | Critical | Change management |
| Vendor escalation failure | High | Define escalation process |
| Credential expiry | Critical | Lifecycle management |
| Poor documentation | High | Documentation gate |
| No operational metrics | Medium | KPI framework |
| Insufficient capacity | High | Capacity management |
| Major incident confusion | Critical | Major incident process |
| Poor BAU handover | Critical | Formal transition |
| Excessive technical debt | High | CSI backlog |
| Legacy dependency | High | Transition plan |

---

# 71. Operational Critical Path

```text
Operating Model
      ↓
Service Ownership
      ↓
Support Model
      ↓
Operational Processes
      ↓
Monitoring
      ↓
Runbooks / SOPs
      ↓
Training
      ↓
Knowledge Transfer
      ↓
Operational Simulation
      ↓
BAU Readiness
      ↓
Production
      ↓
Hypercare
      ↓
BAU Handover
      ↓
Continual Improvement
```

---

# 72. Operational Artefacts

The project should produce:

- Operating model
- Service ownership matrix
- Support model
- RACI
- Service desk procedures
- Incident process
- Major incident process
- Problem process
- Request process
- Change process
- Release process
- Configuration management process
- Monitoring strategy
- Alerting strategy
- SLA/OLA matrix
- KPI framework
- Service reporting framework
- Capacity management plan
- Availability plan
- Business continuity plan
- Disaster recovery plan where applicable
- Vendor escalation matrix
- Knowledge base
- Runbooks
- SOPs
- Administrator guide
- Support guide
- Troubleshooting guide
- Operational dashboard
- Training material
- Knowledge transfer record
- BAU handover document
- Hypercare exit report
- Continual improvement backlog

---

# 73. Support RACI

| Activity | Service Desk | L2 | L3 | Business | Vendor |
|---|---|---|---|---|---|
| User Login | R | A | C | I | I |
| User Provisioning | R | A | C | C | I |
| Queue Change | C | R/A | C | C | I |
| Routing Issue | C | R | A | C | C |
| Architect Issue | C | R | A | C | C |
| Telephony Issue | C | R | A | I | C |
| Integration Issue | C | R | A | I | C |
| Platform Incident | R | R | A | I | C |
| Major Incident | C | R | R | A | C |
| Platform Defect | I | C | R | I | A |

---

# 74. Operational Metrics

Recommended metrics include:

```text
Service Availability
Incident Volume
Major Incidents
MTTA
MTTR
First Contact Resolution
SLA Compliance
Change Success Rate
Change Failure Rate
Problem Recurrence
Service Request SLA
Configuration Drift
Integration Availability
API Error Rate
Telephony Availability
Digital Availability
User Support Volume
Knowledge Article Usage
Vendor Case Volume
Vendor Resolution Time
```

---

# 75. Service Review

The monthly service review should examine:

- Service availability
- Incidents
- Problems
- Changes
- Service requests
- Performance
- Capacity
- Security
- Compliance
- Vendor performance
- Risks
- Improvement backlog

---

# 76. Operational Dashboard

A minimum operational dashboard should show:

| Area | Metrics |
|---|---|
| Service | Availability, incidents |
| Support | Open tickets, SLA |
| Change | Planned, successful, failed |
| Problem | Open problems |
| Telephony | Availability, failures |
| Digital | Channel health |
| Integrations | Success/error rate |
| Security | Access/security events |
| Capacity | Growth/utilisation |
| Vendor | Open cases |

---

# 77. Operational Change Pipeline

```text
Business Requirement
        ↓
Change Request
        ↓
Impact Assessment
        ↓
Technical Design
        ↓
Testing
        ↓
Approval
        ↓
Release
        ↓
Validation
        ↓
Monitoring
        ↓
Closure
```

---

# 78. Operational Release Pipeline

Where appropriate:

```text
Development
     ↓
Code / Configuration Review
     ↓
Automated Validation
     ↓
SIT
     ↓
UAT
     ↓
Approval
     ↓
Production
     ↓
Validation
     ↓
Monitoring
     ↓
Release Closure
```

---

# 79. Operational Security Review

Periodic review should assess:

- Users
- Roles
- Privileges
- OAuth clients
- Service accounts
- API scopes
- Integrations
- Certificates
- Credentials
- Security events
- Audit evidence

---

# 80. Operational Configuration Baseline

The baseline should capture:

```text
Organisation
Divisions
Users
Roles
Groups
Queues
Skills
Languages
Routing
Architect
Data Tables
Data Actions
Scripts
Schedules
Calendars
Telephony
Digital
Integrations
APIs
WFM
Quality
Recording
Analytics
Reporting
Security
```

---

# 81. Operational Testing

The project should test:

- Incident procedures
- Escalation
- Monitoring
- Alerting
- Runbooks
- Change process
- Rollback
- User administration
- Queue administration
- Routing changes
- Architect deployment
- Telephony support
- Integration support
- Major incident process

---

# 82. Operational Simulation

A practical simulation should include scenarios such as:

1. Platform incident.
2. Queue routing failure.
3. Architect failure.
4. Telephony outage.
5. Integration failure.
6. OAuth credential expiry.
7. User access failure.
8. Digital channel failure.
9. Reporting issue.
10. Security incident.

The support team should demonstrate the complete escalation and resolution process.

---

# 83. Hypercare Model

Hypercare should include:

- Increased monitoring
- Daily operational review
- Rapid escalation
- Dedicated project resources
- Vendor engagement
- Incident trend analysis
- Business feedback
- Defect prioritisation

---

# 84. Hypercare Exit Criteria

```text
No Critical Open Defects
No Unresolved Major Incidents
Stable Telephony
Stable Routing
Stable Integrations
Stable Digital Channels
Support Team Operating Independently
Documentation Complete
Monitoring Active
Service Reporting Active
Business Acceptance
```

---

# 85. BAU Handover Checklist

```text
[ ] Service owner assigned
[ ] Support model approved
[ ] Service desk trained
[ ] L2 trained
[ ] L3 identified
[ ] Vendor escalation defined
[ ] Incident process active
[ ] Major incident process active
[ ] Problem process active
[ ] Change process active
[ ] Request process active
[ ] Monitoring active
[ ] Alerting active
[ ] Dashboards active
[ ] Runbooks complete
[ ] SOPs complete
[ ] Knowledge base complete
[ ] Training complete
[ ] Operational simulation complete
[ ] SLA/OLA defined
[ ] KPI reporting active
[ ] Vendor contacts transferred
[ ] Configuration baseline established
[ ] Security process active
[ ] Compliance process active
[ ] Hypercare exit criteria met
```

---

# 86. Continual Improvement Framework

```text
Measure
   ↓
Identify
   ↓
Assess
   ↓
Prioritise
   ↓
Plan
   ↓
Implement
   ↓
Validate
   ↓
Measure Again
```

Improvement should be driven by evidence.

---

# 87. Operational Backlog

Each improvement should capture:

| Attribute | Description |
|---|---|
| ID | Unique identifier |
| Problem | Current issue |
| Opportunity | Proposed improvement |
| Benefit | Business/technical benefit |
| Priority | Priority |
| Effort | Estimated effort |
| Owner | Responsible owner |
| Dependency | Dependencies |
| Target | Target release |
| Status | Backlog / Planned / In Progress / Complete |

---

# 88. Operational Effort Considerations

Effort should account for:

### Organisation Size

- Number of users
- Number of sites
- Number of business units
- Number of queues

### Complexity

- Number of integrations
- Number of Architect flows
- Number of channels
- Number of customisations

### Support

- Number of support teams
- L1/L2/L3 model
- Service desk maturity
- Vendor dependencies

### Governance

- Regulatory requirements
- Change controls
- Security
- Audit
- Reporting

### Operational Readiness

- Training
- Documentation
- Runbooks
- Simulation
- Knowledge transfer

---

# 89. Operational Task Catalogue

The eventual implementation workbook should include at least the following tasks:

```text
OPS-014-001  Define operational strategy
OPS-014-002  Define service ownership
OPS-014-003  Define Genesys Cloud service owner
OPS-014-004  Define platform owner
OPS-014-005  Define business owner
OPS-014-006  Define operating model
OPS-014-007  Define support organisation
OPS-014-008  Define L1 support
OPS-014-009  Define L2 support
OPS-014-010  Define L3 support
OPS-014-011  Define vendor escalation
OPS-014-012  Define service desk integration
OPS-014-013  Define incident process
OPS-014-014  Define major incident process
OPS-014-015  Define problem process
OPS-014-016  Define service request process
OPS-014-017  Define change process
OPS-014-018  Define release process
OPS-014-019  Define configuration management
OPS-014-020  Define asset management
OPS-014-021  Define knowledge management
OPS-014-022  Define monitoring strategy
OPS-014-023  Define alerting strategy
OPS-014-024  Configure platform monitoring
OPS-014-025  Configure integration monitoring
OPS-014-026  Configure operational dashboards
OPS-014-027  Define telephony support
OPS-014-028  Define digital support
OPS-014-029  Define Architect support
OPS-014-030  Define routing administration
OPS-014-031  Define identity administration
OPS-014-032  Define WFM support
OPS-014-033  Define quality support
OPS-014-034  Define recording support
OPS-014-035  Define analytics support
OPS-014-036  Define reporting support
OPS-014-037  Define data operations
OPS-014-038  Define security operations
OPS-014-039  Define compliance operations
OPS-014-040  Define SLA framework
OPS-014-041  Define OLA framework
OPS-014-042  Define KPI framework
OPS-014-043  Define service reporting
OPS-014-044  Define capacity management
OPS-014-045  Define performance management
OPS-014-046  Define availability management
OPS-014-047  Define resilience strategy
OPS-014-048  Define business continuity
OPS-014-049  Define disaster recovery where required
OPS-014-050  Define maintenance management
OPS-014-051  Define certificate lifecycle
OPS-014-052  Define credential lifecycle
OPS-014-053  Define OAuth lifecycle
OPS-014-054  Define API lifecycle
OPS-014-055  Define licensing management
OPS-014-056  Define vendor management
OPS-014-057  Define governance cadence
OPS-014-058  Define audit requirements
OPS-014-059  Develop operational documentation
OPS-014-060  Develop operational runbooks
OPS-014-061  Develop standard operating procedures
OPS-014-062  Develop service desk procedures
OPS-014-063  Develop incident procedures
OPS-014-064  Develop major incident procedures
OPS-014-065  Develop problem management procedures
OPS-014-066  Develop change procedures
OPS-014-067  Develop release procedures
OPS-014-068  Develop configuration procedures
OPS-014-069  Develop telephony procedures
OPS-014-070  Develop Architect procedures
OPS-014-071  Develop routing procedures
OPS-014-072  Develop user administration procedures
OPS-014-073  Develop integration troubleshooting procedures
OPS-014-074  Develop API troubleshooting procedures
OPS-014-075  Develop security procedures
OPS-014-076  Develop compliance procedures
OPS-014-077  Develop service reporting
OPS-014-078  Develop operational dashboards
OPS-014-079  Develop knowledge base
OPS-014-080  Train service desk
OPS-014-081  Train L2 support
OPS-014-082  Train L3 support
OPS-014-083  Train Genesys administrators
OPS-014-084  Train business administrators
OPS-014-085  Execute knowledge transfer
OPS-014-086  Execute administrator enablement
OPS-014-087  Execute support simulation
OPS-014-088  Execute incident simulation
OPS-014-089  Execute major incident simulation
OPS-014-090  Validate monitoring
OPS-014-091  Validate alerting
OPS-014-092  Validate operational dashboards
OPS-014-093  Validate service desk integration
OPS-014-094  Validate escalation paths
OPS-014-095  Validate vendor escalation
OPS-014-096  Validate change process
OPS-014-097  Validate rollback procedures
OPS-014-098  Validate runbooks
OPS-014-099  Validate SOPs
OPS-014-100  Validate operational readiness
OPS-014-101  Establish BAU support
OPS-014-102  Activate hypercare
OPS-014-103  Monitor production service
OPS-014-104  Review production incidents
OPS-014-105  Review production performance
OPS-014-106  Review integration health
OPS-014-107  Review telephony health
OPS-014-108  Review digital health
OPS-014-109  Review routing performance
OPS-014-110  Review reporting
OPS-014-111  Review service KPIs
OPS-014-112  Review SLA performance
OPS-014-113  Review vendor performance
OPS-014-114  Manage operational risks
OPS-014-115  Manage operational defects
OPS-014-116  Manage operational problems
OPS-014-117  Establish continual improvement backlog
OPS-014-118  Prioritise optimisation backlog
OPS-014-119  Execute hypercare exit assessment
OPS-014-120  Complete BAU handover
OPS-014-121  Transfer service ownership
OPS-014-122  Transfer operational documentation
OPS-014-123  Transfer monitoring ownership
OPS-014-124  Transfer vendor management
OPS-014-125  Close project operational actions
OPS-014-126  Conduct operational lessons learned
OPS-014-127  Update deployment methodology
```

---

# 90. Detailed Task Attributes

Every eventual spreadsheet task should contain:

| Field | Description |
|---|---|
| Task ID | Unique task identifier |
| Layer | Layer 2 |
| Domain | 14 |
| Phase | Layer 1 phase |
| Workstream | Operations / Support |
| Capability | Capability area |
| Task | Atomic task |
| Description | Detailed implementation activity |
| Classification | Required / Conditional / Optional |
| Dependencies | Predecessor tasks |
| Role | Primary owner |
| Customer Responsibility | Customer activity |
| Environment | DEV / SIT / UAT / PROD / BAU |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Deliverable | Output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |
| Evidence | Evidence required |
| Approval | Approver |

---

# 91. Operational Task Sequencing

The operational workstream should generally follow:

```text
Operating Model
      ↓
Ownership
      ↓
Support Model
      ↓
Service Management Processes
      ↓
Monitoring
      ↓
Documentation
      ↓
Training
      ↓
Knowledge Transfer
      ↓
Operational Simulation
      ↓
Readiness
      ↓
Production
      ↓
Hypercare
      ↓
BAU Handover
      ↓
Continual Improvement
```

---

# 92. Operational Dependencies

The operational workstream depends on:

- Solution architecture
- Genesys Cloud configuration
- Identity configuration
- Telephony configuration
- Routing
- Architect
- Digital
- Integrations
- Analytics
- Security
- Migration
- Testing
- Business acceptance

---

# 93. Operational Go / No-Go Criteria

BAU transition should not proceed unless:

```text
Support Model Approved
        +
Service Owner Assigned
        +
L1/L2/L3 Defined
        +
Vendor Escalation Defined
        +
Monitoring Active
        +
Runbooks Complete
        +
SOPs Complete
        +
Training Complete
        +
Operational Simulation Passed
        +
Service Reporting Active
        +
Business Acceptance
        ↓
      GO
```

---

# 94. Operational Acceptance Criteria

The operational model is accepted when:

### People

- Support teams trained.
- Service owner assigned.
- Escalation paths established.

### Process

- Incident process operational.
- Change process operational.
- Problem process operational.
- Request process operational.

### Technology

- Monitoring active.
- Alerting active.
- Dashboards active.
- Configuration baseline established.

### Documentation

- Runbooks complete.
- SOPs complete.
- Knowledge base complete.

### Governance

- SLAs defined.
- KPIs defined.
- Service reporting established.
- Vendor escalation established.

---

# 95. Definition of Done

Domain 14 is complete when:

1. Operating model is approved.
2. Service owner is assigned.
3. Platform owner is assigned.
4. Business ownership is assigned.
5. L1 support is defined.
6. L2 support is defined.
7. L3 support is defined where required.
8. Vendor escalation is defined.
9. Service desk process is operational.
10. Incident management is operational.
11. Major incident management is operational.
12. Problem management is operational.
13. Service request management is operational.
14. Change management is operational.
15. Release management is operational.
16. Configuration management is operational.
17. Knowledge management is operational.
18. Monitoring is active.
19. Alerting is active.
20. Operational dashboards are available.
21. Telephony support is established.
22. Digital support is established where applicable.
23. Architect support is established.
24. Routing support is established.
25. Identity support is established.
26. WFM support is established where applicable.
27. Quality support is established where applicable.
28. Recording support is established where applicable.
29. Analytics and reporting support is established.
30. Data operations are established.
31. Security operations are established.
32. Compliance operations are established.
33. SLA/OLA framework is approved.
34. KPI framework is approved.
35. Service reporting is operational.
36. Capacity management is established.
37. Availability management is established.
38. Resilience requirements are documented.
39. Business continuity requirements are documented.
40. Disaster recovery requirements are documented where applicable.
41. Maintenance procedures are established.
42. Credential lifecycle is established where applicable.
43. OAuth/API lifecycle is established where applicable.
44. Licensing management is established.
45. Vendor management is established.
46. Governance cadence is active.
47. Audit requirements are defined.
48. Operational documentation is complete.
49. Runbooks are complete.
50. SOPs are complete.
51. Training is complete.
52. Administrator enablement is complete.
53. Knowledge transfer is complete.
54. Operational simulation is complete.
55. BAU support is activated.
56. Hypercare is active.
57. Hypercare exit criteria are met.
58. Operational ownership is transferred.
59. Continual improvement backlog is established.
60. Operational closure is complete.

---

# 96. Domain Gate

```text
OPERATING MODEL
       +
SERVICE OWNERSHIP
       +
SUPPORT MODEL
       +
SERVICE MANAGEMENT
       +
MONITORING
       +
DOCUMENTATION
       +
TRAINING
       +
KNOWLEDGE TRANSFER
       +
OPERATIONAL SIMULATION
       ↓
BAU READINESS
       ↓
PRODUCTION
       ↓
HYPERCARE
       ↓
BAU HANDOVER
       ↓
CONTINUAL SERVICE IMPROVEMENT
```

---

# 97. Phase Completion

**Layer 2.14 — Operations, Support & Service Management is complete at capability-catalogue level.**

The domain provides the operational framework required to support a Genesys Cloud deployment throughout its production lifecycle.

The eventual implementation workbook will convert the capability catalogue into atomic tasks with:

- Task ID
- Layer
- Phase
- Workstream
- Capability
- Task
- Description
- Classification
- Dependencies
- Role
- Customer responsibility
- Environment
- Effort
- Duration
- Deliverable
- Acceptance criteria
- Critical path indicator
- Evidence
- Approval

---

# 98. Next Domain

The next capability domain is:

**15 — Optimisation, Continuous Improvement & Platform Evolution**

This domain should complete Layer 2 by defining the processes used to continuously improve, optimise, expand and evolve the Genesys Cloud platform after initial deployment and BAU transition.

---

# 99. Domain Completion Gate

```text
OPERATING MODEL
        +
SERVICE OWNERSHIP
        +
SUPPORT MODEL
        +
SERVICE MANAGEMENT
        +
MONITORING
        +
OPERATIONAL DOCUMENTATION
        +
TRAINING
        +
KNOWLEDGE TRANSFER
        +
BAU READINESS
        +
HYPERCARE
        +
HANDOVER
        ↓
OPERATIONS ESTABLISHED
        ↓
CONTINUAL IMPROVEMENT
```