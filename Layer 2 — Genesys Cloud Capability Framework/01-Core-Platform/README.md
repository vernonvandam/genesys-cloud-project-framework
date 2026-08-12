# Layer 2.01 — Core Platform & Organisation

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Capability Framework  
**Domain:** 2.01 — Core Platform & Organisation  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the Genesys Cloud platform-level capabilities that establish the organisational foundation for all downstream configuration, implementation, testing, security and operations.

---

# 1. Purpose

The Core Platform & Organisation domain defines the foundational Genesys Cloud organisational structure and platform configuration required before customer-facing capabilities can be implemented.

This domain establishes the logical structure within which users, divisions, queues, routing, Architect, telephony, digital, WEM, QM, integrations and other capabilities operate.

The domain must be assessed during every Genesys Cloud implementation.

Individual capabilities may be classified as:

- Required
- Conditional
- Optional
- Not Applicable

---

# 2. Scope

This domain covers:

1. Genesys Cloud organisation
2. Region and data residency
3. Organisation settings
4. Divisions
5. Business units
6. Locations
7. Sites
8. Time zones
9. Business hours
10. Holidays
11. Languages
12. Media types
13. Platform defaults
14. Licensing and feature entitlement
15. Storage and retention
16. Platform limits and capacity
17. Environment strategy
18. Core platform configuration
19. Platform validation
20. Platform operational readiness

This domain does not replace the detailed security, telephony, routing, Architect, WEM, integration or operational domains. Those domains consume and extend the foundation established here.

---

# 3. Capability Hierarchy

```text
2.01 Core Platform & Organisation
│
├── 2.01.01 Genesys Cloud Organisation
├── 2.01.02 Region & Data Residency
├── 2.01.03 Organisation Settings
├── 2.01.04 Divisions
├── 2.01.05 Business Units
├── 2.01.06 Locations
├── 2.01.07 Sites
├── 2.01.08 Time Zones
├── 2.01.09 Business Hours
├── 2.01.10 Holidays
├── 2.01.11 Languages
├── 2.01.12 Media Types
├── 2.01.13 Platform Defaults
├── 2.01.14 Licensing & Feature Entitlement
├── 2.01.15 Storage & Retention
├── 2.01.16 Platform Limits & Capacity
├── 2.01.17 Environment Strategy
└── 2.01.18 Core Platform Validation
```

---

# 4. Capability Classification

| Capability | Default Classification | Notes |
|---|---|---|
| Genesys Cloud Organisation | Required | Fundamental platform construct |
| Region & Data Residency | Required | Must be established before implementation |
| Organisation Settings | Required | Scope depends on deployment |
| Divisions | Required | Structure must be defined even where simple |
| Business Units | Conditional | Primarily relevant to WFM and associated capabilities |
| Locations | Conditional | Depends on geographic and operational model |
| Sites | Conditional | Required where site/telephony architecture requires them |
| Time Zones | Required | Required for scheduling and operational configuration |
| Business Hours | Conditional | Required where business-hour behaviour is implemented |
| Holidays | Conditional | Required where holiday schedules are required |
| Languages | Conditional | Required where multilingual operation exists |
| Media Types | Required | Applicable media must be established |
| Platform Defaults | Required | Baseline configuration |
| Licensing & Entitlement | Required | Must be validated against scope |
| Storage & Retention | Conditional | Depends on recording, data and compliance requirements |
| Platform Limits & Capacity | Required | Must be assessed for enterprise deployments |
| Environment Strategy | Required | Required for controlled implementation |
| Core Platform Validation | Required | Required before downstream build |

---

# 5. Layer 1 Lifecycle Mapping

| Layer 1 Phase | Core Platform Activities |
|---|---|
| Phase 1 — Initiation | Identify organisation, region, scope and platform ownership |
| Phase 2 — Discovery | Assess existing organisation and target-state requirements |
| Phase 3 — Requirements | Define platform requirements and organisational structure |
| Phase 4 — Architecture | Design organisation, division, region and environment architecture |
| Phase 5 — Platform Foundation | Configure foundational platform components |
| Phase 6 — Solution Build | Consume platform foundation during feature configuration |
| Phase 7 — Integration & Migration | Validate platform prerequisites for integrations and migration |
| Phase 8 — Testing | Validate platform configuration |
| Phase 9 — Operational Readiness | Confirm operational platform readiness |
| Phase 10 — Production Deployment | Validate production foundation |
| Phase 11 — Hypercare | Monitor platform behaviour |
| Phase 12 — BAU Handover | Transfer ownership and operational documentation |

---

# 6. Roles

Potential delivery roles include:

- Project Manager
- Program Manager
- Solution Architect
- Technical Architect
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Security Architect
- IAM Engineer
- Telephony Engineer
- WFM Specialist
- Integration Engineer
- DevOps / Terraform Engineer
- Test Lead
- Operations Lead
- Customer Platform Owner
- Customer Security Team
- Customer IAM Team
- Customer Network Team

---

# 7. Customer Responsibilities

Customer responsibilities may include:

- Confirm business structure.
- Confirm geographic requirements.
- Confirm regulatory and data residency requirements.
- Confirm organisational hierarchy.
- Approve division model.
- Approve business-unit model.
- Approve site/location model.
- Confirm operating hours.
- Confirm holiday calendars.
- Confirm supported languages.
- Confirm licensing requirements.
- Confirm retention requirements.
- Confirm environment strategy.
- Provide required identity and security information.
- Approve platform architecture.
- Participate in validation and acceptance.

---

# 8. Dependencies

Core Platform & Organisation has dependencies on:

- Customer business structure
- Customer geography
- Data residency requirements
- Licensing
- Security architecture
- IAM architecture
- Telephony architecture
- WFM requirements
- Compliance
- Integration architecture
- Environment strategy
- Terraform / automation strategy

It is itself a prerequisite for many downstream capabilities.

---

# 9. Implementation Principles

1. Establish organisational structure before detailed feature configuration.
2. Do not configure production independently from the approved architecture.
3. Establish region and data residency requirements early.
4. Avoid unnecessary divisions.
5. Do not use divisions as a substitute for every form of organisational grouping.
6. Keep naming standards consistent.
7. Establish time-zone and calendar requirements before scheduling configuration.
8. Validate licensing before committing to detailed design.
9. Identify platform limits before finalising high-volume architecture.
10. Treat environment strategy as an architectural decision.
11. Automate repeatable configuration wherever practical.
12. Capture all deviations from the approved design.

---

# 10. Master Spreadsheet Mapping

Every implementation activity should ultimately become an individual task containing:

| Field | Requirement |
|---|---|
| Task ID | Unique task identifier |
| Layer | 2 |
| Domain | 2.01 |
| Capability | Specific capability |
| Phase | Layer 1 phase |
| Workstream | Platform |
| Task | Individual activity |
| Description | Detailed implementation instruction |
| Classification | Required / Conditional / Optional |
| Dependency | Predecessor |
| Role | Responsible delivery role |
| Customer Responsibility | Yes / No |
| Environment | DEV / TEST / UAT / PROD |
| Effort | Estimated hours |
| Duration | Estimated elapsed time |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Critical Path | Yes / No |

---

# 11. Standard Domain Deliverables

Potential deliverables include:

- Platform architecture
- Organisation structure
- Region/data residency decision
- Division model
- Business-unit model
- Location/site model
- Time-zone model
- Business-hour model
- Holiday calendar
- Language model
- Licensing matrix
- Retention requirements
- Environment strategy
- Platform configuration
- Platform validation evidence
- Platform acceptance
- BAU platform documentation

---

# 12. Standard Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Incorrect region selected | High | Confirm residency and regulatory requirements during discovery |
| Incorrect organisation model | High | Architecture review before build |
| Excessive divisions | Medium | Establish division design principles |
| Licensing mismatch | High | Validate licensing before detailed build |
| Platform limits overlooked | High | Perform capacity assessment |
| Inconsistent time zones | Medium | Establish global time-zone standard |
| Incorrect holiday calendars | Medium | Obtain customer-approved calendars |
| Environment strategy defined too late | High | Establish during architecture |
| Configuration drift | Medium | Use controlled deployment and automation |
| Uncontrolled production changes | High | Establish governance and change control |

---

# 13. Definition of Done

The Core Platform & Organisation domain is complete when:

- Platform architecture is approved.
- Region is confirmed.
- Data residency requirements are confirmed.
- Organisation structure is approved.
- Divisions are defined.
- Business units are defined where applicable.
- Locations are defined where applicable.
- Sites are defined where applicable.
- Time zones are defined.
- Business hours are defined where applicable.
- Holiday schedules are defined where applicable.
- Languages are defined where applicable.
- Media types are confirmed.
- Licensing is validated.
- Retention requirements are confirmed.
- Platform limits have been assessed.
- Environment strategy is approved.
- Platform configuration is complete.
- Platform validation has passed.
- Documentation has been accepted.

---

# 14. Phase Gate

The domain may pass its foundation gate when:

```text
Architecture Approved
        +
Organisation Structure Approved
        +
Licensing Confirmed
        +
Platform Foundation Configured
        +
Platform Validation Passed
        +
Customer Acceptance
        =
CORE PLATFORM READY
```

---

# 15. Domain Document Catalogue

```text
01-Core-Platform/
│
├── README.md
├── 01-Genesys-Cloud-Organisation.md
├── 02-Region-Data-Residency.md
├── 03-Organisation-Settings.md
├── 04-Divisions.md
├── 05-Business-Units.md
├── 06-Locations.md
├── 07-Sites.md
├── 08-Time-Zones.md
├── 09-Business-Hours.md
├── 10-Holidays.md
├── 11-Languages.md
├── 12-Media-Types.md
├── 13-Platform-Defaults.md
├── 14-Licensing-Feature-Entitlement.md
├── 15-Storage-Retention.md
├── 16-Platform-Limits-Capacity.md
├── 17-Environment-Strategy.md
└── 18-Core-Platform-Validation.md
```

---

# 16. Domain Completion

This domain establishes the foundational platform capability catalogue for Layer 2.

The individual capability documents define the implementation-level requirements that can subsequently be mapped to:

```text
Layer 1 Phase
      ↓
Capability
      ↓
Sub-Capability
      ↓
Implementation Activity
      ↓
Project Task
      ↓
Role
      ↓
Dependency
      ↓
Effort
      ↓
Deliverable
      ↓
Acceptance Criteria
```

The next level of development is to validate each capability against the current Genesys Cloud platform, customer requirements, NTT delivery standards and the eventual master estimation model.
