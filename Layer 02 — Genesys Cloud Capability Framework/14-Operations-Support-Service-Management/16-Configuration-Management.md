# Layer 2.14.16 — Configuration Management

## Capability Definition

Configuration Management establishes control over Genesys Cloud configuration objects, their ownership, lifecycle, dependencies and approved state.

---

# 1. Scope

- Configuration inventory
- Configuration ownership
- Baselines
- Configuration changes
- Configuration history
- Terraform/IaC where applicable
- Configuration reconciliation
- Drift management

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify configuration objects.
- Identify configuration owners.
- Identify configuration sources.
- Identify manual versus automated configuration.
- Identify current baselines.
- Identify configuration drift risks.

---

# 4. Design Activities

- Define configuration management model.
- Define configuration baseline.
- Define naming standards.
- Define version control approach.
- Define IaC approach where applicable.
- Define configuration reconciliation.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.16-T01 | Inventory managed configuration | Phase 2 | Technical Architect | 6h |
| 2.14.16-T02 | Define configuration ownership | Phase 3 | Solution Architect | 4h |
| 2.14.16-T03 | Define configuration baseline | Phase 4 | Technical Architect | 6h |
| 2.14.16-T04 | Configure configuration management tooling | Phase 5 | DevOps Engineer | 8h |
| 2.14.16-T05 | Establish configuration baseline | Phase 6 | Technical Lead | 8h |
| 2.14.16-T06 | Validate configuration reconciliation | Phase 8 | Test Lead | 6h |
| 2.14.16-T07 | Transition configuration management | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- Environment Strategy
- Terraform/IaC
- Change Management
- Governance
- Deployment

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 5 — Platform Foundation & Environment Build
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Technical Architect
- DevOps Engineer
- Genesys Cloud Architect
- Operations Lead

---

# 9. Customer Responsibilities

- Approve configuration standards.
- Provide configuration owners.
- Approve automation approach.

---

# 10. Testing

Validate configuration baselines, changes and drift detection.

---

# 11. Deliverables

- Configuration Register
- Configuration Baseline
- Configuration Standards
- IaC Repository where applicable

---

# 12. Effort Drivers

Configuration volume, automation maturity and number of environments.

---

# 13. Acceptance Criteria

- Configuration inventory complete.
- Baseline established.
- Ownership defined.
- Reconciliation validated.

---

# 14. Definition of Done

Managed Genesys Cloud configuration is controlled, baselined and recoverable.