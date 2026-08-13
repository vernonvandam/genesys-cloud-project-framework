# Layer 2.14.15 — Release Management

## Capability Definition

Release Management controls the packaging, validation, scheduling and deployment of Genesys Cloud changes and releases.

---

# 1. Scope

- Release planning
- Release packaging
- Release approval
- Deployment scheduling
- Release testing
- Release communications
- Rollback
- Release closure

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify current release processes.
- Identify deployment environments.
- Identify release authorities.
- Identify release windows.
- Identify dependencies.

---

# 4. Design Activities

- Define release lifecycle.
- Define release classification.
- Define release approval.
- Define deployment readiness.
- Define rollback.
- Define release communication.
- Define post-release validation.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.15-T01 | Assess release process | Phase 2 | Release Manager | 3h |
| 2.14.15-T02 | Define Genesys Cloud release model | Phase 3 | Technical Architect | 4h |
| 2.14.15-T03 | Define release readiness criteria | Phase 4 | Release Manager | 4h |
| 2.14.15-T04 | Define deployment and rollback procedures | Phase 4 | Technical Lead | 6h |
| 2.14.15-T05 | Establish release checklist | Phase 9 | Release Manager | 4h |
| 2.14.15-T06 | Test release workflow | Phase 9 | Test Lead | 4h |
| 2.14.15-T07 | Transition release management | Phase 12 | Release Manager | 2h |

---

# 6. Dependencies

- Change Management
- Configuration Management
- Testing
- Deployment
- Environment Strategy

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 5 — Platform Foundation & Environment Build
- Phase 8 — Testing & Validation
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Release Manager
- Technical Architect
- Test Lead
- Operations Lead
- Project Manager

---

# 9. Customer Responsibilities

- Approve release windows.
- Participate in release governance.
- Approve production releases.

---

# 10. Testing

Validate release readiness, deployment and rollback.

---

# 11. Deliverables

- Release Management Process
- Release Checklist
- Release Calendar
- Rollback Procedure

---

# 12. Effort Drivers

Release frequency, environment strategy and deployment complexity.

---

# 13. Acceptance Criteria

- Release process approved.
- Readiness criteria defined.
- Release checklist tested.
- Rollback process validated.

---

# 14. Definition of Done

Genesys Cloud changes can be packaged, approved, deployed and validated through a controlled release process.