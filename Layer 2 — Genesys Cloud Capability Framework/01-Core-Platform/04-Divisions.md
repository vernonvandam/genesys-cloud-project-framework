# Layer 2.01.04 — Divisions

## Capability Definition

Divisions provide logical separation of Genesys Cloud resources and access boundaries.

---

# 1. Scope

- Division architecture
- Division naming
- Division ownership
- Resource assignment
- Access implications
- Role implications
- Configuration governance

---

# 2. Classification

**Required**

A division strategy must be established even where a single default or simple division structure is appropriate.

---

# 3. Discovery

Determine:

- Number of business entities.
- Geographic separation.
- Administrative separation.
- Security boundaries.
- Customer ownership.
- Resource ownership.
- Reporting requirements.
- WFM requirements.
- Integration requirements.

---

# 4. Design

- Define division principles.
- Define division names.
- Map resources.
- Map administrative ownership.
- Define access boundaries.
- Define reporting implications.
- Validate downstream impacts.

---

# 5. Implementation

```text
Define division model
Approve division model
Create divisions
Assign required resources
Validate permissions
Validate resource visibility
Document division mapping
```

---

# 6. Dependencies

- Organisation
- Security/RBAC
- Business structure
- WFM
- Routing
- Reporting

---

# 7. Layer 1 Mapping

Primary:

- Phase 4 — Architecture
- Phase 5 — Platform Foundation

Supporting:

- Phase 6 — Solution Build
- Phase 8 — Testing

---

# 8. Roles

- Solution Architect
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Security Architect

---

# 9. Risks

- Excessive division complexity.
- Incorrect resource assignment.
- Incorrect permission boundaries.
- Reporting complications.
- WFM configuration impact.

---

# 10. Acceptance Criteria

- Division architecture is approved.
- Divisions are created.
- Required resources are assigned.
- Access has been validated.
- Customer accepts the model.

---

# 11. Definition of Done

Division architecture is implemented and validated against the approved design.
