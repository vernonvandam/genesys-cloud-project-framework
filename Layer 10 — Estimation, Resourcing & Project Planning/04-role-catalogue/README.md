# Layer 10 — 04 Role Catalogue

## Purpose

This directory defines the standard delivery roles used by the Genesys Cloud Project Framework.

The Role Catalogue provides the controlled role definitions required to translate implementation tasks into:

- accountable delivery resources
- supporting resources
- effort by role
- resource demand
- project schedule assignments
- delivery workstreams
- responsibility allocation
- project estimation
- resource planning
- capacity analysis

The Role Catalogue is consumed by the Layer 10 estimation and scheduling models.

---

# 1. Position Within the Methodology

The Role Catalogue sits between the estimation model and the dependency/schedule models.

```text
Layer 1
Deployment Lifecycle
        ↓
Layer 2
Genesys Cloud Capability Catalogue
        ↓
Layer 10 / 01
Task Catalogue
        ↓
Layer 10 / 02
Task Standards
        ↓
Layer 10 / 03
Estimation Model
        ↓
Layer 10 / 04
Role Catalogue
        ↓
Layer 10 / 05
Dependency Model
        ↓
Layer 10 / 06
Project Schedule Model
        ↓
Layer 10 / 07
Spreadsheet Model
        ↓
Layer 10 / 08
Calibration
```

The Task Catalogue defines **what work is required**.

The Task Standards define **how tasks are represented**.

The Estimation Model defines **how effort and duration are estimated**.

The Role Catalogue defines **who performs the work**.

---

# 2. Scope

The Role Catalogue applies to all implementation tasks across the 15 Layer 2 capability domains.

The catalogue defines:

- role purpose
- role responsibilities
- role accountability
- typical task ownership
- supporting responsibilities
- Layer 1 participation
- Layer 2 domain applicability
- customer interaction
- estimation relevance
- resource planning considerations

---

# 3. Role Catalogue

| Role | File | Primary Purpose |
|---|---|---|
| Business Analyst | `business-analyst.md` | Requirements, business process and stakeholder analysis |
| Genesys Cloud Architect | `genesys-cloud-architect.md` | Genesys Cloud platform solution design and architecture |
| Genesys Cloud Engineer | `genesys-cloud-engineer.md` | Genesys Cloud configuration and implementation |
| Integration Engineer | `integration-engineer.md` | Integration, API and external-system implementation |
| Project Manager | `project-manager.md` | Project governance, planning and delivery coordination |
| Solution Architect | `solution-architect.md` | End-to-end solution architecture and design authority |
| Technical Architect | `technical-architect.md` | Technical architecture, infrastructure and technical integration |
| Terraform Engineer | `terraform-engineer.md` | Infrastructure-as-code and automated Genesys Cloud deployment |
| Tester | `tester.md` | Test planning, execution, defect validation and quality assurance |

---

# 4. Primary Role

Every Layer 10 implementation task must identify one Primary Role.

The Primary Role is accountable for completing the task outcome.

Example:

```text
Task:
Configure Genesys Cloud division structure

Primary Role:
Genesys Cloud Engineer
```

The Primary Role does not necessarily perform every activity associated with the task.

Supporting roles may participate where required.

---

# 5. Supporting Roles

A task may require multiple roles.

Example:

```text
Primary:
Genesys Cloud Engineer

Supporting:
Genesys Cloud Architect
Security Specialist
Business Analyst
Tester
```

Supporting roles should only be assigned where they materially contribute to the implementation outcome.

---

# 6. Role vs Responsibility

The Role Catalogue defines **who performs the work**.

The Customer Responsibility Standard defines **which party is responsible for the customer-side obligation**.

These concepts must remain separate.

```text
Primary Role
      ↓
Delivery Accountability

Customer Responsibility
      ↓
Customer / Delivery / Joint Obligation
```

---

# 7. Role Assignment Principles

Roles should be assigned according to:

1. technical accountability
2. implementation capability
3. task complexity
4. required specialist knowledge
5. customer engagement requirements
6. environment
7. security requirements
8. integration requirements
9. migration requirements
10. testing requirements

---

# 8. Role Assignment Rules

The following rules apply:

- every task has one Primary Role
- supporting roles are optional
- the Primary Role must have the skills required to complete the task
- role assignment must be consistent with the Task Standard
- role assignment must not be used to inflate estimates
- one individual may perform multiple roles on a small project
- a role may be performed by multiple individuals on a large project

---

# 9. Role Capacity

Resource planning must distinguish:

```text
Role
        ↓
Available Capacity
        ↓
Allocated Capacity
        ↓
Task Demand
        ↓
Resource Loading
```

The catalogue does not assume that one role equals one person.

---

# 10. Role Effort

Effort is assigned to tasks.

Role effort is derived by aggregating task effort assigned to the role.

Example:

```text
Task A = 8h → Genesys Cloud Engineer
Task B = 12h → Genesys Cloud Engineer
Task C = 4h → Genesys Cloud Engineer

Role Demand = 24h
```

---

# 11. Role Duration

Role effort does not automatically equal role duration.

Duration depends on:

- task sequencing
- dependencies
- resource availability
- parallel work
- customer availability
- project constraints

---

# 12. Role Substitution

A role may be substituted where the delivery organisation has equivalent capability.

For example:

```text
Genesys Cloud Engineer
        ↓
Senior Genesys Cloud Engineer
```

However, substitution should not change the task definition or methodology.

---

# 13. Customer Roles

Customer roles are not defined as delivery roles in this catalogue.

Customer roles may include:

- Business SME
- Product Owner
- System Owner
- Data Owner
- Security Owner
- Network Owner
- Test Lead
- Operations Lead
- Service Owner

Customer responsibilities are modelled separately.

---

# 14. Layer 1 Participation

Roles may participate across all Layer 1 phases.

Typical involvement includes:

| Layer 1 | Typical Role Participation |
|---|---|
| P01 | Project Manager, Business Analyst, Solution Architect |
| P02 | Business Analyst, Solution Architect, Technical Architect |
| P03 | Business Analyst, Architects |
| P04 | Solution Architect, Technical Architect, Genesys Cloud Architect |
| P05 | Genesys Cloud Architect, Genesys Cloud Engineer |
| P06 | Genesys Cloud Engineer, Integration Engineer, Terraform Engineer |
| P07 | Integration Engineer, Terraform Engineer, Migration specialists |
| P08 | Tester, Engineers, Architects |
| P09 | Project Manager, Engineers, Operations stakeholders |
| P10 | Tester, Engineers, Architects |
| P11 | Project Manager, Engineers, Tester |
| P12 | Project Manager, Architects, Engineers |

---

# 15. Layer 2 Applicability

Roles may contribute to any of the 15 Layer 2 domains depending on project scope.

The role catalogue should not artificially constrain a role to a single capability domain.

---

# 16. Estimation Model Relationship

The Role Catalogue feeds the Estimation Model through:

```text
Task
 ↓
Primary Role
 ↓
Baseline Effort
 ↓
Role Effort
 ↓
Role Demand
```

This enables project estimates to be reported by role.

---

# 17. Schedule Model Relationship

The Role Catalogue feeds the Project Schedule Model through:

```text
Task
 ↓
Primary Role
 ↓
Task Effort
 ↓
Task Duration
 ↓
Resource Assignment
 ↓
Schedule
```

---

# 18. Spreadsheet Model Relationship

The project workbook should be able to report:

- Task ID
- Task Name
- Primary Role
- Supporting Roles
- Effort
- Duration
- Layer 1 Phase
- Layer 2 Domain
- Layer 2 Capability
- Dependencies
- Customer Responsibility
- Critical Path

---

# 19. Role Catalogue Completion

The Role Catalogue is complete when:

- all standard roles have been documented
- every role has a defined purpose
- every role has defined responsibilities
- role accountability is clear
- role assignment rules are defined
- role effort can be aggregated
- role demand can be calculated
- roles can feed the project schedule
- roles can feed the project workbook
- roles remain traceable to Layer 10 task definitions