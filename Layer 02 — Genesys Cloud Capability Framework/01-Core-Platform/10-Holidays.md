# Layer 2.01.10 — Holidays

## Capability Definition

Defines customer holiday calendars and associated platform behaviour.

---

# 1. Scope

- Holiday schedules
- Public holidays
- Customer-specific holidays
- Regional holidays
- Site-specific holidays
- After-hours behaviour
- WFM implications

---

# 2. Classification

**Conditional**

---

# 3. Discovery

Determine:

- Countries.
- Regions.
- Public holidays.
- Company holidays.
- Site-specific holidays.
- Business-specific closures.
- Partial-day closures.
- Holiday exceptions.

---

# 4. Implementation

```text
Collect holiday calendar
Validate dates
Map holidays to operating regions
Configure holiday schedules
Associate schedules
Test holiday behaviour
Test exceptions
Document calendar ownership
```

---

# 5. Risks

- Incorrect holiday dates.
- Missing regional holidays.
- Incorrect time zones.
- Holiday schedules not updated annually.

---

# 6. Operational Requirement

Holiday calendars require an owner and an annual maintenance process.

---

# 7. Acceptance Criteria

Approved holiday calendars produce the expected routing and scheduling behaviour.

---

# 8. Definition of Done

Holiday schedules are configured, tested, documented and assigned an operational owner.
