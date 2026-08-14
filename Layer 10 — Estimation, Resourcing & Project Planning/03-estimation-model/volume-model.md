# Layer 10 — Volume Model

## Purpose

The Volume Model defines how implementation quantities influence effort estimation.

---

# 1. Purpose of Volume

Volume allows the methodology to distinguish between:

```text
One object
```

and:

```text
Hundreds or thousands of objects
```

without requiring a separate estimation methodology for every scale.

---

# 2. Volume Drivers

Typical Genesys Cloud volume drivers include:

- users
- groups
- queues
- skills
- languages
- Architect flows
- call routes
- phone numbers
- sites
- trunks
- integrations
- data actions
- data tables
- digital channels
- bots
- knowledge articles
- reports
- dashboards
- recording data
- historical interactions
- migration records

---

# 3. Volume Classification

Where exact volume is not yet available, use:

```text
LOW
MEDIUM
HIGH
VERY HIGH
```

Exact project quantities should replace classifications as soon as they become available.

---

# 4. Unit-Based Estimation

Where appropriate:

```text
Effort =
Base Effort
+
(Unit Quantity × Unit Effort)
```

Example:

```text
Base setup = 4h
Queue configuration = 1.5h each
Quantity = 10

Estimated effort = 4h + (10 × 1.5h)
                 = 19h
```

---

# 5. Volume Bands

Projects may define controlled volume bands.

Example:

| Band | Example Quantity |
|---|---:|
| LOW | 1–10 |
| MEDIUM | 11–50 |
| HIGH | 51–250 |
| VERY HIGH | 251+ |

These bands are illustrative and must be calibrated against actual project data.

---

# 6. Non-Linear Volume

Some activities do not scale linearly.

Examples:

- migration
- testing
- data cleansing
- historical recordings
- reporting
- integration validation

Where effort increases non-linearly, a volume band or stepped model should be used rather than simple multiplication.

---

# 7. Volume Sources

Volume should preferably come from:

1. approved requirements
2. discovery inventory
3. source-system inventory
4. architecture
5. migration assessment
6. customer-provided data
7. validated configuration inventory

Assumed volumes must be clearly marked.

---

# 8. Volume Changes

Changes in volume must trigger an estimate review where they materially affect implementation effort.

---

# 9. Volume and Complexity

Volume must not be used to conceal complexity.

Both dimensions should be independently assessed.

---

# 10. Definition of Done

Volume assessment is complete when:

- applicable volume drivers are identified
- quantities are recorded
- assumptions are documented
- volume-based effort can be calculated
- changes can be propagated into the project estimate