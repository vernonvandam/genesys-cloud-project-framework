# Layer 2.13 — Migration, Data Conversion & Transition

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 13 — Migration, Data Conversion & Transition  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete migration, data conversion, transition, coexistence, cutover, reconciliation, archival and decommissioning capabilities required to move a contact centre solution, its supporting data and operational processes into Genesys Cloud.

---

# 1. Purpose

The Migration, Data Conversion & Transition domain defines the activities required to safely move from the existing contact centre environment to the target Genesys Cloud solution.

Migration is not limited to moving data.

A complete migration strategy must address:

- Existing platform assessment
- Source-system discovery
- Data discovery
- Data classification
- Data ownership
- Data quality
- Data retention
- Data privacy
- Data conversion
- Configuration migration
- User migration
- Queue migration
- Skill migration
- Routing migration
- Architect migration
- Telephony migration
- Digital migration
- CRM/customer data
- Integration migration
- Historical interaction data
- Recordings
- Quality data
- WFM data
- Reporting data
- API dependencies
- Migration tooling
- Migration rehearsals
- Mock migrations
- Delta migrations
- Cutover
- Coexistence
- Rollback
- Validation
- Reconciliation
- Hypercare
- Legacy platform transition
- Archival
- Decommissioning

The objective is to ensure that the transition to Genesys Cloud is controlled, measurable, reversible where required, and operationally safe.

---

# 2. Scope

```text
13 Migration, Data Conversion & Transition
│
├── 01 Migration Strategy
├── 02 Migration Governance
├── 03 Migration Scope & Assessment
├── 04 Source System Inventory
├── 05 Data Discovery
├── 06 Data Profiling
├── 07 Data Classification
├── 08 Data Ownership
├── 09 Data Retention
├── 10 Privacy & Compliance
├── 11 Migration Architecture
├── 12 Migration Approach
├── 13 Migration Mapping
├── 14 Data Transformation
├── 15 Data Cleansing
├── 16 Data Extraction
├── 17 Data Staging
├── 18 Data Loading
├── 19 Configuration Migration
├── 20 User Migration
├── 21 Queue Migration
├── 22 Skill & Language Migration
├── 23 Routing Migration
├── 24 Architect Migration
├── 25 Telephony Migration
├── 26 Digital Migration
├── 27 CRM / Customer Data Migration
├── 28 Integration Migration
├── 29 API Migration
├── 30 Historical Interaction Data
├── 31 Recording Migration
├── 32 Quality Data Migration
├── 33 WFM Data Migration
├── 34 Reporting Data Migration
├── 35 Migration Tooling
├── 36 Migration Automation
├── 37 Mock Migration
├── 38 Migration Rehearsal
├── 39 Cutover Migration
├── 40 Delta Migration
├── 41 Data Freeze
├── 42 Coexistence
├── 43 Transition Management
├── 44 Rollback & Recovery
├── 45 Migration Validation
├── 46 Data Reconciliation
├── 47 Post-Migration Validation
├── 48 Hypercare
├── 49 Operational Handover
├── 50 Legacy Platform Transition
├── 51 Data Archival
├── 52 Legacy Decommissioning
└── 53 Migration Closure
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Migration Strategy | Required |
| Migration Governance | Required |
| Migration Scope & Assessment | Required |
| Source System Inventory | Required |
| Data Discovery | Required |
| Data Profiling | Required |
| Data Classification | Required |
| Data Ownership | Required |
| Data Retention | Required |
| Privacy & Compliance | Required |
| Migration Architecture | Required |
| Migration Approach | Required |
| Migration Mapping | Required |
| Data Transformation | Conditional |
| Data Cleansing | Required |
| Data Extraction | Required |
| Data Staging | Conditional |
| Data Loading | Required |
| Configuration Migration | Required |
| User Migration | Required |
| Queue Migration | Required |
| Skill & Language Migration | Required |
| Routing Migration | Required |
| Architect Migration | Required |
| Telephony Migration | Required |
| Digital Migration | Conditional |
| CRM / Customer Data Migration | Conditional |
| Integration Migration | Required |
| API Migration | Conditional |
| Historical Interaction Data | Conditional |
| Recording Migration | Conditional |
| Quality Data Migration | Conditional |
| WFM Data Migration | Conditional |
| Reporting Data Migration | Conditional |
| Migration Tooling | Required |
| Migration Automation | Conditional |
| Mock Migration | Required |
| Migration Rehearsal | Required |
| Cutover Migration | Required |
| Delta Migration | Conditional |
| Data Freeze | Conditional |
| Coexistence | Conditional |
| Transition Management | Required |
| Rollback & Recovery | Required |
| Migration Validation | Required |
| Data Reconciliation | Required |
| Post-Migration Validation | Required |
| Hypercare | Required |
| Operational Handover | Required |
| Legacy Platform Transition | Required |
| Data Archival | Conditional |
| Legacy Decommissioning | Conditional |
| Migration Closure | Required |

---

# 4. Migration Philosophy

Migration should be treated as a controlled transformation rather than a simple data movement exercise.

```text
CURRENT STATE
     │
     ▼
DISCOVERY
     │
     ▼
ASSESSMENT
     │
     ▼
MIGRATION DESIGN
     │
     ▼
MAPPING
     │
     ▼
TRANSFORMATION
     │
     ▼
MOCK MIGRATION
     │
     ▼
REHEARSAL
     │
     ▼
CUTOVER
     │
     ▼
VALIDATION
     │
     ▼
RECONCILIATION
     │
     ▼
TRANSITION
     │
     ▼
HYPERCARE
     │
     ▼
LEGACY RETIREMENT
```

The project must establish clear boundaries between:

- Data that is migrated.
- Data that is transformed.
- Data that is recreated.
- Data that is retained in the legacy platform.
- Data that is archived.
- Data that is discarded under approved retention rules.

---

# 5. Migration Principles

The project should adopt the following principles:

1. Do not migrate data without a defined business purpose.
2. Do not migrate poor-quality data without an approved remediation strategy.
3. Do not migrate sensitive data without security and privacy assessment.
4. Do not assume that the target platform supports direct migration of every source object.
5. Do not assume that historical data can be imported natively.
6. Validate every migration through reconciliation.
7. Perform at least one mock migration for material migrations.
8. Perform a cutover rehearsal for complex deployments.
9. Define rollback before production migration.
10. Define ownership of migrated data.
11. Define retention and archival requirements before migration.
12. Protect production data throughout migration.
13. Maintain auditability of migration activities.
14. Maintain traceability between source and target objects.
15. Obtain explicit business acceptance before legacy decommissioning.

---

# 6. Migration Strategy

The migration strategy should establish:

- Migration scope
- Migration objectives
- Migration principles
- Source systems
- Target systems
- Migration method
- Migration tooling
- Migration sequencing
- Migration waves
- Coexistence requirements
- Data retention
- Data archival
- Cutover approach
- Rollback
- Validation
- Reconciliation
- Business acceptance
- Decommissioning

The strategy must be approved before detailed migration execution begins.

---

# 7. Migration Assessment

The project should assess the current environment across:

### Platform

- Existing contact centre platform
- Version
- Hosting model
- Licensing
- Configuration
- Customisation

### Users

- Agents
- Supervisors
- Administrators
- WFM users
- Quality users
- Reporting users

### Routing

- Queues
- Skills
- Languages
- Priorities
- Routing rules
- IVR
- Overflow
- Business hours

### Telephony

- Numbers
- Trunks
- SIP
- Carrier
- DID
- Toll-free
- Emergency services

### Digital

- Email
- Chat
- Messaging
- Social
- SMS
- Web messaging

### Data

- Customer data
- Interaction data
- Recordings
- Evaluations
- Reports
- Historical data

### Integrations

- CRM
- ERP
- Identity
- APIs
- Data warehouses
- External applications

---

# 8. Source System Inventory

Create an authoritative inventory of every system participating in migration.

| System | Purpose | Owner | Data | Migration Required | Retention |
|---|---|---|---|---|---|
| Legacy Contact Centre | Contact handling | Customer | Users / interactions | Yes | Defined |
| CRM | Customer data | Customer | Customer records | Conditional | Defined |
| WFM | Workforce | Customer | Schedules / forecasts | Conditional | Defined |
| Reporting Platform | Analytics | Customer | Historical reports | Conditional | Defined |
| Recording Platform | Recordings | Customer | Audio | Conditional | Defined |

The final inventory must be project-specific.

---

# 9. Data Discovery

Data discovery must identify:

- Data objects
- Data attributes
- Data volume
- Data owners
- Data source
- Data format
- Data quality
- Data sensitivity
- Data dependencies
- Data retention
- Data lifecycle
- Data destination

---

# 10. Data Profiling

Data profiling should assess:

- Record count
- Null values
- Duplicate values
- Invalid values
- Orphan records
- Referential integrity
- Data formats
- Character encoding
- Date/time formats
- Time zones
- Invalid identifiers
- Inconsistent naming
- Legacy values

Example:

```text
Source Data
    │
    ├── Valid
    ├── Invalid
    ├── Duplicate
    ├── Incomplete
    ├── Obsolete
    └── Unmapped
```

---

# 11. Data Classification

Data should be classified according to organisational policy.

Potential classifications include:

- Public
- Internal
- Confidential
- Restricted
- Personal information
- Sensitive personal information
- Financial information
- Authentication information
- Payment information

Classification determines:

- Migration controls
- Encryption
- Access
- Handling
- Retention
- Logging
- Evidence
- Disposal

---

# 12. Data Ownership

Each migrated data set must have an identified owner.

| Data | Business Owner | Technical Owner | Approval |
|---|---|---|---|
| Users | Contact Centre | IAM | Required |
| Queues | Operations | Genesys Team | Required |
| Skills | Operations | Genesys Team | Required |
| Customer Data | Business | CRM Team | Required |
| Recordings | Operations | Platform Team | Required |
| Evaluations | Quality | Genesys Team | Required |
| WFM Data | WFM | WFM Team | Required |

---

# 13. Data Retention

Define:

- Source retention
- Target retention
- Historical retention
- Recording retention
- Evaluation retention
- Reporting retention
- Audit retention
- Legal hold
- Archival
- Disposal

Retention requirements must be confirmed before migration.

---

# 14. Privacy & Compliance

Migration must assess:

- PII
- Sensitive data
- Payment data
- Recording data
- Transcripts
- Customer identifiers
- Agent information
- Authentication data

The project should determine:

- What data may be migrated.
- What data must be transformed.
- What data must be masked.
- What data must remain in the source system.
- What data must be archived.
- What data must be deleted.

---

# 15. Migration Architecture

The migration architecture should define:

```text
Source Systems
      │
      ▼
Extraction Layer
      │
      ▼
Staging / Transformation
      │
      ▼
Validation
      │
      ▼
Migration Tooling
      │
      ▼
Genesys Cloud
      │
      ▼
Reconciliation
      │
      ▼
Business Acceptance
```

Where required, include:

- ETL
- APIs
- CSV
- Bulk operations
- Scripts
- Terraform
- Data Actions
- Integration middleware
- Custom migration applications
- Reporting/data warehouse processes

---

# 16. Migration Approach

Possible migration approaches include:

### Big Bang

All users and services move at once.

### Phased

Users, queues or business units migrate in controlled stages.

### Wave-Based

Groups of users or business functions migrate in waves.

### Parallel / Coexistence

Legacy and Genesys Cloud operate simultaneously for a defined period.

### Hybrid

Different migration strategies are used for different capabilities.

The approach must be selected based on:

- Risk
- Scale
- Complexity
- Business tolerance
- Technical dependencies
- Data migration requirements
- Telephony constraints

---

# 17. Migration Wave Strategy

For larger projects, define migration waves.

```text
Wave 0
Pilot / Technical Validation
      ↓
Wave 1
Low-Risk Business Group
      ↓
Wave 2
Standard Business Groups
      ↓
Wave 3
Complex Business Groups
      ↓
Wave 4
Remaining Users
      ↓
Legacy Retirement
```

Each wave should have:

- Scope
- Users
- Queues
- Numbers
- Integrations
- Data
- Cutover plan
- Validation
- Acceptance criteria
- Rollback

---

# 18. Migration Mapping

Create source-to-target mappings.

| Source Object | Target Object | Transformation | Validation |
|---|---|---|---|
| Legacy User | Genesys User | Attribute mapping | User count |
| Legacy Queue | Genesys Queue | Naming conversion | Queue count |
| Legacy Skill | Genesys Skill | Normalisation | Skill count |
| Legacy Number | Genesys DID | Number assignment | Call test |
| Legacy Flow | Architect Flow | Redesign | E2E test |

Mapping must identify objects that cannot be directly migrated.

---

# 19. Data Transformation

Transformation may include:

- Field renaming
- Data type conversion
- Value conversion
- Normalisation
- Time-zone conversion
- Date conversion
- Identifier generation
- String formatting
- Attribute mapping
- Status mapping
- Skill mapping
- Queue mapping

Transformation rules must be documented and testable.

---

# 20. Data Cleansing

Before migration:

- Remove duplicates.
- Correct invalid values.
- Remove obsolete records.
- Resolve missing identifiers.
- Resolve orphaned relationships.
- Standardise naming.
- Standardise formats.
- Validate required fields.

Data cleansing must be approved by the data owner.

---

# 21. Data Extraction

Extraction processes should define:

- Source
- Query
- Filter
- Scope
- Date range
- Record count
- Format
- Encryption
- Storage
- Access
- Validation

Extraction should produce an auditable dataset.

---

# 22. Data Staging

Where required, staging should provide:

- Controlled storage
- Encryption
- Access control
- Versioning
- Transformation
- Validation
- Audit logging
- Retention controls

Staging environments must not expose production data unnecessarily.

---

# 23. Data Loading

Loading may involve:

- Genesys Cloud APIs
- CSV imports
- Administrative interfaces
- Scripts
- Terraform
- Bulk operations
- Integration tooling
- Custom applications

Every loading process should provide:

- Error handling
- Logging
- Retry
- Validation
- Reconciliation

---

# 24. Configuration Migration

Configuration migration may include:

- Divisions
- Users
- Roles
- Permissions
- Groups
- Queues
- Skills
- Languages
- Wrap-up codes
- Routing rules
- Architect flows
- Data Tables
- Prompts
- Schedules
- Calendars
- Scripts
- Policies
- Integrations
- Data Actions
- Architect dependencies

Not every source configuration object will have a direct Genesys Cloud equivalent.

---

# 25. User Migration

Validate:

- User identity
- Name
- Email
- Employee ID
- Department
- Location
- Manager
- Division
- Role
- Queue membership
- Skills
- Languages
- Phone
- Station
- Supervisor relationship

User migration should integrate with the identity strategy established in Domain 02.

---

# 26. Queue Migration

For each queue determine:

- Queue name
- Queue description
- Division
- Members
- Skills
- Languages
- Routing method
- Service level
- Wrap-up
- Scripts
- Prompts
- Business hours
- Overflow
- Callback
- Emergency routing

---

# 27. Skill & Language Migration

Map:

- Source skill
- Target skill
- Skill name
- Skill type
- Proficiency
- Agent assignment
- Queue assignment
- Language
- Language proficiency

Proficiency scales must be normalised.

---

# 28. Routing Migration

Map legacy routing logic to Genesys Cloud.

Consider:

- Skill routing
- Bullseye routing
- Priority
- Queue evaluation
- Preferred agent
- Last agent
- Language
- Business rules
- Overflow
- Callback
- Emergency routing

Routing logic should be validated through end-to-end tests.

---

# 29. Architect Migration

Legacy IVR and call flows must be assessed for:

- Direct migration
- Redesign
- Rebuild
- Retirement

Migration should identify:

- Menus
- Prompts
- Variables
- Integrations
- Data access
- Routing
- Authentication
- Error handling
- Business hours
- Holidays
- Callbacks
- Queues

Architect flows should not be assumed to be one-to-one migrations.

---

# 30. Telephony Migration

Telephony migration may include:

- DID inventory
- Toll-free inventory
- Number ownership
- Carrier details
- Porting
- Number assignment
- SIP
- Edge requirements
- BYOC
- Cloud Voice
- Call routing
- Emergency services
- Caller ID

Number porting should be managed independently from configuration migration.

---

# 31. Digital Migration

Where applicable:

- Email
- Chat
- Web messaging
- SMS
- Social messaging
- Messaging integrations
- Bots
- Digital routing
- Customer identity

Digital migration may require customer-facing changes and therefore requires communications planning.

---

# 32. CRM / Customer Data Migration

Where applicable, determine:

- Customer master
- Contact information
- Customer identifiers
- Interaction context
- Case history
- Customer preferences
- Consent
- Customer attributes

Genesys Cloud should not become the authoritative system for data that belongs in the CRM unless explicitly designed that way.

---

# 33. Integration Migration

Inventory all integrations.

```text
Legacy Platform
      │
      ├── CRM
      ├── ERP
      ├── IAM
      ├── Data Warehouse
      ├── Reporting
      ├── Workforce
      ├── Payment
      ├── Customer Systems
      └── Custom Applications
```

For each integration determine:

- Source
- Target
- Protocol
- Authentication
- Data
- Direction
- Frequency
- Dependencies
- Error handling
- Migration approach

---

# 34. API Migration

Where applicable, assess:

- Legacy APIs
- Genesys Cloud APIs
- OAuth
- Client credentials
- User authentication
- Rate limits
- Data models
- API endpoints
- Error handling
- Retry
- Logging

API clients should be tested before cutover.

---

# 35. Historical Interaction Data

Historical interaction data may include:

- Interaction metadata
- Conversation identifiers
- Agent
- Queue
- Skills
- Time
- Disposition
- Customer information
- Historical reporting metrics

Determine whether each data set will be:

- Migrated
- Recreated
- Integrated
- Archived
- Retained in the legacy platform

---

# 36. Recording Migration

Recording migration is **Conditional**.

Assess:

- Recording volume
- File format
- Metadata
- Retention
- Search requirements
- Playback
- Legal requirements
- Compliance
- Storage
- Access
- Migration feasibility

Historical recordings may require archival rather than native migration.

---

# 37. Quality Data Migration

Where applicable, assess:

- Evaluation forms
- Evaluations
- Scores
- Evaluator
- Agent
- Interaction reference
- Coaching
- Feedback
- Calibration
- Quality history

Determine which historical quality information must remain accessible.

---

# 38. WFM Data Migration

Where applicable, assess:

- Users
- Groups
- Management units
- Historical schedules
- Forecast data
- Time-off
- Adherence
- Historical performance

Historical WFM data may be archived rather than migrated.

---

# 39. Reporting Data Migration

Assess:

- Historical reports
- Report definitions
- Metrics
- Data warehouse
- Dashboards
- Scheduled reports
- Business intelligence
- Data retention

Determine whether historical reporting will:

- Be recreated.
- Be rebuilt.
- Remain in the legacy platform.
- Be archived.
- Be migrated to a data warehouse.

---

# 40. Migration Tooling

Tooling may include:

- Genesys Cloud APIs
- CLI
- Terraform
- Node.js
- Python
- PowerShell
- CSV
- JSON
- ETL tools
- Middleware
- Integration platforms
- Custom migration utilities

Tooling should be version-controlled where practical.

---

# 41. Migration Automation

Automation should be considered for:

- User creation
- Queue creation
- Skill creation
- Membership
- Configuration
- Data loading
- Validation
- Reconciliation
- Reporting

Automation should be idempotent where possible.

---

# 42. Migration Logging

Migration tooling should record:

- Start time
- End time
- Source record
- Target record
- Action
- Status
- Error
- Retry
- Operator
- Batch
- Migration wave

Example:

```text
Source ID
   ↓
Transformation
   ↓
Target ID
   ↓
Migration Status
   ↓
Validation Status
```

---

# 43. Mock Migration

A mock migration should be executed before production migration for material migrations.

The mock should validate:

- Extraction
- Transformation
- Loading
- Timing
- Errors
- Reconciliation
- Validation
- Resource requirements

The mock should identify improvements before production.

---

# 44. Migration Rehearsal

The migration rehearsal should replicate the production cutover as closely as possible.

Validate:

- Task sequence
- Duration
- Dependencies
- Personnel
- Data volumes
- Tooling
- Communications
- Validation
- Rollback

The rehearsal should produce an updated cutover plan.

---

# 45. Delta Migration

Delta migration is **Conditional**.

It is required when data changes between the mock migration and final cutover.

Typical sequence:

```text
Initial Migration
      ↓
Business Continues
      ↓
Changes Accumulate
      ↓
Change Freeze
      ↓
Delta Extraction
      ↓
Delta Transformation
      ↓
Delta Load
      ↓
Reconciliation
```

---

# 46. Data Freeze

Where required, define:

- Freeze date/time
- Systems affected
- Users affected
- Business process affected
- Exception process
- Approval
- Communications
- Validation

The freeze must be coordinated with business operations.

---

# 47. Coexistence

Coexistence may be required when:

- Migration occurs in waves.
- Business units transition separately.
- Telephony requires staged porting.
- Historical data remains in legacy systems.
- Integrations cannot be migrated simultaneously.

Coexistence requires:

- Routing strategy
- Data ownership
- Support model
- Reporting model
- Customer experience controls
- Security
- Reconciliation

---

# 48. Transition Management

Transition management coordinates the movement from project implementation to operational ownership.

Transition includes:

- People
- Process
- Technology
- Documentation
- Support
- Monitoring
- Incident management
- Change management
- Reporting
- Governance

---

# 49. Rollback & Recovery

The migration plan must define rollback.

Potential triggers include:

- Data corruption
- Incorrect user assignments
- Incorrect routing
- Telephony failure
- Critical integration failure
- Security failure
- Reconciliation failure
- Business-critical functionality unavailable

Rollback should include:

- Decision maker
- Trigger
- Procedure
- Owner
- Communications
- Technical recovery
- Validation
- Business acceptance

---

# 50. Migration Validation

Validation should occur at multiple levels.

### Technical

- Records loaded
- Configuration created
- APIs successful
- No load errors

### Data

- Record counts
- Field values
- Relationships
- Identifiers
- Duplicates

### Functional

- Users can log in.
- Routing works.
- Flows work.
- Integrations work.

### Business

- Business scenarios work.
- Users accept migrated configuration.
- Reports are usable.
- Customer journeys work.

---

# 51. Data Reconciliation

Reconciliation is mandatory for material migration.

Example:

```text
SOURCE
1,000 Users
10,000 Queue Memberships
500 Skills
5,000,000 Historical Records
        │
        ▼
MIGRATION
        │
        ▼
TARGET
1,000 Users
10,000 Queue Memberships
500 Skills
5,000,000 Historical Records
        │
        ▼
RECONCILIATION
        │
        ├── Match
        ├── Missing
        ├── Duplicate
        ├── Invalid
        └── Unresolved
```

Reconciliation should compare:

- Counts
- IDs
- Relationships
- Critical fields
- Status
- Business rules

---

# 52. Migration Reconciliation Matrix

| Object | Source Count | Target Count | Difference | Status |
|---|---:|---:|---:|---|
| Users | 0 | 0 | 0 | Pending |
| Queues | 0 | 0 | 0 | Pending |
| Skills | 0 | 0 | 0 | Pending |
| Queue Memberships | 0 | 0 | 0 | Pending |
| Numbers | 0 | 0 | 0 | Pending |
| Flows | 0 | 0 | 0 | Pending |

Project-specific values are populated during migration execution.

---

# 53. Post-Migration Validation

Post-migration validation should verify:

- User access
- Queue membership
- Skills
- Routing
- Architect
- Telephony
- Digital
- Integrations
- Reporting
- Recording
- Quality
- WFM
- Security
- Data

---

# 54. Migration Defect Management

Migration defects should be classified separately from general project defects.

Examples:

- Missing records
- Duplicate records
- Incorrect mapping
- Incorrect transformation
- Invalid target configuration
- Missing user
- Incorrect skill
- Incorrect queue
- Incorrect routing
- Incorrect permissions

---

# 55. Migration Hypercare

Migration hypercare should monitor:

- User access
- Queue membership
- Routing
- Telephony
- Digital
- Integrations
- Data
- Reporting
- Recording
- WFM
- Security

Migration-specific issues should have dedicated ownership until stable.

---

# 56. Operational Handover

Handover should include:

- Migration documentation
- Data mapping
- Migration scripts
- Migration tooling
- Reconciliation reports
- Known limitations
- Archive locations
- Legacy access
- Support procedures
- Ownership

---

# 57. Legacy Platform Transition

After successful migration, define:

- Read-only period
- Continued support
- Historical access
- Data retention
- Integration retirement
- Number retirement
- User retirement
- License retirement

The legacy system should not be decommissioned until explicit approval is obtained.

---

# 58. Data Archival

Where data cannot or should not be migrated, define:

- Archive platform
- Data set
- Retention
- Access
- Security
- Encryption
- Search
- Legal hold
- Disposal

Archived data must remain discoverable for its required retention period.

---

# 59. Legacy Decommissioning

Decommissioning may include:

- Disable integrations
- Remove routing
- Retire telephony
- Release numbers
- Disable users
- Remove access
- Archive data
- Remove infrastructure
- Cancel licenses
- Terminate contracts

Decommissioning must be a separate controlled change.

---

# 60. Migration Closure

Migration closure should confirm:

- All migration tasks complete.
- Reconciliation complete.
- Outstanding issues transferred.
- Business acceptance complete.
- Data ownership transferred.
- Documentation complete.
- Archives complete.
- Legacy strategy confirmed.
- Support ownership transferred.
- Lessons learned captured.

---

# 61. Layer 1 Mapping

| Layer 1 Phase | Migration / Transition Activities |
|---|---|
| Phase 1 — Initiation | Define migration governance |
| Phase 2 — Discovery | Inventory source systems and data |
| Phase 3 — Requirements | Define migration requirements |
| Phase 4 — Architecture | Define migration architecture |
| Phase 5 — Platform Foundation | Prepare migration environments |
| Phase 6 — Solution Build | Build target configuration |
| Phase 7 — Integration & Migration | Execute migration preparation and mock migration |
| Phase 8 — Testing | Validate migrated data and configuration |
| Phase 9 — Operational Readiness | Validate transition readiness |
| Phase 10 — Production Deployment | Execute production migration |
| Phase 11 — Hypercare | Reconcile and stabilise migration |
| Phase 12 — BAU Handover | Transfer ownership and close migration |

---

# 62. Cross-Domain Dependencies

| Domain | Migration Dependency |
|---|---|
| 01 — Core Platform | Target organisation and configuration |
| 02 — Identity & Access | User identity and access migration |
| 03 — Voice & Telephony | Number and telephony transition |
| 04 — ACD Routing | Queue, skill and routing migration |
| 05 — Architect | Flow migration / rebuild |
| 06 — Digital | Digital channel transition |
| 07 — WFM | Workforce migration |
| 08 — Data & Integrations | Integration and API migration |
| 09 — Analytics | Historical reporting |
| 10 — Quality | Recording and evaluation migration |
| 11 — Security | Data handling and access controls |
| 12 — Testing | Migration validation |
| 13 — Migration | Current domain |
| 14 — Operations | Transition and BAU ownership |
| 15 — Optimisation | Post-migration optimisation |

---

# 63. Migration Governance Model

```text
                    Project Steering Committee
                              │
                              ▼
                     Migration Governance
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
       Migration Lead    Technical Lead    Business Owner
             │                │                │
             └────────────────┼────────────────┘
                              ▼
                     Migration Workstreams
                              │
       ┌──────────────┬───────┼───────┬──────────────┐
       ▼              ▼       ▼       ▼              ▼
      Data          Config   Voice   Integrations   Legacy
       │              │       │       │              │
       └──────────────┴───────┼───────┴──────────────┘
                              ▼
                       Validation / QA
                              │
                              ▼
                         Acceptance
```

---

# 64. Migration Workstreams

The migration project should generally be structured into:

```text
Migration
│
├── Migration Management
├── Source Assessment
├── Data Discovery
├── Data Governance
├── Data Cleansing
├── Data Mapping
├── Data Transformation
├── Configuration Migration
├── User Migration
├── Routing Migration
├── Telephony Migration
├── Digital Migration
├── Integration Migration
├── Historical Data
├── Recording
├── Quality
├── WFM
├── Reporting
├── Migration Tooling
├── Mock Migration
├── Rehearsal
├── Cutover
├── Validation
├── Reconciliation
├── Transition
├── Hypercare
├── Archival
└── Decommissioning
```

---

# 65. Migration Risk Management

| Risk | Impact | Mitigation |
|---|---|---|
| Unknown source data | High | Discovery and profiling |
| Poor data quality | High | Cleansing |
| Incorrect mapping | Critical | Mapping review |
| Unsupported target capability | Critical | Early gap assessment |
| Large data volume | High | Migration sizing |
| Migration exceeds window | Critical | Mock migration |
| Data corruption | Critical | Validation and rollback |
| Missing historical data | High | Retention strategy |
| Incorrect routing | Critical | End-to-end testing |
| Incorrect permissions | Critical | Access validation |
| Telephony migration failure | Critical | Porting and cutover rehearsal |
| Integration failure | Critical | Integration testing |
| Legacy dependencies | High | Dependency inventory |
| Business unavailable | High | Early scheduling |
| Incomplete reconciliation | Critical | Formal reconciliation |
| Premature legacy decommission | Critical | Decommission gate |
| Regulatory breach | Critical | Compliance assessment |

---

# 66. Migration Critical Path

A typical migration critical path is:

```text
Source Discovery
      ↓
Data Assessment
      ↓
Migration Design
      ↓
Mapping
      ↓
Transformation
      ↓
Mock Migration
      ↓
Migration Rehearsal
      ↓
Cutover Readiness
      ↓
Data Freeze
      ↓
Production Migration
      ↓
Reconciliation
      ↓
Business Validation
      ↓
Production Acceptance
      ↓
Legacy Transition
```

Potential critical-path blockers include:

- Data mapping approval
- Data cleansing
- Migration tooling
- Telephony porting
- Integration readiness
- Migration rehearsal
- Business availability
- Reconciliation
- Production acceptance

---

# 67. Migration Wave Sequence

```text
1. Define Migration Strategy
2. Inventory Source Systems
3. Identify Data
4. Classify Data
5. Identify Data Owners
6. Define Retention
7. Assess Migration Feasibility
8. Define Source-to-Target Mapping
9. Define Transformation
10. Cleanse Data
11. Build Migration Tooling
12. Extract Data
13. Transform Data
14. Load Test Data
15. Validate Migration
16. Execute Mock Migration
17. Remediate Issues
18. Execute Migration Rehearsal
19. Finalise Cutover
20. Freeze Source Changes
21. Extract Final Data
22. Execute Delta Migration
23. Validate Target
24. Reconcile Source and Target
25. Execute Business Validation
26. Obtain Acceptance
27. Transition Support
28. Enter Hypercare
29. Archive Legacy Data
30. Decommission Legacy Components
31. Close Migration
```

---

# 68. Migration Acceptance Criteria

Migration acceptance should include:

### Data

- Required records migrated.
- Required attributes migrated.
- Relationships preserved.
- Reconciliation completed.

### Configuration

- Users correct.
- Queues correct.
- Skills correct.
- Routing correct.
- Architect correct.

### Telephony

- Required numbers active.
- Routing operational.
- Caller ID validated.

### Integrations

- Critical integrations operational.
- Authentication validated.
- Error handling validated.

### Business

- Critical customer journeys work.
- Users can perform their roles.
- Reporting is available.
- Business owner accepts migration.

---

# 69. Migration Reconciliation Gate

The migration must not proceed to final acceptance until:

```text
Source Count
     =
Target Count
     +
Approved Exceptions
```

And:

```text
Source Data
     ↔
Target Data
     ↔
Business Rules
```

All exceptions must be:

- Identified
- Classified
- Owned
- Documented
- Accepted or remediated

---

# 70. Migration Cutover Checklist

```text
[ ] Migration strategy approved
[ ] Source systems inventoried
[ ] Data owners identified
[ ] Data classification completed
[ ] Retention approved
[ ] Mapping approved
[ ] Transformation approved
[ ] Cleansing complete
[ ] Migration tooling tested
[ ] Mock migration complete
[ ] Migration rehearsal complete
[ ] Cutover plan approved
[ ] Rollback plan approved
[ ] Business communications complete
[ ] Change freeze activated
[ ] Final extraction complete
[ ] Delta migration complete
[ ] Target validation complete
[ ] Reconciliation complete
[ ] Business validation complete
[ ] Migration accepted
[ ] Hypercare activated
```

---

# 71. Post-Migration Validation Checklist

```text
[ ] Users migrated
[ ] User permissions validated
[ ] Queue membership validated
[ ] Skills validated
[ ] Routing validated
[ ] Architect validated
[ ] Telephony validated
[ ] Digital validated
[ ] Integrations validated
[ ] APIs validated
[ ] Reporting validated
[ ] Recording validated
[ ] Quality validated
[ ] WFM validated
[ ] Historical data validated
[ ] Security validated
[ ] Compliance validated
[ ] Reconciliation complete
[ ] Business acceptance complete
```

---

# 72. Legacy Decommissioning Checklist

```text
[ ] Business acceptance obtained
[ ] Historical data strategy approved
[ ] Data archived where required
[ ] Legacy integrations disabled
[ ] Legacy routing removed
[ ] Telephony retired
[ ] Numbers released where applicable
[ ] Legacy users disabled
[ ] Legacy access removed
[ ] Licenses cancelled
[ ] Contracts reviewed
[ ] Support terminated
[ ] Legacy platform decommissioned
[ ] Decommissioning validated
[ ] Evidence archived
```

---

# 73. Migration Artefacts

The project should produce:

- Migration strategy
- Migration plan
- Source system inventory
- Data inventory
- Data classification matrix
- Data ownership matrix
- Data retention matrix
- Migration architecture
- Source-to-target mapping
- Transformation rules
- Data cleansing plan
- Extraction procedures
- Loading procedures
- Migration scripts
- Migration tooling
- Migration logs
- Migration test cases
- Mock migration report
- Migration rehearsal report
- Cutover plan
- Rollback plan
- Data freeze plan
- Reconciliation report
- Migration acceptance
- Transition plan
- Legacy archival plan
- Legacy decommission plan
- Migration closure report
- Lessons learned

---

# 74. Migration Responsibility Model

| Activity | Partner | Customer | Shared |
|---|---:|---:|---:|
| Migration Strategy | Lead | Approve | Yes |
| Source Discovery | Lead | Support | Yes |
| Data Ownership | Support | Lead | Yes |
| Data Classification | Support | Lead | Yes |
| Data Cleansing | Support | Lead | Yes |
| Mapping | Lead | Approve | Yes |
| Transformation | Lead | Review | Yes |
| Migration Tooling | Lead | Review | Yes |
| Mock Migration | Lead | Support | Yes |
| Rehearsal | Lead | Support | Yes |
| Production Migration | Lead | Approve | Yes |
| Reconciliation | Lead | Validate | Yes |
| Business Validation | Support | Lead | Yes |
| Legacy Decommissioning | Support | Lead | Yes |
| Data Archival | Support | Lead | Yes |
| Migration Closure | Lead | Approve | Yes |

Actual responsibility should be confirmed during project initiation.

---

# 75. Migration Tooling Standards

Where custom tooling is used:

- Store source code in version control.
- Use configuration rather than hard-coded values.
- Separate credentials from source code.
- Use service accounts appropriately.
- Log migration activity.
- Support retries.
- Validate input.
- Validate output.
- Make processes idempotent where practical.
- Maintain version history.
- Document execution procedures.
- Test against non-production data first.

---

# 76. Migration Security Controls

Migration processes must protect:

- Credentials
- OAuth tokens
- API keys
- Customer data
- PII
- Recordings
- Transcripts
- Agent data
- Reports
- Historical data

Controls should include:

- Least privilege
- Encryption
- Secure storage
- Access logging
- Data masking where appropriate
- Controlled migration accounts
- Credential rotation
- Secure disposal

---

# 77. Migration Monitoring

During migration monitor:

- Extraction status
- Transformation errors
- Load errors
- API failures
- Rate limits
- Record counts
- Duplicate records
- Failed records
- Processing time
- Data reconciliation
- Target availability

---

# 78. Migration Metrics

Track:

| Metric | Description |
|---|---|
| Source Records | Records available |
| Migrated Records | Records loaded |
| Failed Records | Records rejected |
| Duplicate Records | Duplicate target records |
| Reconciled Records | Records successfully matched |
| Exception Records | Records requiring review |
| Migration Duration | Total elapsed time |
| Error Rate | Migration errors |
| Validation Pass Rate | Successful validation |
| Business Acceptance | Accepted / rejected |

---

# 79. Domain Completion Definition

The Migration, Data Conversion & Transition domain is complete when:

- Migration strategy is approved.
- Migration scope is defined.
- Source systems are inventoried.
- Data is discovered.
- Data is profiled.
- Data is classified.
- Data owners are identified.
- Retention is defined.
- Compliance requirements are defined.
- Migration architecture is approved.
- Migration approach is approved.
- Source-to-target mappings are approved.
- Transformation rules are approved.
- Data cleansing is complete.
- Extraction is validated.
- Loading is validated.
- Configuration migration is validated.
- User migration is validated.
- Queue migration is validated.
- Skill migration is validated.
- Routing migration is validated.
- Architect migration is validated.
- Telephony migration is validated.
- Digital migration is validated where applicable.
- CRM/customer data migration is validated where applicable.
- Integration migration is validated.
- API migration is validated where applicable.
- Historical data strategy is approved.
- Recording strategy is approved where applicable.
- Quality data strategy is approved where applicable.
- WFM data strategy is approved where applicable.
- Reporting data strategy is approved where applicable.
- Migration tooling is ready.
- Migration automation is tested where applicable.
- Mock migration is complete.
- Migration rehearsal is complete.
- Cutover migration is planned.
- Delta migration is planned where required.
- Data freeze is planned where required.
- Coexistence is defined where required.
- Rollback is defined.
- Migration validation is complete.
- Reconciliation is complete.
- Post-migration validation is complete.
- Business acceptance is obtained.
- Hypercare is active.
- Operational handover is complete.
- Legacy transition is approved.
- Archival is complete where required.
- Decommissioning is complete where applicable.
- Migration closure is complete.

---

# 80. Domain Gate

```text
SOURCE DISCOVERY
       +
DATA ASSESSMENT
       +
MIGRATION ARCHITECTURE
       +
SOURCE-TO-TARGET MAPPING
       +
TRANSFORMATION / CLEANSING
       +
MIGRATION TOOLING
       +
MOCK MIGRATION
       +
MIGRATION REHEARSAL
       ↓
CUTOVER READINESS
       ↓
PRODUCTION MIGRATION
       ↓
VALIDATION
       +
RECONCILIATION
       +
BUSINESS ACCEPTANCE
       ↓
HYPERCARE
       ↓
OPERATIONAL HANDOVER
       ↓
LEGACY TRANSITION
       ↓
MIGRATION CLOSURE
```

---

# 81. Implementation Task Decomposition Preview

The final implementation catalogue should decompose this domain into atomic project tasks.

```text
MIG-013-001  Define migration strategy
MIG-013-002  Establish migration governance
MIG-013-003  Define migration roles
MIG-013-004  Define migration responsibilities
MIG-013-005  Define migration scope
MIG-013-006  Identify source systems
MIG-013-007  Inventory source applications
MIG-013-008  Inventory source contact centre configuration
MIG-013-009  Inventory source data
MIG-013-010  Identify data owners
MIG-013-011  Profile source data
MIG-013-012  Classify migration data
MIG-013-013  Define data retention requirements
MIG-013-014  Define privacy requirements
MIG-013-015  Define compliance requirements
MIG-013-016  Assess source-to-target compatibility
MIG-013-017  Identify unsupported migration objects
MIG-013-018  Define migration architecture
MIG-013-019  Select migration approach
MIG-013-020  Define migration waves
MIG-013-021  Define source-to-target mappings
MIG-013-022  Define transformation rules
MIG-013-023  Define data cleansing rules
MIG-013-024  Execute data cleansing
MIG-013-025  Develop extraction process
MIG-013-026  Develop staging process
MIG-013-027  Develop transformation process
MIG-013-028  Develop loading process
MIG-013-029  Develop migration logging
MIG-013-030  Develop migration validation
MIG-013-031  Develop reconciliation process
MIG-013-032  Migrate platform configuration
MIG-013-033  Migrate users
MIG-013-034  Migrate roles and permissions
MIG-013-035  Migrate divisions
MIG-013-036  Migrate queues
MIG-013-037  Migrate queue memberships
MIG-013-038  Migrate skills
MIG-013-039  Migrate languages
MIG-013-040  Migrate wrap-up codes
MIG-013-041  Migrate routing configuration
MIG-013-042  Migrate Architect configuration
MIG-013-043  Migrate prompts
MIG-013-044  Migrate schedules
MIG-013-045  Migrate calendars
MIG-013-046  Migrate telephony configuration
MIG-013-047  Migrate telephone numbers
MIG-013-048  Execute number porting activities
MIG-013-049  Migrate digital configuration
MIG-013-050  Migrate CRM integration configuration
MIG-013-051  Migrate customer data where applicable
MIG-013-052  Migrate external integrations
MIG-013-053  Migrate API integrations
MIG-013-054  Define historical interaction strategy
MIG-013-055  Define recording migration strategy
MIG-013-056  Define quality data migration strategy
MIG-013-057  Define WFM migration strategy
MIG-013-058  Define reporting migration strategy
MIG-013-059  Build migration automation
MIG-013-060  Execute initial test migration
MIG-013-061  Validate test migration
MIG-013-062  Remediate migration defects
MIG-013-063  Execute mock migration
MIG-013-064  Measure migration duration
MIG-013-065  Validate mock migration
MIG-013-066  Reconcile mock migration
MIG-013-067  Update migration tooling
MIG-013-068  Execute migration rehearsal
MIG-013-069  Validate migration rehearsal
MIG-013-070  Finalise cutover migration plan
MIG-013-071  Finalise rollback plan
MIG-013-072  Define data freeze
MIG-013-073  Define coexistence strategy
MIG-013-074  Prepare final migration dataset
MIG-013-075  Execute final extraction
MIG-013-076  Execute final transformation
MIG-013-077  Execute final load
MIG-013-078  Execute delta migration
MIG-013-079  Validate migrated configuration
MIG-013-080  Validate migrated users
MIG-013-081  Validate queues and memberships
MIG-013-082  Validate skills and languages
MIG-013-083  Validate routing
MIG-013-084  Validate Architect
MIG-013-085  Validate telephony
MIG-013-086  Validate digital
MIG-013-087  Validate integrations
MIG-013-088  Validate APIs
MIG-013-089  Validate historical data
MIG-013-090  Validate recordings
MIG-013-091  Validate quality data
MIG-013-092  Validate WFM data
MIG-013-093  Validate reporting
MIG-013-094  Execute source-to-target reconciliation
MIG-013-095  Resolve migration exceptions
MIG-013-096  Execute business validation
MIG-013-097  Obtain migration acceptance
MIG-013-098  Activate migration hypercare
MIG-013-099  Monitor migration stability
MIG-013-100  Manage migration defects
MIG-013-101  Complete operational handover
MIG-013-102  Transfer migration tooling
MIG-013-103  Transfer migration documentation
MIG-013-104  Finalise historical data archive
MIG-013-105  Finalise legacy access
MIG-013-106  Disable legacy integrations
MIG-013-107  Retire legacy routing
MIG-013-108  Retire legacy telephony
MIG-013-109  Disable legacy users
MIG-013-110  Decommission legacy platform
MIG-013-111  Validate decommissioning
MIG-013-112  Complete migration closure
MIG-013-113  Archive migration evidence
MIG-013-114  Conduct migration lessons learned
MIG-013-115  Update deployment methodology
```

The eventual spreadsheet should expand these tasks further where required.

---

# 82. Detailed Implementation Task Attributes

Each task should ultimately include:

| Field | Description |
|---|---|
| Task ID | Unique task identifier |
| Layer | Layer 2 |
| Domain | 13 |
| Phase | Layer 1 phase |
| Workstream | Migration / Transition |
| Capability | Applicable capability |
| Task | Atomic activity |
| Description | Detailed implementation activity |
| Classification | Required / Conditional / Optional |
| Dependency | Predecessor tasks |
| Role | Primary delivery owner |
| Customer Responsibility | Customer activity |
| Environment | DEV / SIT / UAT / PROD |
| Effort | Estimated hours |
| Duration | Elapsed time |
| Deliverable | Output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |
| Evidence | Migration evidence |
| Approval | Required approver |

---

# 83. Migration Task Sequencing

The eventual project schedule should generally follow:

```text
Discovery
    ↓
Assessment
    ↓
Data Governance
    ↓
Migration Architecture
    ↓
Mapping
    ↓
Transformation
    ↓
Cleansing
    ↓
Tooling
    ↓
Test Migration
    ↓
Mock Migration
    ↓
Rehearsal
    ↓
Cutover Preparation
    ↓
Final Migration
    ↓
Reconciliation
    ↓
Business Acceptance
    ↓
Hypercare
    ↓
Transition
    ↓
Archival
    ↓
Decommissioning
```

---

# 84. Migration Critical Dependencies

Migration tasks may depend upon:

- Approved requirements
- Approved solution architecture
- Target Genesys Cloud organisation
- Identity configuration
- Telephony configuration
- Queue configuration
- Routing configuration
- Architect configuration
- Integration configuration
- Security approval
- Data owner approval
- Business availability
- Test completion
- Cutover approval

---

# 85. Migration Effort Considerations

Effort must be estimated based on:

### Data

- Number of source systems
- Number of data objects
- Data volume
- Data quality
- Data transformation complexity

### Configuration

- Number of users
- Number of queues
- Number of skills
- Number of flows
- Number of business units
- Number of divisions

### Integration

- Number of integrations
- API complexity
- Authentication
- Transformation
- External dependencies

### Telephony

- Number of telephone numbers
- Porting complexity
- Carrier requirements
- Geographic requirements
- Emergency service requirements

### Historical Data

- Record volume
- Recording volume
- Retention
- Archive requirements
- Search requirements

### Cutover

- Number of migration waves
- Migration window
- Business availability
- Rollback complexity
- Coexistence requirements

---

# 86. Migration Estimation Categories

The final workbook should distinguish:

- Discovery effort
- Design effort
- Development effort
- Configuration effort
- Data cleansing effort
- Migration tooling effort
- Test migration effort
- Mock migration effort
- Rehearsal effort
- Production migration effort
- Validation effort
- Reconciliation effort
- Hypercare effort
- Archival effort
- Decommissioning effort

---

# 87. Migration Go / No-Go Criteria

Migration should not proceed unless:

```text
Data Mapping Approved
        +
Migration Tooling Validated
        +
Mock Migration Passed
        +
Reconciliation Passed
        +
Migration Rehearsal Passed
        +
Rollback Validated
        +
Business Approval
        +
Operational Readiness
        ↓
      GO
```

---

# 88. Migration Completion Gate

The final migration gate requires:

```text
SOURCE DATA ASSESSED
        +
MIGRATION MAPPING APPROVED
        +
DATA QUALITY ACCEPTED
        +
MIGRATION TOOLING TESTED
        +
MOCK MIGRATION PASSED
        +
REHEARSAL PASSED
        +
CUTOVER APPROVED
        ↓
FINAL MIGRATION
        ↓
RECONCILIATION
        +
VALIDATION
        +
BUSINESS ACCEPTANCE
        ↓
HYPERCARE
        ↓
OPERATIONAL HANDOVER
        ↓
LEGACY TRANSITION
        ↓
CLOSURE
```

---

# 89. Definition of Done

Domain 13 is complete when:

1. Migration scope is approved.
2. Source systems are inventoried.
3. Source data is identified.
4. Data ownership is established.
5. Data classification is complete.
6. Data retention is approved.
7. Privacy requirements are approved.
8. Migration architecture is approved.
9. Migration approach is approved.
10. Migration waves are defined.
11. Source-to-target mappings are approved.
12. Transformation rules are approved.
13. Data cleansing is complete.
14. Extraction procedures are validated.
15. Loading procedures are validated.
16. Migration tooling is tested.
17. Migration logging is operational.
18. Configuration migration is validated.
19. User migration is validated.
20. Queue migration is validated.
21. Skill and language migration is validated.
22. Routing migration is validated.
23. Architect migration is validated.
24. Telephony migration is validated.
25. Digital migration is validated where applicable.
26. CRM/customer data migration is validated where applicable.
27. Integration migration is validated.
28. API migration is validated where applicable.
29. Historical data strategy is approved.
30. Recording strategy is approved where applicable.
31. Quality data strategy is approved where applicable.
32. WFM data strategy is approved where applicable.
33. Reporting migration strategy is approved where applicable.
34. Mock migration is complete.
35. Migration rehearsal is complete.
36. Cutover plan is approved.
37. Rollback plan is approved.
38. Data freeze is approved where required.
39. Coexistence strategy is approved where required.
40. Production migration is complete.
41. Migration validation is complete.
42. Reconciliation is complete.
43. Exceptions are resolved or accepted.
44. Business validation is complete.
45. Migration acceptance is obtained.
46. Hypercare is complete or formally transitioned.
47. Operational handover is complete.
48. Legacy transition is approved.
49. Data archival is complete where required.
50. Legacy decommissioning is complete where applicable.
51. Migration evidence is archived.
52. Migration closure is complete.
53. Lessons learned are captured.

---

# 90. Domain Completion

**Layer:** 2  
**Domain:** 13 — Migration, Data Conversion & Transition  
**Capability Catalogue:** Complete  
**Status:** Baseline capability catalogue complete

The domain defines the migration capabilities required to move from the existing contact centre environment into Genesys Cloud.

The final implementation workbook will convert these capabilities into detailed project tasks and sequence them against Layer 1.

The final workbook will contain:

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

# 91. Domain Completion Gate

```text
MIGRATION STRATEGY
        +
SOURCE DISCOVERY
        +
DATA GOVERNANCE
        +
MIGRATION ARCHITECTURE
        +
MAPPING
        +
TRANSFORMATION
        +
CLEANSING
        +
MIGRATION TOOLING
        +
MOCK MIGRATION
        +
REHEARSAL
        ↓
PRODUCTION MIGRATION
        ↓
VALIDATION
        +
RECONCILIATION
        +
BUSINESS ACCEPTANCE
        ↓
HYPERCARE
        ↓
OPERATIONAL HANDOVER
        ↓
LEGACY TRANSITION
        ↓
MIGRATION CLOSURE
```

---
