# Phase 04 — Solution Architecture & Detailed Design

## 1. Purpose

Translate the approved requirements from Phase 03 — Requirements & Solution Definition into a complete future-state Genesys Cloud solution architecture and detailed technical design.

The objective is to define **how the Genesys Cloud solution will be structured, integrated, secured, configured, operated, and supported** before implementation begins.

This phase establishes the technical blueprint that will drive:

- Platform foundation
- Feature configuration
- Telephony implementation
- Routing configuration
- Architect development
- Digital-channel implementation
- WEM configuration
- Integration development
- Data migration
- Testing
- Deployment
- Operational handover

---

# 2. Phase Objective

By the end of Phase 04:

- Future-state architecture is defined.
- Genesys Cloud organisation architecture is defined.
- Environment strategy is defined.
- Division strategy is defined.
- Identity and security architecture is defined.
- User and role architecture is defined.
- Telephony architecture is defined.
- Number strategy is defined.
- ACD and routing architecture is defined.
- Queue, skill and language architecture is defined.
- Architect / IVR architecture is defined.
- Digital-channel architecture is defined.
- Email architecture is defined.
- Outbound architecture is defined where applicable.
- WEM architecture is defined where applicable.
- Recording architecture is defined.
- Analytics and reporting architecture is defined.
- CRM and integration architecture is defined.
- API and Data Action architecture is defined.
- Data migration architecture is defined.
- Network and endpoint architecture is defined.
- Security and compliance architecture is defined.
- Operational architecture is defined.
- Disaster recovery and business continuity requirements are addressed.
- Detailed configuration designs are produced.
- Build dependencies are identified.
- Design decisions are documented.
- The solution is approved for implementation.

---

# 3. Architecture Principles

The following principles should guide the design.

## 3.1 Requirements Driven

Every significant architecture decision should trace back to an approved requirement.

## 3.2 Standard Before Custom

Use native Genesys Cloud functionality wherever practical before introducing:

- Custom development
- Middleware
- External services
- Complex integrations
- Custom APIs

## 3.3 Least Privilege

Users, applications, service accounts and integrations should receive only the permissions required to perform their functions.

## 3.4 Security by Design

Security, privacy, authentication, authorisation and data protection must be designed into the solution rather than added after configuration.

## 3.5 Automation Where Practical

Configuration should be designed for repeatability and automation wherever appropriate.

Potential automation mechanisms include:

- Genesys Cloud APIs
- Terraform
- CI/CD
- Configuration-as-code
- Data-driven configuration
- Automated validation

## 3.6 Operational Simplicity

The solution should be maintainable by the customer's BAU team.

## 3.7 Scalability

The architecture should accommodate expected future:

- Users
- Contact volumes
- Channels
- Sites
- Integrations
- Business units
- Feature adoption

## 3.8 Traceability

Architecture components should be traceable to:

**Requirement → Design → Build → Test → Acceptance**

---

# 4. Architecture Workstreams

The solution architecture phase is structured into the following workstreams:

### 04.01 Solution Architecture
### 04.02 Genesys Cloud Organisation Architecture
### 04.03 Environment Strategy
### 04.04 Division Architecture
### 04.05 Identity & Security Architecture
### 04.06 User / Role / Permission Architecture
### 04.07 Voice & Telephony Architecture
### 04.08 Number & Dial Plan Architecture
### 04.09 ACD & Routing Architecture
### 04.10 Queue / Skill / Language Architecture
### 04.11 Architect / IVR Architecture
### 04.12 Digital Channel Architecture
### 04.13 Email Architecture
### 04.14 Outbound Architecture
### 04.15 Workforce Engagement Architecture
### 04.16 Recording Architecture
### 04.17 Analytics & Reporting Architecture
### 04.18 CRM & Integration Architecture
### 04.19 API / Data Action Architecture
### 04.20 Data & Migration Architecture
### 04.21 Network & Endpoint Architecture
### 04.22 Security & Compliance Architecture
### 04.23 Operational Architecture
### 04.24 Disaster Recovery & Business Continuity
### 04.25 Build Strategy & Dependencies
### 04.26 Design Review & Approval

---

# 5. Solution Architecture

Create the overall future-state architecture.

## Activities

1. Review approved requirements.
2. Review requirements traceability.
3. Identify solution components.
4. Identify platform boundaries.
5. Identify external systems.
6. Define integration boundaries.
7. Define data flows.
8. Define trust boundaries.
9. Define security boundaries.
10. Define customer interaction channels.
11. Define agent interaction channels.
12. Define administrative boundaries.
13. Define operational boundaries.
14. Define high-level dependencies.

## Architecture Views

Produce, where applicable:

- Context diagram
- Logical architecture
- Physical / deployment architecture
- Integration architecture
- Security architecture
- Data-flow architecture
- Contact-flow architecture
- Operational architecture

## Primary Output

**Future-State Solution Architecture**

---

# 6. Genesys Cloud Organisation Architecture

Define the structure of the Genesys Cloud organisation.

## Design

Determine:

- Organisation
- Region
- Organisation naming
- Organisation settings
- Business units
- Sites
- Locations
- Divisions
- Groups
- Teams
- Queues
- Users

## Consider

- Business segmentation
- Security boundaries
- Administrative boundaries
- Reporting boundaries
- Data access
- Delegated administration
- Future scalability

## Output

**Genesys Cloud Organisation Design**

---

# 7. Environment Strategy

Define how environments will be used throughout the lifecycle.

Potential model:

```text
Development
     ↓
System Integration Testing
     ↓
User Acceptance Testing
     ↓
Production
```

Depending on project requirements, determine:

- Number of organisations
- Development strategy
- Configuration promotion strategy
- Testing strategy
- Production isolation
- Data separation
- Integration endpoints
- Environment-specific credentials
- Environment-specific URLs
- Environment-specific configuration

## Define

- Environment purpose
- Owner
- Access
- Configuration approach
- Data
- Integrations
- Testing
- Promotion process

---

# 8. Division Architecture

Define how divisions will be used to control access and administration.

## Design

Determine:

- Division structure
- Objects assigned to divisions
- Administrative boundaries
- User access
- Role access
- Reporting implications
- Integration implications

## Consider

Divisions should not be created simply because organisational departments exist.

They should have a clear security, administrative, or data-access purpose.

---

# 9. Identity & Security Architecture

Define the future-state identity model.

## Identity

Design:

- Identity provider
- SSO
- SAML / OIDC where applicable
- MFA
- SCIM
- User provisioning
- Group provisioning
- Deprovisioning
- Authentication policies
- Conditional access

## Application Identity

Design:

- OAuth clients
- Service accounts
- API authentication
- Integration credentials
- Secrets management
- Token lifecycle

## Security

Define:

- Authentication boundaries
- Authorisation model
- Privileged access
- Administrative access
- Audit requirements
- Logging
- Security monitoring

## Output

**Identity & Security Architecture**

---

# 10. User / Role / Permission Architecture

Define the Genesys Cloud RBAC model.

## Design

Map:

**Business Role → Genesys Role → Permissions → Division → Group**

Potential roles include:

- Agent
- Supervisor
- Manager
- Administrator
- WFM user
- QM user
- Reporting user
- Developer
- Integration service account

## Define

- Roles
- Permissions
- Groups
- Teams
- Divisions
- Licence assignments
- Administrative boundaries

## Output

**RBAC / Permission Matrix**

---

# 11. Voice & Telephony Architecture

Define the complete future-state voice architecture.

## Design Options

Evaluate where applicable:

- Genesys Cloud Voice
- BYOC Cloud
- BYOC Premises
- Hybrid models
- Existing PBX integration

## Design

Define:

- Carrier
- SIP
- PSTN
- Trunks
- Sites
- Edges
- Phone configuration
- Number management
- Outbound routes
- Dial plans
- Emergency services
- Caller ID
- Call recording
- Failover

## Network

Define:

- SIP paths
- RTP paths
- NAT
- Firewall
- QoS
- Bandwidth
- Remote-user connectivity

## Output

**Future-State Telephony Architecture**

---

# 12. Number & Dial Plan Architecture

Design the number strategy.

## Number Categories

- DID
- Toll-free
- Service numbers
- Emergency
- Internal
- Outbound caller ID
- International

## Define

- Number ownership
- Number allocation
- Porting
- Routing
- Number pools
- Caller ID
- Dial plans
- Outbound routes
- Emergency calling

## Output

**Number & Dial Plan Design**

---

# 13. ACD & Routing Architecture

Define how Genesys Cloud will route interactions.

## Design

Determine:

- Queue architecture
- Routing method
- Skills
- Languages
- Priority
- Bullseye routing
- Preferred agent routing
- VIP routing
- Overflow
- Escalation
- Callback
- Service levels
- Agent utilisation

## Routing Hierarchy

Document:

```text
Interaction
    ↓
Channel
    ↓
Queue
    ↓
Priority
    ↓
Skills / Language
    ↓
Routing Method
    ↓
Agent Selection
    ↓
Agent
```

## Output

**ACD / Routing Architecture**

---

# 14. Queue / Skill / Language Architecture

Define the standard configuration model.

## Queue Design

For each queue:

- Queue ID
- Queue name
- Purpose
- Division
- Channel
- Agents
- Skills
- Languages
- Priority
- Routing method
- SLA
- Overflow
- Escalation
- Operating hours

## Skill Design

Define:

- Skill naming convention
- Skill categories
- Skill ownership
- Skill assignment
- Skill proficiency
- Skill lifecycle

## Language Design

Define:

- Supported languages
- Language naming
- Agent proficiency
- Routing rules
- Queue requirements

---

# 15. Architect / IVR Architecture

Define the future-state customer interaction architecture.

## Design

Create:

- Call-flow architecture
- IVR hierarchy
- Menu architecture
- Reusable components
- Common flows
- Data lookup architecture
- Error handling
- Failover
- Authentication
- Self-service
- Queue selection
- Callback
- Transfer strategy

## Architect Standards

Define:

- Flow naming
- Variable naming
- Prompt naming
- Reusable logic
- Error handling standards
- Logging
- Versioning
- Testing approach

## Flow Architecture

```text
Inbound Number
      ↓
Entry Flow
      ↓
Customer Identification
      ↓
Authentication
      ↓
Business Logic
      ↓
Self-Service / Menu
      ↓
Data Lookup
      ↓
Routing
      ↓
Queue
      ↓
Agent
```

## Output

**Architect / IVR Solution Design**

---

# 16. Digital Channel Architecture

Define the future-state digital architecture.

## Channels

Potential channels:

- Web messaging
- Web chat
- SMS
- WhatsApp
- Social messaging
- Mobile applications
- Bots

## Design

For each channel define:

- Entry point
- Authentication
- Customer identification
- Queue
- Skills
- Routing
- Priority
- SLA
- Bot integration
- Agent escalation
- Transfer
- Reporting
- Retention
- Integration

---

# 17. Email Architecture

Design:

- Email addresses
- Email domains
- Queues
- Routing
- Auto-response
- Templates
- SLA
- Escalation
- Attachments
- Security
- Retention
- Reporting

---

# 18. Outbound Architecture

Where applicable, define:

- Campaign architecture
- Campaign types
- Contact lists
- Data sources
- Campaign schedules
- Calling modes
- Caller ID
- DNC
- Dispositions
- Wrap-up codes
- Retry rules
- Agent allocation
- Compliance
- Reporting

---

# 19. Workforce Engagement Architecture

Where applicable, design:

## WFM

- Management units
- Service goals
- Planning groups
- Forecasting
- Scheduling
- Staffing
- Intraday management
- Adherence

## QM

- Evaluation forms
- Evaluation questions
- Scoring
- Sampling
- Calibration
- Coaching

## Performance

- Metrics
- Scorecards
- Targets
- Dashboards
- Coaching

---

# 20. Recording Architecture

Define:

- Recording policies
- Recording scope
- Recording retention
- Recording access
- Encryption
- Screen recording
- Secure pause
- PCI handling
- Quality workflows
- Legal requirements
- Data retention

---

# 21. Analytics & Reporting Architecture

Define the reporting model.

## Architecture

Determine:

- Real-time reporting
- Historical reporting
- Dashboards
- Views
- Exports
- Data access
- Reporting roles
- Data retention
- External reporting
- BI integration

## Reporting Model

```text
Genesys Cloud
      │
      ├── Real-Time Analytics
      │
      ├── Historical Analytics
      │
      ├── Dashboards
      │
      └── External BI / Data Platform
```

---

# 22. CRM & Integration Architecture

Design the complete integration landscape.

## For Each Integration

Define:

- Source
- Target
- Trigger
- Direction
- Data
- API
- Authentication
- Middleware
- Transformation
- Error handling
- Retry
- Timeout
- Logging
- Monitoring
- Security
- Availability

## Integration Patterns

Evaluate:

- Data Actions
- REST APIs
- Webhooks
- Event streams
- Middleware
- Serverless
- CRM integrations
- Custom applications

## Output

**Integration Architecture Diagram**

---

# 23. API / Data Action Architecture

Define the technical approach for Genesys Cloud API integrations.

## Design

Determine:

- OAuth clients
- Scopes
- Authentication
- API endpoints
- Data Actions
- Contracts
- Input schema
- Output schema
- Error handling
- Timeout
- Retry
- Logging
- Monitoring
- Rate-limit considerations

## Data Action Design

Each Data Action should define:

- Name
- Purpose
- Input contract
- Output contract
- Endpoint
- Authentication
- Request
- Response
- Success conditions
- Error conditions
- Timeout
- Retry

---

# 24. Data & Migration Architecture

Define the strategy for data migration.

## Migration Types

- User migration
- Configuration migration
- Number migration
- Contact migration
- Campaign migration
- Historical data migration
- Knowledge migration

## Define

- Source
- Target
- Transformation
- Validation
- Migration tooling
- Migration sequence
- Cutover requirements
- Rollback
- Reconciliation

## Output

**Migration Strategy & Data Mapping**

---

# 25. Network & Endpoint Architecture

Define the technical endpoint architecture.

## Design

- Network connectivity
- Internet
- WAN
- LAN
- SD-WAN
- Firewall
- Proxy
- DNS
- QoS
- NAT
- WebRTC
- SIP
- RTP
- Browser
- OS
- Headsets
- Physical phones
- Remote workers

## Voice Quality

Define:

- Latency thresholds
- Jitter thresholds
- Packet loss thresholds
- Bandwidth
- QoS
- Monitoring

---

# 26. Security & Compliance Architecture

Map requirements to technical controls.

## Design

Address:

- Authentication
- Authorisation
- SSO
- MFA
- SCIM
- OAuth
- API security
- Encryption
- Data residency
- PII
- PCI
- Recording
- Retention
- Audit
- Logging
- Monitoring
- Privileged access

## Output

**Security & Compliance Architecture**

---

# 27. Operational Architecture

Define how the platform will be operated after implementation.

## Design

Determine:

- Administration model
- Support model
- Service desk
- Monitoring
- Alerting
- Incident management
- Problem management
- Change management
- Release management
- Configuration management
- Documentation
- Runbooks
- Escalation
- Vendor support

## BAU Ownership

Map each major Genesys capability to:

- Business owner
- Technical owner
- BAU support owner
- Escalation owner

---

# 28. Disaster Recovery & Business Continuity

Define how the solution responds to failures.

## Scenarios

Consider:

- Genesys service disruption
- Carrier failure
- Network failure
- Site failure
- Identity provider failure
- CRM failure
- Integration failure
- Data Action failure
- Agent endpoint failure
- Internet outage
- Power outage
- Third-party outage

## Define

- Detection
- Failover
- Manual workaround
- Recovery
- Escalation
- Business continuity process
- Communication
- Recovery objectives

---

# 29. Build Strategy & Dependencies

Translate the architecture into implementation workstreams.

## Identify

- Build sequence
- Dependencies
- Parallel workstreams
- Technical prerequisites
- Customer prerequisites
- Third-party prerequisites
- Environment prerequisites
- Data prerequisites
- Integration prerequisites

## Example

```text
Platform Foundation
        ↓
Identity
        ↓
Users / Roles
        ↓
Telephony
        ↓
Queues / Skills
        ↓
Architect
        ↓
Routing
        ↓
Integrations
        ↓
Digital
        ↓
WEM
        ↓
Reporting
        ↓
Testing
```

Where appropriate, parallel workstreams should be identified.

---

# 30. Configuration Standards

Define implementation standards before build begins.

## Standards should cover

- Naming conventions
- Description standards
- Queue naming
- Skill naming
- Language naming
- Architect flow naming
- Prompt naming
- Data Action naming
- OAuth client naming
- Integration naming
- Group naming
- Role naming
- Division naming
- User naming
- Documentation standards
- Version control
- Change control
- Configuration promotion

---

# 31. Automation & Infrastructure-as-Code Strategy

Determine which components should be deployed manually versus automatically.

## Consider

- Terraform
- Genesys Cloud APIs
- CLI tooling
- CI/CD
- Configuration-as-code
- CSV-driven configuration
- JSON configuration
- Automated validation
- Automated deployment
- Automated testing

## Define

For each component:

- Manual
- Automated
- Hybrid

And document the reason.

---

# 32. Design Decisions

Every significant architectural decision should be recorded.

Recommended format:

| Field | Description |
|---|---|
| Decision ID | Unique identifier |
| Date | Decision date |
| Decision | What was decided |
| Context | Why a decision was required |
| Options | Alternatives considered |
| Selected Option | Chosen approach |
| Rationale | Reason for selection |
| Impact | Technical / business impact |
| Owner | Decision owner |
| Status | Proposed / Approved / Rejected |

---

# 33. Architecture Risks

Identify risks introduced or discovered during design.

Potential categories:

- Technical
- Integration
- Security
- Network
- Telephony
- Data
- Performance
- Operational
- Licensing
- Third-party
- Schedule
- Resource

Each risk should have:

- Risk ID
- Description
- Probability
- Impact
- Rating
- Mitigation
- Owner
- Target date

---

# 34. Design Validation

Before approval, conduct structured validation.

## Review Areas

### Business

- Requirements satisfied
- Business processes supported
- Customer experience validated

### Technical

- Architecture validated
- Dependencies understood
- Integration design validated
- Network validated
- Security validated

### Operational

- Support model validated
- Monitoring defined
- BAU ownership defined
- Runbooks identified

### Compliance

- Regulatory requirements satisfied
- Data retention defined
- Security controls validated

---

# 35. Primary Design Deliverables

Phase 04 should produce, at minimum:

1. Future-state solution architecture
2. High-level architecture diagram
3. Detailed solution architecture
4. Genesys Cloud organisation design
5. Environment strategy
6. Division architecture
7. Identity architecture
8. Security architecture
9. RBAC / permissions matrix
10. User / licence architecture
11. Telephony architecture
12. Number / dial plan design
13. ACD / routing architecture
14. Queue / skill / language design
15. Architect / IVR architecture
16. Digital channel architecture
17. Email architecture
18. Outbound architecture
19. WEM architecture
20. Recording architecture
21. Reporting / analytics architecture
22. CRM / integration architecture
23. API / Data Action design
24. Data migration architecture
25. Network / endpoint architecture
26. Security / compliance architecture
27. Operational architecture
28. DR / business continuity design
29. Build strategy
30. Build dependency map
31. Configuration standards
32. Automation / IaC strategy
33. Architecture decision register
34. Updated RAID register
35. Requirements traceability update
36. Detailed solution design pack

---

# 36. Phase Gate — Gate 04: Solution Design Approved

## Entry Criteria

- Phase 03 Gate 03 passed.
- Requirements baseline approved.
- Solution stakeholders available.
- Architecture workshops completed.

## Exit Criteria

Design is complete when:

- Future-state architecture is documented.
- Genesys Cloud organisation architecture is defined.
- Environment strategy is defined.
- Division architecture is defined.
- Identity and security architecture is defined.
- RBAC model is defined.
- Telephony architecture is approved.
- Number strategy is approved.
- ACD and routing architecture is approved.
- Queue / skill / language model is approved.
- Architect architecture is approved.
- Digital architecture is approved.
- WEM architecture is approved where applicable.
- Integration architecture is approved.
- API / Data Action architecture is approved.
- Data migration strategy is approved.
- Reporting architecture is approved.
- Network architecture is approved.
- Operational architecture is approved.
- DR / business continuity requirements are addressed.
- Build dependencies are identified.
- Configuration standards are established.
- Automation strategy is established.
- Major architecture decisions are documented.
- Design risks are documented.
- Requirements traceability is established.
- Solution design has been reviewed with required stakeholders.

## Gate Decision

**Gate 04 — SOLUTION DESIGN APPROVED**

Status:

- **PASS** — Approved for implementation
- **PASS WITH CONDITIONS** — Build may commence with documented actions
- **HOLD** — Significant design items remain unresolved
- **FAIL** — Design insufficient to commence implementation

---

# 37. Phase Dependencies

## Predecessor

**Phase 03 — Requirements & Solution Definition**

## Successor

**Phase 05 — Platform Foundation & Environment Build**

---

# 38. Key Roles

| Role | Responsibility |
|---|---|
| Project Manager | Coordinate design activities |
| Solution Architect | Own overall solution architecture |
| Genesys Cloud Architect | Own Genesys platform architecture |
| Technical Lead | Coordinate technical architecture |
| Telephony Architect | Own voice / carrier design |
| Network Architect | Own network architecture |
| Security Architect | Own security architecture |
| IAM Lead | Own identity architecture |
| ACD / Routing Lead | Own routing architecture |
| Architect Lead | Own IVR / Architect architecture |
| Digital Lead | Own digital architecture |
| WEM Lead | Own WFM / QM architecture |
| Integration Architect | Own integration architecture |
| CRM Architect | Own CRM architecture |
| Data Architect | Own data / migration architecture |
| Reporting Lead | Own analytics architecture |
| Operations Lead | Own BAU operational architecture |
| Customer SMEs | Validate future-state design |
| Compliance / Legal | Validate compliance design |

---

# 39. Methodology Principle

**Phase 04 defines how the requirements will be realised as a technical solution.**

The design must be detailed enough that the implementation team can build the solution without making significant undocumented architectural decisions during configuration.

The intended progression is:

**Requirements**

↓

**Architecture**

↓

**Detailed Design**

↓

**Build Tasks**

↓

**Configuration**

↓

**Testing**

This phase should therefore produce enough detail to enable the next phase to be decomposed into discrete implementation tasks with clear dependencies and effort estimates.

---

# Layer 1 Position

| Phase | Status |
|---|---|
| **01 — Project Initiation & Mobilisation** | Baseline |
| **02 — Discovery & Current-State Assessment** | Baseline |
| **03 — Requirements & Solution Definition** | Baseline |
| **04 — Solution Architecture & Detailed Design** | **Defined** |
| 05 — Platform Foundation & Environment Build | Next |
| 06 — Feature Configuration & Solution Build | Pending |
| 07 — Integration & Data Migration | Pending |
| 08 — Testing & Validation | Pending |
| 09 — Operational Readiness & Cutover Preparation | Pending |
| 10 — Production Deployment & Go-Live | Pending |
| 11 — Hypercare & Stabilisation | Pending |
| 12 — BAU Handover & Project Closure | Pending |

---

## Reference

**Methodology:** Genesys Cloud Deployment Project Template  
**Phase:** 04 — Solution Architecture & Detailed Design  
**Phase Gate:** Gate 04 — Solution Design Approved  
**Next Phase:** 05 — Platform Foundation & Environment Build