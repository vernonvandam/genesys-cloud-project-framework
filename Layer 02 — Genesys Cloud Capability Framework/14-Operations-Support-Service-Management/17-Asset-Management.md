# Layer 2.14.17 — Asset Management

## Capability Definition

Asset Management provides operational control over Genesys Cloud-related assets and dependencies throughout their lifecycle.

---

# 1. Scope

- Phones
- Devices
- SIP infrastructure
- Numbers
- Integrations
- Applications
- Certificates
- Service accounts
- Configuration assets
- Ownership

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify existing assets.
- Identify asset owners.
- Identify lifecycle state.
- Identify dependencies.
- Identify asset repositories.

---

# 4. Design Activities

- Define asset categories.
- Define asset ownership.
- Define lifecycle states.
- Define asset relationships.
- Define asset retirement process.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.17-T01 | Inventory Genesys Cloud assets | Phase 2 | Technical Architect | 6h |
| 2.14.17-T02 | Define asset ownership | Phase 3 | Operations Lead | 4h |
| 2.14.17-T03 | Define lifecycle model | Phase 4 | Service Manager | 4h |
| 2.14.17-T04 | Populate asset register | Phase 6 | Technical Lead | 8h |
| 2.14.17-T05 | Validate asset dependencies | Phase 8 | Test Lead | 4h |
| 2.14.17-T06 | Transition asset management | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- Configuration Management
- Telephony
- Integrations
- Security
- Operations Documentation

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Technical Architect
- Operations Lead
- Service Manager
- Asset Manager

---

# 9. Customer Responsibilities

- Provide asset information.
- Confirm ownership.
- Maintain enterprise asset register.

---

# 10. Testing

Validate asset records and relationships.

---

# 11. Deliverables

- Genesys Cloud Asset Register
- Ownership Register
- Lifecycle Matrix

---

# 12. Effort Drivers

Asset volume, integration dependencies and enterprise asset-management requirements.

---

# 13. Acceptance Criteria

- Assets inventoried.
- Owners assigned.
- Lifecycle states defined.
- Critical dependencies documented.

---

# 14. Definition of Done

Genesys Cloud operational assets are identified, owned and governed throughout their lifecycle.