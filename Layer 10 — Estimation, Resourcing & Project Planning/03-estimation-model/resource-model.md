# Layer 10 — Resource Model

## Purpose

The Resource Model defines how task effort is translated into resource demand.

---

# 1. Resource Principles

Resource planning must distinguish between:

```text
Role
Resource Type
Resource Availability
Resource Allocation
Effort
Duration
```

---

# 2. Primary Role

Every task has one Primary Role.

The Primary Role provides the initial resource classification.

---

# 3. Supporting Roles

Supporting roles may be required for:

- architecture
- security
- testing
- migration
- integration
- telephony
- WFM
- reporting
- quality
- operational readiness

---

# 4. Resource Demand

Resource demand is influenced by:

- task effort
- duration
- role
- dependencies
- concurrency
- specialist availability
- environment requirements

---

# 5. Resource Loading

Example:

```text
Task Effort = 40h
Duration = 10 working days

Average allocation = 40h / 10 days
                  = 4h/day
                  = 50% of an 8h day
```

This is an average loading calculation, not necessarily the actual daily schedule.

---

# 6. Specialist Constraints

Specialist roles may become bottlenecks.

Examples:

- Solution Architect
- Telephony Engineer
- Security Specialist
- Migration Lead
- Integration Engineer
- WFM Specialist

The schedule should identify where a limited specialist resource is shared across tasks.

---

# 7. Customer Resources

Customer resource requirements must be represented separately from delivery resources.

Examples:

- customer SME
- business tester
- system administrator
- security approver
- data owner
- operational owner

---

# 8. Resource Conflicts

Resource conflicts should be identified when:

- the same specialist is required by multiple critical tasks
- multiple environments require simultaneous support
- deployment windows overlap
- customer SMEs are unavailable
- specialist capacity is constrained

---

# 9. Resource Categories

The model may classify resources as:

```text
DELIVERY
CUSTOMER
THIRD-PARTY
```

---

# 10. Resource Planning Output

The model should support reporting:

- effort by role
- peak demand by role
- total role demand
- customer demand
- specialist bottlenecks
- resource utilisation
- critical-path resource demand

---

# 11. Definition of Done

Resource modelling is complete when:

- each task has a Primary Role
- supporting roles can be identified
- role demand can be calculated
- customer resources are separated
- specialist constraints can be identified
- resource demand can feed the project schedule