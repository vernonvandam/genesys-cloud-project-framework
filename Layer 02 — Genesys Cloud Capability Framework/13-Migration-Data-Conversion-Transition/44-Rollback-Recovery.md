# Layer 2.13.44 — Rollback & Recovery

## Capability Definition

Rollback & Recovery defines the controlled process for reversing or recovering from an unsuccessful migration or cutover.

---

# 1. Scope

- Rollback criteria
- Decision authority
- Recovery actions
- Data recovery
- Configuration recovery
- Telephony rollback
- Integration rollback
- Communications

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Identify failure scenarios and recoverability constraints.

---

# 4. Design Activities

Define rollback thresholds, decision points, recovery procedures and ownership.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.44-T01 | Identify rollback scenarios | Phase 4 | 4h |
| 2.13.44-T02 | Define rollback criteria | Phase 4 | 3h |
| 2.13.44-T03 | Develop rollback runbook | Phase 9 | 5h |
| 2.13.44-T04 | Rehearse rollback | Phase 9 | 5h |
| 2.13.44-T05 | Validate recovery | Phase 9 | 4h |
| 2.13.44-T06 | Execute rollback if required | Phase 10 | 8h |

---

# 6. Dependencies

- Migration Rehearsal
- Cutover
- Data Freeze
- Telephony
- Integration

---

# 7. Layer 1 Mapping

- Phase 4 — Design
- Phase 8 — Testing
- Phase 9 — Cutover Preparation
- Phase 10 — Go-Live
- Phase 11 — Hypercare

---

# 8. Roles

- Technical Architect
- Migration Lead
- Project Manager
- Genesys Cloud Architect

---

# 9. Customer Responsibilities

Approve rollback criteria and decision authority.

---

# 10. Testing

Rollback must be rehearsed for material migrations.

---

# 11. Deliverables

- Rollback Plan
- Recovery Runbook
- Rehearsal Results

---

# 12. Effort Drivers

Migration complexity and business continuity requirements.

---

# 13. Acceptance Criteria

Rollback can be executed within agreed recovery objectives.

---

# 14. Definition of Done

Rollback is tested and approved.

