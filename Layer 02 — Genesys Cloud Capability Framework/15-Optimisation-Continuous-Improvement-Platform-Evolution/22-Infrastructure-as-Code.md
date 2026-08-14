# Layer 2.15.22 — Infrastructure as Code

## Capability Definition

Uses infrastructure-as-code and configuration-as-code practices to improve repeatability, consistency, governance and lifecycle management of Genesys Cloud configuration.

---

# 1. Scope

- Terraform
- Configuration as code
- Version control
- State management
- CI/CD
- Environment promotion
- Drift management
- Automated deployment

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Inventory managed configuration.
- Identify manually managed objects.
- Review existing Terraform.
- Identify configuration drift.
- Review environment strategy.

---

# 4. Design Activities

- Define IaC scope.
- Define module standards.
- Define state strategy.
- Define promotion strategy.
- Define CI/CD controls.
- Define drift detection.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.15.22-T01 | Assess configuration automation maturity | Phase 2 | DevOps Engineer | 6h |
| 2.15.22-T02 | Identify IaC candidates | Phase 3 | Solution Architect | 4h |
| 2.15.22-T03 | Design Terraform architecture | Phase 4 | DevOps Engineer | 8h |
| 2.15.22-T04 | Implement IaC improvements | Phase 6 | DevOps Engineer | 12h |
| 2.15.22-T05 | Validate deployment automation | Phase 8 | Test Lead | 6h |
| 2.15.22-T06 | Establish ongoing drift management | Phase 12 | DevOps Lead | 4h |

---

# 6. Dependencies

- Automation
- Platform Foundation
- Environment Strategy
- Security
- Configuration Governance

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

- DevOps Engineer
- DevOps Lead
- Solution Architect
- Test Lead

---

# 9. Customer Responsibilities

- Approve IaC strategy.
- Provide repository access.
- Define governance requirements.
- Participate in validation.

---

# 10. Testing

Validate plan, apply, promotion, rollback, state and drift scenarios.

---

# 11. Deliverables

- IaC Strategy
- Terraform Modules
- CI/CD Pipeline
- Configuration Standards
- Drift Management Process

---

# 12. Effort Drivers

Configuration volume, module complexity, environment count and CI/CD requirements.

---

# 13. Acceptance Criteria

- IaC scope defined.
- Modules implemented.
- Deployment automated.
- Drift process established.

---

# 14. Definition of Done

Supported Genesys Cloud configuration can be managed consistently through controlled infrastructure-as-code practices.

---