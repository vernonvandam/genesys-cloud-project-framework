# Phase 03 — Requirements & Solution Definition

## 1. Purpose

Translate the findings from Phase 02 — Discovery & Current-State Assessment into a complete, agreed, prioritised, and traceable set of business, functional, technical, operational, security, integration, data, and compliance requirements.

The objective is to establish **what the future Genesys Cloud solution must achieve** before detailed technical design and configuration begins.

This phase establishes the baseline against which solution architecture, configuration, testing, acceptance, and ultimately project success will be measured.

---

## 2. Phase Objective

By the end of Phase 03:

- Business requirements are documented.
- Functional requirements are documented.
- Non-functional requirements are documented.
- Genesys Cloud feature requirements are identified.
- Requirements are prioritised.
- Requirements are traceable to business objectives.
- Requirements are traceable to solution components.
- Requirements are traceable to future test cases.
- Integration requirements are defined.
- Telephony requirements are defined.
- Routing requirements are defined.
- Architect / IVR requirements are defined.
- Digital-channel requirements are defined.
- WEM requirements are defined where applicable.
- Reporting and analytics requirements are defined.
- Security and identity requirements are defined.
- Data and migration requirements are defined.
- Compliance requirements are defined.
- Operational and support requirements are defined.
- Customer acceptance criteria are established.
- Scope is baselined.
- Requirements are approved and ready to drive solution design.

---

# 3. Requirements Workstreams

The requirements phase is structured into the following workstreams:

### 03.01 Business Requirements
### 03.02 Contact Centre Functional Requirements
### 03.03 User & Role Requirements
### 03.04 Voice & Telephony Requirements
### 03.05 ACD & Routing Requirements
### 03.06 Architect / IVR Requirements
### 03.07 Digital Channel Requirements
### 03.08 Email Requirements
### 03.09 Outbound Requirements
### 03.10 Workforce Engagement Requirements
### 03.11 Recording & Quality Requirements
### 03.12 Reporting & Analytics Requirements
### 03.13 CRM & Integration Requirements
### 03.14 Security, Identity & Access Requirements
### 03.15 Network & Endpoint Requirements
### 03.16 Data & Migration Requirements
### 03.17 Compliance & Regulatory Requirements
### 03.18 Operational & Support Requirements
### 03.19 Training & Change Requirements
### 03.20 Non-Functional Requirements
### 03.21 Acceptance Criteria
### 03.22 Requirements Traceability & Baseline

---

# 4. Business Requirements

Define what the business expects the new contact centre platform to achieve.

## Activities

1. Review Phase 02 discovery findings.
2. Validate business objectives.
3. Validate business outcomes.
4. Identify measurable business goals.
5. Define customer experience objectives.
6. Define agent experience objectives.
7. Define supervisor experience objectives.
8. Define management objectives.
9. Define operational efficiency objectives.
10. Define automation objectives.
11. Define service-level objectives.
12. Define reporting objectives.
13. Define compliance objectives.
14. Define scalability objectives.
15. Define resilience objectives.

## Example Business Requirements

Requirements may include:

- Reduce customer wait times.
- Improve first-contact resolution.
- Increase self-service.
- Improve agent productivity.
- Consolidate customer interaction channels.
- Improve supervisor visibility.
- Improve workforce forecasting.
- Improve quality monitoring.
- Reduce operational cost.
- Improve customer experience.
- Replace legacy contact centre technology.
- Standardise contact centre operations.

Each business requirement should have:

- Requirement ID
- Description
- Business owner
- Business objective
- Priority
- Acceptance criteria
- Source
- Dependencies

---

# 5. Contact Centre Functional Requirements

Define how the contact centre must operate.

## Requirements

Capture requirements relating to:

- Inbound interactions
- Outbound interactions
- Agent handling
- Supervisor handling
- Queue management
- Interaction routing
- Transfers
- Consultations
- Conferences
- Callbacks
- Escalations
- Priority handling
- VIP customers
- Service levels
- Overflow
- After-hours
- Holidays
- Failover
- Agent status
- Wrap-up
- Dispositions
- Interaction history

---

# 6. User & Role Requirements

Define the user populations and what each population must be able to do.

## User Types

Identify requirements for:

- Agents
- Supervisors
- Managers
- Administrators
- WFM users
- QM users
- Reporting users
- Developers
- Integration accounts
- API users
- External users

For each population define:

- User count
- Business role
- Genesys role
- Licence requirement
- Permissions
- Divisions
- Groups
- Authentication
- SSO
- MFA
- Provisioning
- Deprovisioning

---

# 7. Voice & Telephony Requirements

Define the target telephony capabilities.

## Requirements

Capture:

- Carrier
- PSTN
- DID
- Toll-free numbers
- Number porting
- Outbound caller ID
- Inbound caller ID
- SIP
- BYOC Cloud
- BYOC Premises
- Genesys Cloud Voice
- Sites
- Phone configuration
- WebRTC
- Physical phones
- Emergency calling
- E911 / local emergency requirements
- International calling
- Dial plans
- Outbound routes
- Call recording
- Call transfer
- Conference
- Callback
- Failover

## Number Requirements

Define:

- Number
- Purpose
- Business owner
- Current destination
- Target destination
- Porting requirement
- Carrier requirement
- Cutover requirement

---

# 8. ACD & Routing Requirements

Define exactly how Genesys Cloud should determine where interactions are sent.

## Requirements

Capture:

- Queue structure
- Skill structure
- Language structure
- Routing method
- Standard routing
- Bullseye routing
- Preferred agent routing
- Priority routing
- VIP routing
- Emergency routing
- Overflow
- Escalation
- Callback
- Service level
- Queue timeout
- Agent utilisation
- Interaction priority
- Routing delay
- Evaluation method

## Queue Requirements

Each queue should define:

- Queue ID
- Queue name
- Purpose
- Channel
- Business owner
- Agent population
- Skills
- Languages
- Priority
- Service level
- Routing method
- Overflow
- Escalation
- Operating hours

---

# 9. Architect / IVR Requirements

Define the required customer interaction flows.

## Requirements

Capture:

- Entry points
- Main menus
- Submenus
- Prompts
- Menu options
- DTMF
- Speech recognition
- Customer identification
- Authentication
- Data lookup
- Self-service
- Business rules
- Queue selection
- Skill selection
- Priority
- Callback
- Transfer
- Agent escalation
- Error handling
- Failover
- After-hours
- Holiday handling
- Disconnect behaviour

## Call Flow Definition

Each flow should document:

**Entry → Greeting → Identification → Menu → Business Logic → Data Lookup → Routing → Queue → Agent**

Where self-service exists:

**Entry → Authentication → Data → Self-Service → Resolution / Escalation**

## Architect Requirements

Each flow should have:

- Flow ID
- Flow name
- Purpose
- Trigger
- Inputs
- Logic
- Data dependencies
- Outputs
- Queue
- Skills
- Error handling
- Failover
- Business owner
- Acceptance criteria

---

# 10. Digital Channel Requirements

Define the required digital interaction channels.

## Channels

Potential requirements include:

- Web chat
- Web messaging
- SMS
- WhatsApp
- Facebook Messenger
- Instagram
- Other social messaging
- Mobile application
- Bot / virtual agent channels

For each channel define:

- Business purpose
- Customer journey
- Operating hours
- Routing
- Queue
- Skills
- Priority
- SLA
- Automation
- Bot requirements
- Agent escalation
- Transfer requirements
- Reporting
- Retention
- Integration requirements

---

# 11. Email Requirements

Define the required email contact centre capabilities.

## Requirements

Capture:

- Email addresses
- Email queues
- Routing
- Auto responses
- Templates
- SLAs
- Escalations
- Attachments
- Security
- Retention
- Email threading
- Agent handling
- Reporting
- Integrations

---

# 12. Outbound Requirements

Where outbound is in scope, define:

- Campaigns
- Campaign types
- Contact lists
- Contact sources
- Campaign schedules
- Calling modes
- Preview
- Power
- Predictive
- Agentless
- Caller ID
- Dispositions
- Wrap-up codes
- Retry rules
- DNC
- Compliance
- Campaign priorities
- Agent assignment
- Reporting

---

# 13. Workforce Engagement Requirements

Where WEM is in scope, define requirements for:

## Workforce Management

- Forecasting
- Scheduling
- Staffing
- Service-level targets
- Shrinkage
- Intraday management
- Adherence
- Schedule rules
- Planning periods

## Quality Management

- Evaluation forms
- Evaluation questions
- Scoring
- Sampling
- Calibration
- Coaching
- Feedback
- Disputes
- Quality targets

## Performance Management

- KPIs
- Scorecards
- Targets
- Agent performance
- Team performance
- Supervisor performance
- Coaching

---

# 14. Recording & Quality Requirements

Define:

- Recording scope
- Recording policies
- Recording retention
- Recording access
- Encryption
- Screen recording
- Quality management
- Evaluation
- PCI handling
- Secure pause
- Recording export
- Legal hold
- Data retention

---

# 15. Reporting & Analytics Requirements

Define the required reporting model.

## Reporting Categories

- Real-time reporting
- Historical reporting
- Agent reporting
- Queue reporting
- Interaction reporting
- SLA reporting
- Abandonment reporting
- Contact-volume reporting
- Performance reporting
- WEM reporting
- Executive reporting
- Regulatory reporting

For each report define:

- Report ID
- Name
- Purpose
- Audience
- Owner
- Data source
- KPIs
- Filters
- Frequency
- Retention
- Export requirements
- Acceptance criteria

---

# 16. CRM & Integration Requirements

Define the future-state integration requirements.

## For Each Integration

Capture:

- Integration ID
- Source system
- Target system
- Purpose
- Trigger
- Direction
- Data exchanged
- API
- Authentication
- Data transformation
- Middleware
- Real-time / batch
- Frequency
- Timeout
- Retry
- Error handling
- Logging
- Monitoring
- Security
- Availability
- Business owner
- Technical owner
- Acceptance criteria

## Integration Patterns

Identify whether the solution requires:

- Genesys Cloud Data Actions
- REST APIs
- Webhooks
- Event streams
- Middleware
- Serverless functions
- Custom applications
- CRM embedded clients
- Screen pops
- Customer lookup
- Case creation
- Case updates
- Interaction synchronisation

---

# 17. Security, Identity & Access Requirements

Define the required security model.

## Identity

Capture:

- Identity provider
- SSO
- MFA
- SCIM
- User provisioning
- Group provisioning
- Deprovisioning
- Password policies
- Conditional access

## Authorisation

Define:

- Roles
- Permissions
- Divisions
- Groups
- Administrative access
- Privileged access
- API access
- Service accounts

## Security

Define:

- Data encryption
- Data residency
- Audit
- Logging
- Security monitoring
- PII
- PCI
- Recording protection
- Data retention
- Access logging

---

# 18. Network & Endpoint Requirements

Define requirements for:

- Internet connectivity
- WAN
- LAN
- SD-WAN
- Firewall
- Proxy
- DNS
- NAT
- QoS
- WebRTC
- SIP
- RTP
- Browser
- Operating system
- Headsets
- Physical phones
- Remote users
- Office users
- Home workers

## Voice Quality Requirements

Define acceptable thresholds for:

- Latency
- Jitter
- Packet loss
- Bandwidth
- MOS / voice quality
- Network availability

---

# 19. Data & Migration Requirements

Define all data that must be migrated, transformed, recreated, or retained.

## Migration Objects

Potential objects include:

- Users
- Teams
- Queues
- Skills
- Languages
- Numbers
- Routing
- Architect flows
- Prompts
- Scripts
- Wrap-up codes
- Dispositions
- Campaigns
- Contact lists
- Integrations
- Reports
- Historical data
- Knowledge content

For each object define:

- Source
- Target
- Volume
- Format
- Transformation
- Validation
- Migration method
- Migration owner
- Cutover requirement
- Retention requirement

---

# 20. Compliance & Regulatory Requirements

Identify all regulatory and compliance requirements affecting the implementation.

Potential areas include:

- Privacy
- PII
- PCI DSS
- Recording
- Data residency
- Data sovereignty
- Retention
- Legal hold
- Consent
- Call recording notification
- DNC
- Marketing compliance
- Accessibility
- Security standards
- Industry-specific requirements

Each compliance requirement should include:

- Requirement ID
- Regulation / policy
- Requirement
- Business owner
- Technical implication
- Evidence required
- Acceptance criteria

---

# 21. Operational & Support Requirements

Define how the platform must be operated after go-live.

## Requirements

Capture:

- Support hours
- Support model
- Service desk
- Incident management
- Escalation
- Monitoring
- Alerting
- Administration
- Change management
- Configuration management
- Release management
- Problem management
- Disaster recovery
- Business continuity
- Backup / recovery requirements
- Operational reporting
- Runbooks
- Knowledge management

---

# 22. Training & Change Requirements

Define the training and organisational-change requirements.

## User Groups

- Agents
- Supervisors
- Managers
- Administrators
- WFM users
- QM users
- Reporting users
- Support teams
- IT teams

For each group define:

- Training topics
- Delivery method
- Training duration
- Training environment
- Training materials
- Training owner
- Completion criteria

---

# 23. Non-Functional Requirements

Non-functional requirements should be explicitly documented rather than assumed.

## Categories

### Performance

- Response time
- Interaction handling
- API performance
- Reporting performance

### Availability

- Service availability
- Integration availability
- Network availability
- Business continuity

### Scalability

- Users
- Concurrent interactions
- Contact volume
- Digital interactions
- Campaign volume

### Security

- Authentication
- Authorisation
- Encryption
- Logging
- Audit

### Maintainability

- Administration
- Configuration
- Documentation
- Monitoring
- Support

### Usability

- Agent experience
- Supervisor experience
- Administrator experience
- Customer experience

### Compliance

- Data retention
- Privacy
- Recording
- Regulatory requirements

---

# 24. Requirements Prioritisation

Every requirement should be assigned a priority.

Recommended classification:

| Priority | Meaning |
|---|---|
| **Must Have** | Required for successful go-live |
| **Should Have** | Important but has an acceptable workaround |
| **Could Have** | Desirable but not essential |
| **Won't Have** | Explicitly excluded from current release |

This is useful for controlling scope and identifying MVP versus future-phase functionality.

---

# 25. Requirements ID Structure

Every requirement should receive a unique identifier.

Recommended format:

```text
REQ-BUS-001
REQ-FUN-001
REQ-VOICE-001
REQ-ACD-001
REQ-ARCH-001
REQ-DIG-001
REQ-EMAIL-001
REQ-OUT-001
REQ-WEM-001
REQ-REC-001
REQ-RPT-001
REQ-INT-001
REQ-SEC-001
REQ-NET-001
REQ-DATA-001
REQ-COMP-001
REQ-OPS-001
REQ-TRN-001
REQ-NFR-001