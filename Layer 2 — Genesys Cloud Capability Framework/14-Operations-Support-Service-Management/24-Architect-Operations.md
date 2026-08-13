# Layer 2.14.24 — Architect Operations

## Capability Definition

Architect Operations defines the BAU lifecycle for Genesys Cloud Architect flows, prompts, reusable components and supporting configuration.

---

# 1. Scope

- Architect flows
- Flow versions
- Prompts
- Menus
- Reusable tasks
- Data Actions
- Flow troubleshooting
- Deployment
- Rollback

---

# 2. Classification

**Required where Architect is used**

---

# 3. Discovery Activities

- Inventory Architect flows.
- Identify flow owners.
- Identify dependencies.
- Identify common failures.
- Identify deployment procedures.

---

# 4. Design Activities

- Define Architect operational lifecycle.
- Define flow ownership.
- Define versioning.
- Define deployment process.
- Define rollback.
- Define troubleshooting.
- Define change controls.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.24-T01 | Inventory Architect assets | Phase 2 | Architect Lead | 6h |
| 2.14.24-T02 | Define Architect operating model | Phase 3 | Architect Lead | 6h |
| 2.14.24-T03 | Define flow lifecycle and versioning | Phase 4 | Architect Lead | 4h |
| 2.14.24-T04 | Create Architect operational runbooks | Phase 9 | Architect Lead | 8h |
| 2.14.24-T05 | Test flow deployment and rollback | Phase 8 | Test Lead | 8h |
| 2.14.24-T06 | Transition Architect operations | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- Architect
- Routing
- Integrations
- Change Management
- Configuration Management

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Architect Lead
- Genesys Cloud Architect
- Integration Lead
- Operations Lead
- Test Lead

---

# 9. Customer Responsibilities

- Nominate flow owners.
- Approve operational standards.
- Provide SMEs.

---

# 10. Testing

Test flow deployment, versioning, rollback and failure handling.

---

# 11. Deliverables

- Architect Operations Guide
- Flow Lifecycle Procedure
- Architect Runbooks
- Rollback Procedure

---

# 12. Effort Drivers

Flow volume, complexity, integrations and release frequency.

---

# 13. Acceptance Criteria

- Architect assets inventoried.
- Ownership defined.
- Lifecycle documented.
- Deployment and rollback tested.

---

# 14. Definition of Done

Architect assets can be safely maintained, versioned, deployed and supported under BAU.