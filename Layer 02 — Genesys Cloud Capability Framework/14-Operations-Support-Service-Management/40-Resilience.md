# Layer 2.14.40 — Resilience

## Capability Definition

Resilience defines how Genesys Cloud services and dependencies withstand failures and recover from operational disruptions.

---

# 1. Scope

- Platform resilience
- Telephony resilience
- Integration resilience
- Network dependencies
- Failure modes
- Recovery
- Redundancy
- Resilience testing

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify critical services.
- Identify failure modes.
- Identify dependencies.
- Identify recovery requirements.
- Identify resilience controls.

---

# 4. Design Activities

- Define resilience requirements.
- Define failure scenarios.
- Define recovery strategies.
- Define redundancy.
- Define resilience testing.
- Define operational procedures.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.40-T01 | Assess resilience requirements | Phase 2 | Technical Architect | 6h |
| 2.14.40-T02 | Identify critical failure scenarios | Phase 3 | Resilience Lead | 6h |
| 2.14.40-T03 | Design resilience controls | Phase 4 | Technical Architect | 8h |
| 2.14.40-T04 | Implement resilience controls | Phase 6 | Technical Lead | 10h |
| 2.14.40-T05 | Execute resilience tests | Phase 8 | Test Lead | 10h |
| 2.14.40-T06 | Correct resilience gaps | Phase 11 | Technical Lead | 8h |
| 2.14.40-T07 | Transition resilience procedures | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- Architecture
- Telephony
- Integrations
- Business Continuity
- Disaster Recovery

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 11 — Hypercare & Stabilisation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Technical Architect
- Resilience Lead
- Telephony Architect
- Integration Architect
- Test Lead

---

# 9. Customer Responsibilities

- Define resilience requirements.
- Approve recovery objectives.
- Participate in resilience testing.

---

# 10. Testing

Execute agreed failure and recovery scenarios.

---

# 11. Deliverables

- Resilience Assessment
- Resilience Design
- Failure Scenarios
- Recovery Procedures
- Resilience Test Results

---

# 12. Effort Drivers

Criticality, architecture, dependencies and recovery complexity.

---

# 13. Acceptance Criteria

- Failure scenarios identified.
- Controls implemented.
- Tests completed.
- Gaps resolved or accepted.

---

# 14. Definition of Done

Critical Genesys Cloud services have defined and tested resilience mechanisms appropriate to their business criticality.