# Layer 10 — Phase Gate Model

## Purpose

This document defines the phase-gate model used to control progression through the Genesys Cloud deployment lifecycle.

Phase gates provide formal decision points between major delivery stages.

A phase gate is not simply a project milestone.

A milestone records achievement.

A phase gate determines whether the project is permitted to proceed.

---

# 1. Phase Gate Principles

Phase gates should:

- provide controlled progression
- confirm required deliverables exist
- confirm prerequisite activities are complete
- confirm risks are understood
- confirm dependencies are satisfied
- confirm customer readiness
- confirm environment readiness
- confirm acceptance conditions
- identify unresolved issues
- establish an explicit decision

The standard decision outcomes are:

```text
GO
GO WITH CONDITIONS
NO-GO
```

---

# 2. Phase Gate Structure

Each gate should contain:

| Attribute | Requirement |
|---|---|
| Gate ID | REQUIRED |
| Gate Name | REQUIRED |
| Layer 1 Phase | REQUIRED |
| Entry Criteria | REQUIRED |
| Exit Criteria | REQUIRED |
| Required Deliverables | REQUIRED |
| Required Approvals | REQUIRED |
| Open Risks | REQUIRED |
| Open Defects | REQUIRED where applicable |
| Dependency Status | REQUIRED |
| Customer Readiness | REQUIRED |
| Technical Readiness | REQUIRED |
| Decision | REQUIRED |
| Decision Owner | REQUIRED |
| Decision Date | REQUIRED |

---

# 3. Gate ID

Recommended format:

```text
PG-01
PG-02
PG-03
```

Gate IDs are schedule control identifiers and do not replace Layer 1 phase IDs or Layer 10 task IDs.

---

# 4. Standard Gate Lifecycle

A typical implementation may include:

```text
PG-01
Project Initiation Gate
        ↓
PG-02
Requirements Baseline Gate
        ↓
PG-03
Architecture Gate
        ↓
PG-04
Design Gate
        ↓
PG-05
Build Readiness Gate
        ↓
PG-06
Build Complete Gate
        ↓
PG-07
Test Entry Gate
        ↓
PG-08
UAT Entry Gate
        ↓
PG-09
Production Readiness Gate
        ↓
PG-10
Go-Live Gate
        ↓
PG-11
Hypercare Exit Gate
        ↓
PG-12
Operational Handover Gate
        ↓
PG-13
Project Closure Gate
```

The actual number of gates may vary according to project size and delivery methodology.

---

# 5. Gate Entry Criteria

Entry criteria identify what must be true before the gate review can begin.

Examples include:

- required predecessor tasks complete
- required deliverables available
- required reviews completed
- required dependencies resolved
- required stakeholders available
- required evidence available

---

# 6. Gate Exit Criteria

Exit criteria define the conditions required to proceed.

Examples:

```text
Architecture Gate

- architecture approved
- material architecture decisions resolved
- security review complete
- integration approach approved
- customer approval obtained
```

---

# 7. Project Initiation Gate

Typical criteria:

- project scope defined
- project governance established
- key stakeholders identified
- delivery roles assigned
- project assumptions documented
- initial schedule established
- project risks identified

Decision:

```text
Project authorised to commence detailed delivery.
```

---

# 8. Requirements Baseline Gate

Typical criteria:

- requirements captured
- requirements reviewed
- scope boundaries documented
- assumptions documented
- dependencies identified
- requirements accepted

Decision:

```text
Requirements baseline approved.
```

---

# 9. Architecture Gate

Typical criteria:

- solution architecture complete
- technical architecture complete
- security architecture reviewed
- integration architecture defined
- migration architecture defined where applicable
- major architecture decisions resolved
- required approvals obtained

Decision:

```text
Architecture approved for detailed design and implementation.
```

---

# 10. Design Gate

Typical criteria:

- detailed designs complete
- configuration approach defined
- integration designs complete
- test strategy defined
- migration strategy defined
- security controls defined
- operational requirements defined
- outstanding design decisions resolved

Decision:

```text
Solution approved for build.
```

---

# 11. Build Readiness Gate

Typical criteria:

- environments available
- access available
- build resources assigned
- configuration standards available
- dependencies satisfied
- required customer inputs available

Decision:

```text
Build authorised to commence.
```

---

# 12. Build Complete Gate

Typical criteria:

- required configuration complete
- required development complete
- integrations configured
- security controls implemented
- migration tooling available where required
- build documentation complete
- known defects classified
- test environment ready

Decision:

```text
Solution authorised to enter formal testing.
```

---

# 13. Test Entry Gate

Typical criteria:

- test environment ready
- test cases prepared
- test data available
- test resources assigned
- test entry criteria satisfied
- known build defects assessed
- integrations available for testing

Decision:

```text
Formal system testing authorised.
```

---

# 14. UAT Entry Gate

Typical criteria:

- system testing complete
- critical defects resolved
- UAT environment ready
- UAT scenarios approved
- business users available
- UAT data available
- customer test resources confirmed

Decision:

```text
Business acceptance testing authorised.
```

---

# 15. Production Readiness Gate

Typical criteria:

- UAT accepted
- critical defects resolved or formally accepted
- production configuration validated
- production access validated
- monitoring ready
- support model ready
- operational documentation ready
- migration plan ready
- rollback plan ready
- cutover plan approved
- customer approval obtained

Decision:

```text
Production deployment authorised.
```

---

# 16. Go-Live Gate

Typical criteria:

- production deployment complete
- technical validation complete
- business validation complete
- critical issues resolved
- migration reconciliation complete where applicable
- operational support available
- customer go-live approval obtained

Decision:

```text
Solution declared live.
```

---

# 17. Hypercare Exit Gate

Typical criteria:

- production stability demonstrated
- priority defects resolved
- monitoring operational
- support process operating
- incident volumes within agreed tolerance
- outstanding risks accepted
- operations team prepared for BAU

Decision:

```text
Hypercare complete and BAU support transition authorised.
```

---

# 18. Operational Handover Gate

Typical criteria:

- operational documentation complete
- support procedures complete
- knowledge transfer complete
- support ownership confirmed
- monitoring ownership confirmed
- escalation procedures confirmed
- customer acceptance obtained

Decision:

```text
Operational ownership formally transferred.
```

---

# 19. Project Closure Gate

Typical criteria:

- contracted implementation activities complete
- outstanding tasks resolved or accepted
- documentation complete
- operational handover complete
- project acceptance obtained
- lessons learned captured
- final project reporting complete
- project records archived

Decision:

```text
Project formally closed.
```

---

# 20. Gate Decision Governance

Gate decisions must be explicit.

Recommended decision structure:

```text
GO
All mandatory criteria satisfied.

GO WITH CONDITIONS
Remaining issues do not prevent progression and have
documented owners and due dates.

NO-GO
One or more mandatory criteria are not satisfied and
progression is not authorised.
```

---

# 21. Gate Evidence

Evidence may include:

- approved documents
- test reports
- validation results
- configuration evidence
- migration results
- reconciliation reports
- risk assessments
- defect reports
- customer approvals
- operational readiness assessments
- security approvals
- architecture approvals

Gate evidence must be traceable to the relevant criteria.

---

# 22. Gate Exceptions

Exceptions may be approved where:

- a criterion cannot reasonably be satisfied before progression
- residual risk is understood
- ownership is assigned
- remediation is scheduled
- the decision is explicitly authorised

Exceptions must not silently bypass gate criteria.

---

# 23. Gate and Critical Path

A phase gate may become critical path where:

- downstream work cannot begin without approval
- the gate controls production deployment
- the gate controls go-live
- the gate controls migration
- the gate controls operational handover

The gate's criticality should be derived from schedule dependencies.

---

# 24. Gate Traceability

The complete relationship is:

```text
Layer 1 Phase
        ↓
Layer 2 Capabilities
        ↓
Layer 10 Tasks
        ↓
Deliverables
        ↓
Acceptance Criteria
        ↓
Milestone
        ↓
Phase Gate
        ↓
Decision
        ↓
Next Phase
```

---

# 25. Phase Gate Reporting

The project should report:

- gate ID
- gate name
- planned date
- forecast date
- actual date
- entry status
- exit status
- decision
- decision owner
- open risks
- open defects
- open dependencies
- customer readiness
- technical readiness

---

# 26. Definition of Done

The Phase Gate Model is complete when:

- gate structure is defined
- gate IDs are defined
- entry criteria are defined
- exit criteria are defined
- standard gate lifecycle is defined
- approval governance is defined
- gate decisions are defined
- exception handling is defined
- evidence requirements are defined
- customer readiness is represented
- technical readiness is represented
- critical-path interaction is defined
- gate reporting is defined
- gate traceability is defined