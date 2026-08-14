# Layer 2.01.09 — Business Hours

## Capability Definition

Defines the customer's operating hours and their use within Genesys Cloud routing, Architect, scheduling and operational processes.

---

# 1. Scope

- Business hours
- Operating hours
- Multiple schedules
- Time zones
- Queue schedules
- Architect schedules
- WFM scheduling implications
- After-hours behaviour

---

# 2. Classification

**Conditional**

Required whenever customer behaviour changes according to operating hours.

---

# 3. Discovery

Determine:

- Standard operating hours.
- Different hours by location.
- Different hours by queue.
- Different hours by channel.
- After-hours behaviour.
- Emergency behaviour.
- Seasonal variations.
- Time zones.

---

# 4. Implementation

```text
Collect approved operating hours
Map time zones
Define schedules
Configure business hours
Associate schedules
Configure after-hours behaviour
Test normal hours
Test boundary conditions
Test after-hours behaviour
```

---

# 5. Layer 1 Mapping

Primary:

- Phase 3 — Requirements
- Phase 4 — Architecture
- Phase 6 — Solution Build

Supporting:

- Phase 8 — Testing

---

# 6. Acceptance Criteria

Operating-hour logic matches approved customer requirements across applicable channels and locations.

---

# 7. Definition of Done

Business hours and associated behaviours are configured, tested and approved.
