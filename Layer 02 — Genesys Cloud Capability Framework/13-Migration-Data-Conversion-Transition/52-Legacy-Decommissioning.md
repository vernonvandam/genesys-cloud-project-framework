# Layer 2.13.52 — Legacy Decommissioning

## Capability Definition

Legacy Decommissioning removes or disables legacy platform components after migration, validation and retention obligations are satisfied.

---

# 1. Scope

- Applications
- Servers
- Integrations
- APIs
- Telephony
- Licences
- Accounts
- Network dependencies
- Data repositories

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

Identify all legacy components and dependencies.

---

# 4. Design Activities

Define decommission sequence, approvals, rollback and evidence requirements.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.52-T01 | Inventory decommission candidates | Phase 2 | 4h |
| 2.13.52-T02 | Validate no remaining dependencies | Phase 11 | 5h |
| 2.13.52-T03 | Confirm archival and retention | Phase 12 | 4h |
| 2.13.52-T04 | Obtain decommission approval | Phase 12 | 2h |
| 2.13.52-T05 | Execute decommissioning | Phase 12 | 8h |
| 2.13.52-T06 | Validate removal | Phase 12 | 4h |

---

# 6. Dependencies

- Legacy Transition
- Data Archival
- Operational Handover
- Business Acceptance

---

# 7. Layer 1 Mapping

- Phase 11 — Hypercare
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Technical Architect
- Customer IT
- Migration Lead
- Service Manager

---

# 9. Customer Responsibilities

Approve and execute legacy retirement activities.

---

# 10. Testing

Validate no production dependencies remain after decommissioning.

---

# 11. Deliverables

- Decommission Plan
- Approval Record
- Decommission Evidence

---

# 12. Effort Drivers

Legacy platform complexity and dependency count.

---

# 13. Acceptance Criteria

Legacy components are safely retired without impact to Genesys Cloud operations.

---

# 14. Definition of Done

Legacy decommissioning is completed and evidenced.
