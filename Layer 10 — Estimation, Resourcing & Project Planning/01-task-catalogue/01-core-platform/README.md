# 01 — Core Platform Task Catalogue

## Layer 10 — Estimation, Resourcing & Project Planning

## 1. Purpose

This directory contains the **Layer 10 implementation task catalogue for the Core Platform capability domain**.

The Core Platform domain establishes the foundational Genesys Cloud organisation, platform configuration, tenancy, regional, environmental, and organisational structures upon which the remaining Genesys Cloud solution is built.

The task catalogue translates the Layer 2 Core Platform capabilities and their implementation activities into discrete, estimable, assignable, and schedulable implementation tasks.

---

# 2. Domain Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Task Catalogue Domain | 01 — Core Platform |
| Layer 2 Domain | 01 — Core Platform |
| Domain Type | Foundation |
| Primary Purpose | Establish and validate the Genesys Cloud platform foundation |
| Primary Delivery Roles | Solution Architect, Genesys Cloud Architect, Genesys Cloud Engineer, Technical Architect |
| Primary Customer Roles | Customer Platform Owner, Customer Technical Lead, Customer Security Lead |
| Primary Environments | Design, DEV, TEST, UAT, PROD |
| Primary Layer 1 Phases | P01–P12 |
| Task Catalogue Status | In Development |

---

# 3. Relationship to Layer 2

The authoritative capability definitions for this domain are maintained within:

```text
Layer 2
└── 01-Core-Platform
```

Layer 10 does not redefine the capability catalogue.

Instead, this task catalogue takes the Layer 2 implementation activities and decomposes them into individual implementation tasks.

The relationship is:

```text
Layer 2
01 — Core Platform
        │
        ├── Capability
        │       │
        │       └── Implementation Activity
        │                     │
        │                     ▼
        │              Layer 10 Task Catalogue
        │                     │
        │                     ├── Task
        │                     ├── Task
        │                     └── Task
        │
        └── Capability
                │
                └── Implementation Activity
                              │
                              ▼
                       Layer 10 Task Catalogue
```

---

# 4. Domain Objective

The objective of the Core Platform Task Catalogue is to ensure that every project establishes a consistent, secure, supportable, and validated Genesys Cloud foundation before dependent capabilities are implemented.

The catalogue must account for:

- Genesys Cloud organisation establishment
- region selection
- data residency
- organisation settings
- divisions
- business units
- locations
- sites
- time zones
- business hours
- holiday schedules
- languages
- media types
- platform defaults
- licensing and feature entitlements
- storage and retention
- platform limits and capacity
- environment strategy
- platform validation

---

# 5. Core Platform Capabilities

The Core Platform domain contains the following Layer 2 capabilities.

| Capability ID | Capability | Task Catalogue File | Status |
|---|---|---|---|
| 2.01.01 | Genesys Cloud Organisation | `01-genesys-cloud-organisation.md` | Planned |
| 2.01.02 | Region & Data Residency | `02-region-data-residency.md` | Planned |
| 2.01.03 | Organisation Settings | `03-organisation-settings.md` | Planned |
| 2.01.04 | Divisions | `04-divisions.md` | Planned |
| 2.01.05 | Business Units | `05-business-units.md` | Planned |
| 2.01.06 | Locations | `06-locations.md` | Planned |
| 2.01.07 | Sites | `07-sites.md` | Planned |
| 2.01.08 | Time Zones | `08-time-zones.md` | Planned |
| 2.01.09 | Business Hours | `09-business-hours.md` | Planned |
| 2.01.10 | Holidays | `10-holidays.md` | Planned |
| 2.01.11 | Languages | `11-languages.md` | Planned |
| 2.01.12 | Media Types | `12-media-types.md` | Planned |
| 2.01.13 | Platform Defaults | `13-platform-defaults.md` | Planned |
| 2.01.14 | Licensing & Feature Entitlements | `14-licensing-feature-entitlement.md` | Planned |
| 2.01.15 | Storage & Retention | `15-storage-retention.md` | Planned |
| 2.01.16 | Platform Limits & Capacity | `16-platform-limits-capacity.md` | Planned |
| 2.01.17 | Environment Strategy | `17-environment-strategy.md` | Planned |
| 2.01.18 | Core Platform Validation | `18-core-platform-validation.md` | Planned |

---

# 6. Capability-to-Task Structure

Each capability will follow the standard Layer 10 hierarchy:

```text
01 — Core Platform
        │
        ├── 2.01.01 — Genesys Cloud Organisation
        │       │
        │       ├── Implementation Activity
        │       │       ├── Task
        │       │       ├── Task
        │       │       └── Task
        │       │
        │       └── Implementation Activity
        │               ├── Task
        │               └── Task
        │
        ├── 2.01.02 — Region & Data Residency
        │       │
        │       └── Implementation Activities
        │               └── Implementation Tasks
        │
        └── ...
```

Each individual capability document is the authoritative Layer 10 location for the tasks associated with that capability.

---

# 7. Task ID Convention

Core Platform tasks use the Layer 10 task ID format:

```text
L10-01.CC-TTT
```

Where:

| Component | Meaning |
|---|---|
| `L10` | Layer 10 |
| `01` | Core Platform domain |
| `CC` | Capability number |
| `TTT` | Sequential task number |

Examples:

```text
L10-01.01-001
L10-01.01-002
L10-01.01-003
```

These represent tasks within:

```text
Domain 01 — Core Platform
Capability 01 — Genesys Cloud Organisation
```

For capability 14:

```text
L10-01.14-001
```

represents:

```text
Domain 01 — Core Platform
Capability 14 — Licensing & Feature Entitlements
Task 001
```

---

# 8. Layer 1 Mapping

Every Core Platform task must map to one or more applicable Layer 1 deployment phases.

Core Platform activities are expected to span the deployment lifecycle rather than being restricted to a single phase.

Typical mappings include:

| Layer 1 Phase | Core Platform Relationship |
|---|---|
| P01 — Project Initiation & Mobilisation | Platform ownership, project assumptions, initial provisioning requirements |
| P02 — Discovery & Current-State Assessment | Current platform, tenancy, regional and organisational assessment |
| P03 — Requirements & Solution Definition | Platform requirements and constraints |
| P04 — Solution Architecture & Detailed Design | Organisation, division, environment and platform architecture |
| P05 — Platform Foundation & Environment Build | Core platform provisioning and foundational configuration |
| P06 — Configuration & Development | Platform configuration and supporting settings |
| P07 — Integration & Data Enablement | Platform dependencies supporting integrations |
| P08 — Testing, Validation & Defect Resolution | Core platform validation |
| P09 — Operational Readiness & Training | Platform operational documentation and readiness |
| P10 — Go-Live Preparation & Cutover | Production readiness |
| P11 — Go-Live & Hypercare | Production validation and early-life support |
| P12 — BAU Handover & Project Closure | Platform handover and operational ownership |

The exact Layer 1 mapping must be defined at the individual task level.

---

# 9. Core Platform Implementation Sequence

The baseline implementation sequence should generally follow:

```text
01
Organisation & tenancy requirements
        │
        ▼
02
Region & data residency
        │
        ▼
03
Organisation settings
        │
        ▼
04
Divisions
        │
        ▼
05
Business units
        │
        ▼
06
Locations
        │
        ▼
07
Sites
        │
        ▼
08
Time zones
        │
        ▼
09
Business hours
        │
        ▼
10
Holiday schedules
        │
        ▼
11
Languages
        │
        ▼
12
Media types
        │
        ▼
13
Platform defaults
        │
        ▼
14
Licensing & feature entitlements
        │
        ▼
15
Storage & retention
        │
        ▼
16
Platform limits & capacity
        │
        ▼
17
Environment strategy
        │
        ▼
18
Core platform validation
```

This is the **baseline logical dependency sequence**.

Actual project sequencing may vary depending on:

- existing organisation versus new organisation
- migration strategy
- environment model
- customer architecture
- licensing model
- implementation methodology
- automation approach
- customer approval dependencies
- Genesys Cloud product capabilities
- integration requirements

---

# 10. Domain-Level Dependencies

The Core Platform domain has dependencies on activities outside the domain.

Typical upstream dependencies include:

```text
Project Initiation
        ↓
Customer Stakeholder Identification
        ↓
Discovery
        ↓
Requirements
        ↓
Solution Architecture
        ↓
Core Platform
```

Core Platform tasks may also depend upon:

- customer tenancy decisions
- licensing decisions
- contractual scope
- data residency requirements
- regulatory requirements
- security requirements
- network architecture
- identity architecture
- environment strategy
- migration strategy
- integration architecture

---

# 11. Downstream Dependencies

The Core Platform domain is a major dependency for many subsequent domains.

Examples include:

```text
Core Platform
      │
      ├── Identity & Access
      │
      ├── Voice & Telephony
      │
      ├── ACD & Routing
      │
      ├── Architect
      │
      ├── Digital
      │
      ├── WFM & Employee Engagement
      │
      ├── Data, Integrations & APIs
      │
      ├── Analytics & Reporting
      │
      ├── Quality Management
      │
      ├── Security & Governance
      │
      ├── Testing & Deployment
      │
      ├── Migration
      │
      ├── Operations
      │
      └── Optimisation
```

The Core Platform domain should therefore be treated as a **foundational dependency domain**.

---

# 12. Cross-Domain Dependency Considerations

Individual capability tasks should explicitly identify dependencies where applicable.

Examples include:

### Identity & Access

Core Platform configuration may be required before:

- users are provisioned
- roles are assigned
- groups are configured
- authentication is validated

### Voice & Telephony

Core Platform configuration may be required before:

- phone numbers are assigned
- sites are configured
- telephony settings are validated

### ACD & Routing

Core Platform structures may be required before:

- queues are configured
- divisions are assigned
- routing objects are deployed

### Architect

Core Platform settings may be required before:

- flows are deployed
- language configuration is validated
- schedules are applied

### Analytics

Core Platform structures may influence:

- reporting
- divisions
- business units
- operational views

---

# 13. Customer Responsibilities

The following customer responsibilities should be considered during Core Platform implementation.

The exact responsibility must be confirmed for each project.

Typical customer activities include:

- confirm Genesys Cloud organisation ownership
- approve region and data residency requirements
- provide regulatory requirements
- provide organisational hierarchy
- approve division structure
- provide business unit structure
- provide site and location information
- provide business hours
- provide holiday calendars
- confirm required languages
- confirm licensing requirements
- confirm retention requirements
- confirm environment strategy
- approve platform architecture
- provide operational ownership
- approve production readiness

Customer-owned activities should be represented as explicit tasks when they affect the project schedule.

---

# 14. Delivery Roles

Typical delivery roles involved in Core Platform implementation include:

| Role | Typical Responsibility |
|---|---|
| Project Manager | Schedule, dependencies and governance |
| Business Analyst | Requirements and business rules |
| Solution Architect | Platform architecture and design |
| Genesys Cloud Architect | Genesys Cloud platform design |
| Technical Architect | Technical architecture and dependencies |
| Genesys Cloud Engineer | Configuration and validation |
| Terraform / DevOps Engineer | Infrastructure automation where applicable |
| Security Architect | Security and compliance requirements |
| Integration Engineer | Platform integration dependencies |
| Test Lead | Validation strategy |
| Customer Platform Owner | Customer decisions and approvals |
| Customer Technical Lead | Customer technical dependencies |
| Customer Security Lead | Security and compliance approval |

---

# 15. Environment Considerations

Core Platform tasks may apply across multiple environments or organisations.

Standard environment classifications include:

```text
DESIGN
DEV
TEST
UAT
PROD
MULTI
EXTERNAL
N/A
```

Each task should explicitly identify its environment where practical.

Some tasks may be:

```text
MULTI
```

when the same configuration must be established consistently across multiple Genesys Cloud organisations.

---

# 16. Automation Considerations

Core Platform tasks should be assessed for automation potential.

Potential methods include:

| Method | Typical Application |
|---|---|
| MANUAL | One-off platform decisions or settings |
| API | Repeatable organisation configuration |
| SDK | Custom deployment tooling |
| TERRAFORM | Infrastructure-as-code controlled configuration |
| SCRIPT | Supporting configuration and validation |
| IMPORT | Bulk data/configuration |
| PIPELINE | Automated environment deployment |
| HYBRID | Combination of methods |

Automation suitability should be captured at the individual task level.

---

# 17. Estimation Considerations

Core Platform effort is influenced by:

- new versus existing organisation
- number of organisations
- number of divisions
- number of business units
- number of sites
- number of locations
- number of languages
- number of business-hour schedules
- number of holiday schedules
- number of environments
- number of customer stakeholders
- regulatory complexity
- security requirements
- licensing complexity
- automation requirements
- Terraform adoption
- migration requirements
- customer approval cycle
- number of deployment iterations
- validation requirements

These variables should eventually become **estimation drivers** in the Layer 10 estimation model.

---

# 18. Volume Drivers

The following are likely candidates for volume-based estimation:

| Volume Driver | Example |
|---|---|
| Organisations | 1, 2, N |
| Divisions | 1, 5, 20 |
| Business Units | 1, 5, 20 |
| Locations | 1, 10, 100 |
| Sites | 1, 10, 100 |
| Time Zones | 1, 5, N |
| Business Hours | 1, 10, N |
| Holiday Schedules | 1, 10, N |
| Languages | 1, 5, N |
| Environments | 1, 2, 3, N |
| Regions | 1, N |
| Configuration Objects | Project-specific |
| Validation Cycles | 1, 2, N |

The estimation model should distinguish between:

```text
Fixed effort
+
Volume-based effort
+
Complexity adjustment
+
Dependency / coordination effort
```

---

# 19. Complexity Drivers

Core Platform complexity may increase due to:

### Low Complexity

- single organisation
- single region
- straightforward hierarchy
- single environment
- limited customer stakeholders
- minimal regulatory requirements
- standard configuration

### Medium Complexity

- multiple divisions
- multiple sites
- multiple business units
- multiple environments
- complex organisational structures
- additional compliance requirements
- automation requirements

### High Complexity

- multiple organisations
- complex data residency requirements
- complex regulatory requirements
- complex organisational hierarchy
- multiple environments requiring synchronisation
- significant migration dependencies
- extensive infrastructure-as-code requirements
- multiple customer business units
- complex approval processes
- multiple production deployment stages

Complexity must be applied as an estimation modifier rather than arbitrarily inflating individual tasks.

---

# 20. Task Catalogue Requirements

Every capability file within this directory must:

- reference the correct Layer 2 capability
- preserve the Layer 2 implementation activities
- decompose activities into individual tasks
- use the standard Layer 10 Task ID
- map each task to Layer 1
- identify task type
- identify role
- identify customer responsibility
- identify environment
- identify dependencies
- identify automation method
- identify effort
- identify duration
- identify deliverable
- identify acceptance criteria
- identify critical-path relevance
- identify applicable estimation drivers

---

# 21. Capability File Standard

Each capability document must use the following structure:

```markdown
# Layer 10 — [Capability Name]

## Capability Reference

## Capability Objective

## Layer 1 Mapping

## Source Implementation Activities

## Implementation Tasks

### [Implementation Activity]

#### [Task ID] — [Task Name]

| Attribute | Value |
|---|---|

### Description

### Dependencies

### Deliverable

### Acceptance Criteria

### Notes

## Capability-Level Dependencies

## Capability-Level Assumptions

## Capability-Level Estimation Considerations

## Definition of Done
```

The exact structure should remain consistent across all Core Platform capability files and the other Layer 10 domains.

---

# 22. Core Platform Definition of Done

The Core Platform Task Catalogue is complete when:

- all 18 capabilities have been represented
- all Layer 2 implementation activities have been reviewed
- every implementation activity has been decomposed into tasks
- every task has a unique Task ID
- every task maps to Layer 1
- task types are defined
- delivery roles are identified
- customer responsibilities are identified
- environments are identified
- dependencies are documented
- automation opportunities are documented
- deliverables are defined
- acceptance criteria are defined
- critical-path expectations are identified
- estimation drivers are identified
- capability-level assumptions are documented
- downstream dependencies are identified
- the resulting catalogue can be extracted into the Layer 10 spreadsheet model

---

# 23. Domain Completion Gate

The Core Platform domain should pass the following gate before being considered ready for project estimation:

```text
Layer 2 capabilities confirmed
        ↓
Implementation activities confirmed
        ↓
Implementation tasks decomposed
        ↓
Task IDs assigned
        ↓
Layer 1 mappings confirmed
        ↓
Dependencies identified
        ↓
Roles identified
        ↓
Customer responsibilities identified
        ↓
Environment mappings confirmed
        ↓
Automation methods identified
        ↓
Deliverables defined
        ↓
Acceptance criteria defined
        ↓
Effort drivers identified
        ↓
Complexity drivers identified
        ↓
Task catalogue reviewed
        ↓
READY FOR ESTIMATION
```

---

# 24. Future Spreadsheet Mapping

The Core Platform Task Catalogue must support eventual extraction into the project estimation workbook.

The expected spreadsheet mapping is:

| Markdown Attribute | Spreadsheet Column |
|---|---|
| Task ID | Task ID |
| Layer 1 Phase | Phase |
| Domain | Workstream / Domain |
| Capability ID | Capability ID |
| Capability | Capability |
| Parent Activity | Implementation Activity |
| Task | Task |
| Description | Description |
| Task Type | Task Type |
| Dependencies | Dependencies |
| Primary Role | Role |
| Supporting Role | Supporting Role |
| Customer Responsibility | Customer Responsibility |
| Environment | Environment |
| Automation Method | Automation |
| Effort | Effort |
| Duration | Duration |
| Deliverable | Deliverable |
| Acceptance Criteria | Acceptance Criteria |
| Critical Path | Critical Path |
| Complexity Drivers | Complexity |
| Volume Drivers | Volume |
| Notes | Notes |

This allows the Markdown repository to remain the **human-readable source of truth**, while the spreadsheet becomes the **project planning and estimation execution model**.

---

# 25. Domain End State

When this directory is complete, the Core Platform domain will provide a complete implementation chain:

```text
Layer 2 Capability
        │
        ▼
Implementation Activity
        │
        ▼
Layer 10 Task
        │
        ├── Layer 1 Phase
        ├── Dependency
        ├── Role
        ├── Customer Responsibility
        ├── Environment
        ├── Automation Method
        ├── Effort
        ├── Duration
        ├── Deliverable
        ├── Acceptance Criteria
        └── Critical Path
                │
                ▼
        Project Schedule
                │
                ▼
        Resource Plan
                │
                ▼
        Project Estimate
```

The Core Platform Task Catalogue therefore becomes the **execution-level representation of the Layer 2 Core Platform domain** and establishes the template that subsequent Layer 10 capability domains will follow.