# Layer 2.13.03 — Migration Scope & Assessment

## Capability Definition

Migration Scope & Assessment determines which platform objects, data, integrations and operational dependencies are within migration scope and how they will be treated.

---

# 1. Scope

- Migration inventory
- Scope classification
- Migration complexity
- Source-to-target assessment
- Migration exclusions
- Risks
- Dependencies
- Migration waves

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Inventory existing platform capabilities.
- Identify configuration objects.
- Identify users and teams.
- Identify queues and skills.
- Identify Architect flows.
- Identify telephony.
- Identify digital channels.
- Identify integrations.
- Identify historical data.
- Identify recordings.
- Identify WFM and reporting data.

---

# 4. Design Activities

Classify each object as:

- Migrate
- Recreate
- Transform
- Archive
- Retire
- Replace
- Not applicable

Determine migration complexity and target-state treatment.

---

# 5. Implementation Activities

| Task ID | Task | Primary Phase | Effort |
|---|---|---|---:|
| 2.13.03-T01 | Inventory migration candidates | Phase 2 | 6h |
| 2.13.03-T02 | Classify migration objects | Phase 2 | 6h |
| 2.13.03-T03 | Assess source-to-target compatibility | Phase 3 | 8h |
| 2.13.03-T04 | Identify migration exclusions | Phase 3 | 4h |
| 2.13.03-T05 | Assign migration complexity | Phase 3 | 4h |
| 2.13.03-T06 | Define migration waves | Phase 4 | 6h |
| 2.13.03-T07 | Obtain scope approval | Phase 4 | 2h |

---

# 6. Dependencies

- Current-state assessment
- Requirements
- Capability catalogue
- Source-system inventory

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 7 — Integration & Data Migration

---

# 8. Roles

- Migration Lead
- Solution Architect
- Data Architect
- Genesys Cloud Architect
- Business SME

---

# 9. Customer Responsibilities

Provide source-system information, SMEs, configuration exports and migration decisions.

---

# 10. Testing

Validate scope completeness and confirm every migration object has an approved target treatment.

---

# 11. Deliverables

- Migration Scope Assessment
- Migration Object Inventory
- Complexity Assessment
- Migration Wave Matrix

---

# 12. Effort Drivers

Number of objects, source platforms, configuration complexity and number of business units.

---

# 13. Acceptance Criteria

Every identified migration object has a documented migration treatment.

---

# 14. Definition of Done

Migration scope is approved and traceable to the capability and project scope.

