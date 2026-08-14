# Layer 2.13.20 — User Migration

## Capability Definition

User Migration establishes Genesys Cloud users, identity attributes, licences, roles, divisions, queues, skills and related access based on approved source data.

---

# 1. Scope

- User records
- Identity
- SSO
- SCIM
- Licences
- Roles
- Divisions
- Groups
- Queues
- Skills
- Languages

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify user populations.
- Identify source identity attributes.
- Identify roles.
- Identify licensing.
- Identify queue membership.
- Identify skills and languages.
- Identify migration exclusions.

---

# 4. Design Activities

Define user mapping, provisioning method, access model and validation.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.20-T01 | Extract user inventory | Phase 2 | 4h |
| 2.13.20-T02 | Map identity and access | Phase 3 | 5h |
| 2.13.20-T03 | Prepare user migration | Phase 6 | 5h |
| 2.13.20-T04 | Execute user migration | Phase 7 | 6h |
| 2.13.20-T05 | Validate licences and roles | Phase 8 | 4h |
| 2.13.20-T06 | Validate queue and skill membership | Phase 8 | 4h |

---

# 6. Dependencies

- Identity & Access
- Licensing
- Queues
- Skills

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing
- Phase 10 — Go-Live

---

# 8. Roles

- Identity Specialist
- Genesys Cloud Engineer
- Migration Engineer

---

# 9. Customer Responsibilities

Provide user source data and approve user access.

---

# 10. Testing

Validate authentication, licensing, permissions and routing eligibility.

---

# 11. Deliverables

- User Migration Dataset
- User Mapping
- User Validation Report

---

# 12. Effort Drivers

User count, roles, licensing and provisioning method.

---

# 13. Acceptance Criteria

All required users are correctly provisioned and authorised.

---

# 14. Definition of Done

Users can authenticate and operate according to approved access design.

