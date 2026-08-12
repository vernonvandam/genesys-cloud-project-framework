# Phase 02 — Discovery & Current-State Assessment

## 1. Purpose

Establish a comprehensive understanding of the customer's current contact centre environment, business operations, technology landscape, existing processes, integrations, data, telephony, users, and operational requirements.

The objective is to document **what exists today**, identify gaps and constraints, and provide the factual baseline required for Phase 03 — Requirements & Solution Definition.

---

## 2. Phase Objective

By the end of Phase 02:

- Current business processes are understood.
- Current contact centre operations are documented.
- Existing technology is inventoried.
- Existing telephony and carrier arrangements are understood.
- Current routing and queue structures are documented.
- Existing IVR / Architect behaviour is understood.
- User and agent populations are identified.
- Existing digital channels are documented.
- CRM and third-party integrations are identified.
- Reporting and analytics requirements are understood at a current-state level.
- WFM / QM processes are documented where applicable.
- Security and identity architecture is understood.
- Network and connectivity requirements are identified.
- Migration requirements are identified.
- Pain points and gaps are documented.
- Risks, constraints and dependencies are identified.
- Discovery findings are ready to feed into requirements and solution design.

---

# 3. Discovery Workstreams

The discovery phase is structured into 15 workstreams:

### 02.01 Business & Operational Discovery
### 02.02 Contact Centre Organisation
### 02.03 User & Workforce Discovery
### 02.04 Voice & Telephony Discovery
### 02.05 ACD & Routing Discovery
### 02.06 IVR / Architect Discovery
### 02.07 Digital Channel Discovery
### 02.08 Email Discovery
### 02.09 Outbound Discovery
### 02.10 WEM Discovery
### 02.11 Reporting & Analytics Discovery
### 02.12 CRM & Integration Discovery
### 02.13 Security, Identity & Access Discovery
### 02.14 Network & Infrastructure Discovery
### 02.15 Data & Migration Discovery

---

# 4. Business & Operational Discovery

Understand **why the contact centre exists and how the business operates it**.

## Activities

1. Identify business objectives.
2. Identify business units.
3. Identify contact centre functions.
4. Identify customer interaction types.
5. Identify inbound interaction volumes.
6. Identify outbound interaction volumes.
7. Identify peak periods.
8. Identify seasonal variations.
9. Identify operating hours.
10. Identify holidays and closures.
11. Identify service-level objectives.
12. Identify response-time objectives.
13. Identify abandonment targets.
14. Identify customer experience objectives.
15. Identify operational KPIs.
16. Document major business processes.
17. Document escalation processes.
18. Document exception processes.
19. Identify regulatory requirements.
20. Identify compliance requirements.
21. Identify business continuity requirements.

## Outputs

- Business operating model
- Contact centre process inventory
- Business KPI catalogue
- Operational requirements baseline

---

# 5. Contact Centre Organisation Discovery

Document the organisational structure of the contact centre.

## Activities

Identify:

- Business units
- Departments
- Contact centres
- Sites
- Teams
- Supervisors
- Managers
- Agents
- Back-office users
- Administrators
- Workforce management teams
- Quality teams
- Reporting teams
- Support teams

Document reporting relationships and operational ownership.

---

# 6. User & Workforce Discovery

Establish the complete user population.

## Activities

Capture:

- Total users
- Agents
- Supervisors
- Managers
- Administrators
- Business users
- WFM users
- QM users
- Reporting users
- Developers
- External users
- Temporary users
- Contractors

For each population identify:

- Number of users
- Location
- Role
- Department
- Team
- Shift
- Licence requirements
- Security requirements
- Authentication requirements
- Required Genesys permissions
- Existing identity source

## Output

**User & Licence Discovery Matrix**

This will eventually feed directly into the Genesys Cloud licensing and user configuration work.

---

# 7. Voice & Telephony Discovery

This is one of the highest-impact discovery areas.

## Current Telephony

Document:

- Current platform
- Carrier
- SIP provider
- PSTN provider
- Phone numbers
- DID ranges
- Toll-free numbers
- Service numbers
- Emergency numbers
- Geographic numbers
- International numbers
- Existing SIP trunks
- SBCs
- PBXs
- Contact centre platforms
- Recording platforms

## Number Inventory

For every number:

- Number
- Purpose
- Business owner
- Current carrier
- Destination
- Porting requirement
- Target Genesys destination
- Cutover requirement

## Call Types

Identify:

- Inbound
- Outbound
- Internal
- Transfers
- Consults
- Conferences
- Callbacks
- Emergency calls
- After-hours calls

## Output

**Current-State Telephony Architecture**

---

# 8. ACD & Routing Discovery

Understand how interactions are currently routed.

## Identify

- Queues
- Skills
- Languages
- Routing methods
- Agent groups
- Teams
- Priorities
- Service levels
- Overflow
- Escalation
- Callback
- Bullseye routing
- Preferred agents
- VIP routing
- Priority customers
- After-hours routing
- Holiday routing
- Failover routing

## Document

For each queue:

- Queue name
- Purpose
- Interaction types
- Skills
- Languages
- Agent population
- Service level
- Routing method
- Priority
- Overflow
- Escalation
- Business hours

## Output

**Current-State Routing Catalogue**

---

# 9. IVR / Architect Discovery

Document the current customer journey through the IVR.

## Activities

Identify:

- Main IVR
- Submenus
- Menu options
- Authentication
- Customer identification
- Account lookup
- Data lookups
- Self-service
- Announcements
- Queue selection
- Queue transfers
- Agent transfers
- Callback
- Failover
- After-hours
- Holiday handling
- Error handling
- Disconnect behaviour

## For Every IVR Flow

Document:

**Entry → Menu → Decision → Data Lookup → Routing → Queue → Agent**

Where possible, capture the existing call flow visually.

## Output

**Current-State IVR / Call Flow Catalogue**

---

# 10. Digital Channel Discovery

Identify every digital interaction channel currently supported.

## Channels

- Web chat
- Web messaging
- SMS
- WhatsApp
- Facebook Messenger
- Instagram
- Other social messaging
- Mobile applications
- Other digital channels

For each channel identify:

- Volume
- Operating hours
- Routing
- Queues
- Agents
- Skills
- SLAs
- Automation
- Bots
- Escalation
- Reporting
- Integrations
- Retention requirements

---

# 11. Email Discovery

Document the current email contact centre model.

## Identify

- Email addresses
- Mailboxes
- Shared mailboxes
- Distribution groups
- Email queues
- Routing rules
- Auto responses
- Templates
- SLAs
- Escalations
- Attachments
- Security requirements
- Retention requirements
- Existing integrations

---

# 12. Outbound Discovery

If outbound is in scope, capture:

- Campaigns
- Campaign types
- Campaign volumes
- Contact lists
- Data sources
- Campaign schedules
- Calling modes
- Preview
- Predictive
- Power
- Agentless
- DNC requirements
- Compliance
- Caller ID
- Dispositions
- Wrap-up codes
- Reporting
- Campaign-specific routing

---

# 13. WEM Discovery

Where applicable, document current Workforce Engagement Management processes.

## Workforce Management

- Forecasting
- Scheduling
- Intraday management
- Adherence
- Shrinkage
- Staffing
- Planning horizons
- Scheduling rules
- Service-level targets

## Quality Management

- Evaluation forms
- Evaluation criteria
- Sampling
- Quality scores
- Calibration
- Coaching
- Feedback
- Dispute process

## Performance Management

- KPIs
- Scorecards
- Targets
- Agent performance
- Supervisor performance
- Coaching

## Recording

Document:

- Recording scope
- Recording policies
- Retention
- Encryption
- PCI requirements
- Pause/resume
- Screen recording
- Recording access

---

# 14. Reporting & Analytics Discovery

Identify current reporting requirements.

## Discover

- Operational reports
- Historical reports
- Real-time dashboards
- Wallboards
- Supervisor reporting
- Management reporting
- Executive reporting
- Regulatory reporting
- Agent performance reporting
- Queue reporting
- SLA reporting
- Abandonment reporting
- Contact-volume reporting
- WEM reporting

For each report identify:

- Report name
- Business owner
- Data source
- Frequency
- Audience
- KPIs
- Required history
- Export requirements

---

# 15. CRM & Integration Discovery

This needs to be comprehensive because integration complexity can materially change project effort.

## Identify

- CRM
- ERP
- Ticketing
- Authentication
- Customer databases
- Knowledge bases
- Payment systems
- External APIs
- Middleware
- Data warehouses
- Reporting platforms
- Business applications

## For Each Integration

Capture:

- System
- Owner
- Purpose
- Direction
- Trigger
- Data exchanged
- API
- Authentication
- Middleware
- Frequency
- Real-time / batch
- Error handling
- Retry behaviour
- Availability requirements
- Security requirements
- Dependencies

## Output

**Integration Inventory**

---

# 16. Security, Identity & Access Discovery

Identify the customer's security architecture.

## Discover

- Identity provider
- Active Directory
- Entra ID
- SSO
- MFA
- SCIM
- User provisioning
- Group provisioning
- Password policies
- Conditional access
- Role-based access
- Privileged access
- API authentication
- OAuth
- Service accounts
- Security monitoring
- Audit requirements

Also identify:

- Data residency requirements
- Compliance requirements
- Privacy requirements
- PCI
- PII
- Data retention
- Recording retention

---

# 17. Network & Infrastructure Discovery

Identify technical connectivity requirements.

## Discover

- Internet connectivity
- WAN
- LAN
- SD-WAN
- Firewalls
- Proxies
- DNS
- QoS
- NAT
- VPN
- WebRTC requirements
- Browser requirements
- Endpoint requirements
- Headsets
- Softphones
- Remote users
- Office users
- Home workers
- Network restrictions

## Voice-Specific

Capture:

- RTP
- SIP
- Ports
- NAT
- QoS
- Latency
- Jitter
- Packet loss
- Bandwidth
- Carrier connectivity

## Output

**Network Readiness Assessment**

---

# 18. Data & Migration Discovery

Identify all data that needs to move or be recreated.

## Potential Migration Objects

- Users
- Teams
- Queues
- Skills
- Languages
- Numbers
- Routing configuration
- IVR
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

For each object determine:

- Source
- Volume
- Format
- Owner
- Quality
- Transformation requirements
- Migration method
- Validation method
- Retention requirement

---

# 19. Current-State Gap Analysis

Once discovery is complete, compare:

**Current State → Target Business Requirement**

Identify:

- Capability gaps
- Process gaps
- Technical gaps
- Integration gaps
- Security gaps
- Data gaps
- Network gaps
- Operational gaps
- Skills gaps
- Training gaps

Each gap should receive:

- Gap ID
- Description
- Impact
- Owner
- Required action
- Dependency
- Risk
- Target phase

---

# 20. Discovery Findings & Risks

Consolidate all findings into:

### Risks

Potential events that could negatively impact delivery.

### Issues

Known problems requiring action.

### Assumptions

Items currently accepted as true but not yet validated.

### Dependencies

External conditions required for delivery.

### Constraints

Known limitations affecting the solution or schedule.

---

# 21. Primary Deliverables

Phase 02 should produce:

1. Business discovery document
2. Current-state architecture
3. Contact centre operating model
4. User / workforce inventory
5. Licence discovery matrix
6. Telephony inventory
7. Number inventory
8. Current-state routing catalogue
9. Current-state IVR catalogue
10. Digital-channel inventory
11. Email inventory
12. Outbound inventory
13. WEM discovery
14. Reporting inventory
15. Integration inventory
16. Security / identity assessment
17. Network readiness assessment
18. Data / migration assessment
19. Gap analysis
20. Updated RAID register
21. Discovery findings report
22. Requirements input catalogue

---

# 22. Phase Gate — Gate 02: Discovery Complete

## Entry Criteria

- Phase 01 Gate 01 passed.
- Project team mobilised.
- Stakeholders available.
- Discovery workshops scheduled.

## Exit Criteria

Discovery is complete when:

- Business processes have been documented.
- Current contact centre architecture is understood.
- User populations are identified.
- Telephony is understood.
- Routing is understood.
- IVR flows are documented.
- Digital channels are documented.
- Integrations are identified.
- Security and identity are understood.
- Network requirements are understood.
- WEM requirements are understood at current-state level.
- Reporting requirements are documented at current-state level.
- Data and migration requirements are identified.
- Gaps have been documented.
- Risks and dependencies have been updated.
- Discovery findings have been reviewed with stakeholders.
- Inputs required for Phase 03 are available.

## Gate Decision

**Gate 02 — DISCOVERY COMPLETE**

Status:

- **PASS** — Ready for Requirements
- **PASS WITH CONDITIONS** — Requirements can proceed with documented outstanding actions
- **HOLD** — Significant discovery gaps remain
- **FAIL** — Insufficient information to define requirements

---

# 23. Phase Dependencies

## Predecessor

**Phase 01 — Project Initiation & Mobilisation**

## Successor

**Phase 03 — Requirements & Solution Definition**

---

# 24. Key Roles

| Role | Discovery Responsibility |
|---|---|
| Project Manager | Coordinate discovery activities |
| Solution Architect | Lead technical discovery |
| Genesys Cloud Architect | Genesys capability discovery |
| Business Lead | Business process discovery |
| Contact Centre Lead | Operational discovery |
| Telephony Lead | Voice and carrier discovery |
| Network Lead | Network discovery |
| Security Lead | Security and identity discovery |
| Integration Lead | Integration discovery |
| CRM Lead | CRM discovery |
| WEM Lead | WFM / QM discovery |
| Data Lead | Data and migration discovery |
| Reporting Lead | Reporting and analytics discovery |
| Customer SMEs | Provide current-state knowledge |

---

# 25. Methodology Principle

**Phase 02 is about understanding the current state — not designing the future state.**

The team should avoid prematurely deciding how the Genesys Cloud solution will be configured.

The correct progression is:

**Current State → Requirements → Future State → Solution Design → Build**

This distinction is critical because discovery findings should inform requirements, while requirements should drive the eventual Genesys Cloud design.

---

# Layer 1 Position

| Phase | Status |
|---|---|
| **01 — Project Initiation & Mobilisation** | Baseline |
| **02 — Discovery & Current-State Assessment** | **Defined** |
| 03 — Requirements & Solution Definition | Next |
| 04 — Solution Architecture & Detailed Design | Pending |
| 05 — Platform Foundation & Environment Build | Pending |
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
**Phase:** 02 — Discovery & Current-State Assessment  
**Phase Gate:** Gate 02 — Discovery Complete  
**Next Phase:** 03 — Requirements & Solution Definition