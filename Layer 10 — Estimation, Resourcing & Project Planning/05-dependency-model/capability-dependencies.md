# Layer 10 — Capability Dependencies

## Purpose

This document defines the standard dependency relationships between Layer 2 Genesys Cloud capability domains.

Capability dependencies provide the bridge between the Layer 2 capability catalogue and the detailed Layer 10 task dependency model.

---

# 1. Principle

Capability dependencies describe **logical delivery relationships**.

They do not automatically mean that every task in one capability must precede every task in another capability.

The detailed task dependency model determines the actual schedule relationship.

---

# 2. Layer 2 Domains

The framework contains:

| ID | Domain |
|---|---|
| 01 | Core Platform |
| 02 | Identity & Access |
| 03 | Voice & Telephony |
| 04 | ACD & Routing |
| 05 | Architect |
| 06 | Digital |
| 07 | WFM & Employee Engagement |
| 08 | Data, Integrations & APIs |
| 09 | Analytics, Reporting & Data Visualisation |
| 10 | Quality Management, Recording & Evaluation |
| 11 | Security, Compliance & Governance |
| 12 | Testing, Validation & Deployment |
| 13 | Migration, Data Conversion & Transition |
| 14 | Operations, Support & Service Management |
| 15 | Optimisation, Continuous Improvement & Platform Evolution |

---

# 3. Foundational Capability Dependencies

Typical foundational relationships include:

```text
01 Core Platform
        ↓
02 Identity & Access
        ↓
03 Voice & Telephony
        ↓
04 ACD & Routing
        ↓
05 Architect
```

These are logical relationships rather than universal sequencing rules.

---

# 4. Core Platform Dependencies

Core Platform commonly provides prerequisites for:

- Identity & Access
- Voice & Telephony
- ACD & Routing
- Architect
- Digital
- WFM
- Data & Integrations
- Analytics
- Quality
- Security
- Testing
- Migration
- Operations

---

# 5. Identity & Access Dependencies

Identity & Access may be a prerequisite for:

- user configuration
- agent configuration
- permissions
- SSO
- MFA
- queue membership
- WFM access
- reporting access
- operational access

Typical relationship:

```text
02 Identity & Access
        ↓
User / Agent Configuration
```

---

# 6. Voice & Telephony Dependencies

Voice & Telephony commonly interacts with:

- ACD & Routing
- Architect
- Integrations
- Analytics
- Quality
- Migration
- Testing

Example:

```text
03 Voice & Telephony
        ↓
04 ACD & Routing
        ↓
05 Architect
```

---

# 7. ACD & Routing Dependencies

ACD & Routing commonly depends on:

- users
- queues
- skills
- languages
- divisions
- routing requirements

It provides prerequisites for:

- Architect
- testing
- analytics
- quality
- WFM
- migration

---

# 8. Architect Dependencies

Architect commonly depends on:

- queues
- routing
- skills
- telephony
- data actions
- integration requirements

Architect may provide prerequisites for:

- voice testing
- digital testing
- integration testing
- analytics validation
- migration validation

---

# 9. Digital Dependencies

Digital may depend on:

- core platform
- identity
- routing
- Architect
- integrations
- security

Digital may provide prerequisites for:

- digital testing
- digital reporting
- quality
- operational readiness

---

# 10. WFM Dependencies

WFM may depend on:

- users
- queues
- skills
- organisational structures
- routing configuration
- operational requirements

WFM may also depend on:

- historical data
- scheduling requirements
- workforce processes

---

# 11. Data, Integrations & APIs Dependencies

This domain commonly has cross-domain relationships with:

- Architect
- Digital
- CRM
- Analytics
- Reporting
- Migration
- Security

Example:

```text
Integration Architecture
        ↓
API / Data Action Configuration
        ↓
Integration Testing
```

---

# 12. Analytics Dependencies

Analytics and reporting may depend on:

- configured platform objects
- queues
- users
- routing
- interaction flows
- data integrations
- reporting requirements

Testing and validation must follow relevant configuration.

---

# 13. Quality & Recording Dependencies

Quality Management may depend on:

- voice configuration
- recording configuration
- users
- queues
- retention requirements
- security requirements
- compliance requirements

Typical relationship:

```text
Recording Requirements
        ↓
Recording Configuration
        ↓
Quality Configuration
        ↓
Quality Validation
```

---

# 14. Security Dependencies

Security and Compliance is cross-cutting.

Security requirements may be a prerequisite for:

- identity
- integrations
- recording
- data
- migration
- testing
- production deployment
- operations

Security dependencies should therefore be represented at task level rather than forcing all security work to occur as one sequential block.

---

# 15. Testing Dependencies

Testing consumes outputs from almost every other domain.

Typical relationship:

```text
Capability Build
      ↓
Capability Validation
      ↓
Integration Testing
      ↓
System Testing
      ↓
UAT
```

---

# 16. Migration Dependencies

Migration may depend on:

- source discovery
- target architecture
- target configuration
- integration readiness
- data mapping
- testing
- security
- operational readiness

Migration may itself provide prerequisites for:

- production deployment
- validation
- reporting
- historical data availability
- operational handover

---

# 17. Operations Dependencies

Operations requires outputs from:

- platform configuration
- integrations
- monitoring
- reporting
- security
- testing
- migration
- deployment

Example:

```text
Production Validation
        ↓
Operational Handover
        ↓
Support
```

---

# 18. Optimisation Dependencies

Optimisation generally depends on:

- production operation
- reporting
- analytics
- quality
- WFM
- operational feedback
- incident data
- performance data

Typical relationship:

```text
Production Operation
        ↓
Performance Data
        ↓
Analysis
        ↓
Optimisation
        ↓
Continuous Improvement
```

---

# 19. Capability Dependency Matrix

The following matrix identifies common logical dependencies.

| Capability Domain | Common Prerequisites |
|---|---|
| 01 Core Platform | Architecture, security requirements |
| 02 Identity & Access | Core Platform, security |
| 03 Voice & Telephony | Core Platform, identity, telephony requirements |
| 04 ACD & Routing | Core Platform, users, queues, skills |
| 05 Architect | Routing, telephony, integrations |
| 06 Digital | Core Platform, identity, routing, integrations |
| 07 WFM | Users, queues, skills, operational requirements |
| 08 Data & Integrations | Architecture, security, source/target systems |
| 09 Analytics | Platform configuration, data sources |
| 10 Quality & Recording | Voice, users, queues, security |
| 11 Security | Cross-domain requirements and architecture |
| 12 Testing | Configured capabilities and test environments |
| 13 Migration | Source data, target design, configuration, testing |
| 14 Operations | Production solution, monitoring, documentation |
| 15 Optimisation | Production data, reporting, operational feedback |

---

# 20. Dependency Classification

Each capability dependency must be classified:

- REQUIRED
- CONDITIONAL
- EXTERNAL
- CUSTOMER
- APPROVAL

---

# 21. Task-Level Derivation

Capability dependencies must be decomposed into task dependencies.

Example:

```text
Capability:
04 ACD & Routing

Capability:
05 Architect

        ↓

Task:
L10-04.01-003 Configure Queue
        ↓
Task:
L10-05.01-002 Configure Inbound Flow
```

The task dependency is what ultimately enters the project schedule.

---

# 22. Definition of Done

Capability dependency modelling is complete when:

- all Layer 2 domains are represented
- major cross-domain relationships are defined
- conditional relationships are identified
- dependencies are not treated as blanket sequential constraints
- task-level dependencies can be derived
- dependencies can feed the task dependency model