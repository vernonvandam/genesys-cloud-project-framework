# Layer 2.13.22 — Skill & Language Migration

## Capability Definition

Skill & Language Migration establishes target skills, language proficiencies and agent assignments required for routing.

---

# 1. Scope

- Skills
- Languages
- Proficiency
- User assignments
- Queue relationships
- Routing dependencies

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Inventory source skills, languages, proficiency models and assignments.

---

# 4. Design Activities

Map source skill structures to Genesys Cloud target skills and language configuration.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.22-T01 | Inventory source skills and languages | Phase 2 | 4h |
| 2.13.22-T02 | Define target skill model | Phase 3 | 4h |
| 2.13.22-T03 | Configure target skills | Phase 6 | 4h |
| 2.13.22-T04 | Assign users | Phase 7 | 5h |
| 2.13.22-T05 | Validate routing proficiency | Phase 8 | 4h |

---

# 6. Dependencies

- User Migration
- Queue Migration
- Routing Design

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing

---

# 8. Roles

- Genesys Cloud Architect
- Genesys Cloud Engineer
- Migration Engineer

---

# 9. Customer Responsibilities

Approve skills, languages and proficiency requirements.

---

# 10. Testing

Validate skill-based and language-based routing.

---

# 11. Deliverables

- Skill Mapping
- Language Mapping
- Assignment Matrix

---

# 12. Effort Drivers

Skill count and assignment volume.

---

# 13. Acceptance Criteria

Routing produces the expected agent selection.

---

# 14. Definition of Done

Skills, languages and assignments are validated.
