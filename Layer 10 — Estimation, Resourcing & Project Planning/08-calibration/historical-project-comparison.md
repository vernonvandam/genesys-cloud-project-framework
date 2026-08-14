# Layer 10 — Historical Project Comparison

## Purpose

This document defines how completed Genesys Cloud projects are compared to identify useful estimation patterns for future projects.

Historical comparison provides empirical evidence for:

- baseline effort
- duration
- complexity
- resource requirements
- dependencies
- customer effort
- implementation sequencing
- project risk

Historical projects must only be compared where they are sufficiently comparable.

---

# 1. Comparison Principles

Historical comparison shall:

1. Use completed projects where possible.
2. Preserve the original project baseline.
3. Compare equivalent task definitions.
4. Account for scope differences.
5. Account for complexity.
6. Account for customer conditions.
7. Account for technology changes.
8. Account for delivery methodology changes.
9. Record the model version used.
10. Avoid blindly copying historical effort.

---

# 2. Historical Project Record

Each historical project should contain:

| Attribute | Description |
|---|---|
| Project ID | Unique project identifier |
| Project Type | Implementation type |
| Model Version | Layer 10 version |
| Customer Size | Relevant size classification |
| User Count | User population |
| Queue Count | Queue population |
| Integration Count | Integration complexity |
| Flow Count | Architect complexity |
| Digital Scope | Digital channel scope |
| WFM Scope | WFM scope |
| Migration Scope | Migration complexity |
| Data Volume | Relevant data volume |
| Project Duration | Actual elapsed duration |
| Delivery Effort | Actual delivery effort |
| Customer Effort | Actual customer effort |
| Major Risks | Significant risks |
| Major Issues | Significant issues |
| Complexity | Complexity classification |

---

# 3. Comparability

Projects should be classified as:

- HIGHLY COMPARABLE
- COMPARABLE
- PARTIALLY COMPARABLE
- NOT COMPARABLE

Comparison should consider:

- solution scope
- organisation size
- technical complexity
- integration landscape
- migration complexity
- regulatory requirements
- deployment methodology
- number of environments
- number of deployment waves

---

# 4. Project Complexity

A project may be classified as:

```text
LOW
MEDIUM
HIGH
VERY HIGH
```

Complexity should consider:

- user volume
- channel count
- telephony complexity
- routing complexity
- Architect complexity
- integration count
- data complexity
- migration scope
- compliance requirements
- number of business units
- geographic distribution
- deployment waves

---

# 5. Historical Task Comparison

Where possible, compare equivalent Layer 10 Task IDs.

Example:

```text
L10-01.01-001

Project A = 8h
Project B = 9h
Project C = 7h
Project D = 10h
```

Potential baseline:

```text
Median = 8.5h
Mean   = 8.5h
```

The resulting baseline should still be reviewed against the current methodology.

---

# 6. Historical Capability Comparison

Compare total capability effort.

Example:

```text
Capability:
Platform Provisioning

Project A
Baseline = 18h
Actual   = 20h

Project B
Baseline = 18h
Actual   = 17h

Project C
Baseline = 18h
Actual   = 21h
```

Historical evidence suggests a baseline around the existing value may remain appropriate.

---

# 7. Historical Domain Comparison

Domain-level comparison may reveal broader patterns.

Example:

```text
Voice & Telephony

Project A = 160h
Project B = 180h
Project C = 170h
Project D = 210h
```

The 210-hour project should be analysed for complexity before changing the domain baseline.

---

# 8. Historical Role Comparison

Compare actual effort by role.

Example:

```text
Genesys Cloud Engineer

Project A = 120h
Project B = 140h
Project C = 125h
Project D = 135h
```

This can help identify:

- role loading assumptions
- under-allocation
- over-allocation
- missing supporting roles
- specialist requirements

---

# 9. Historical Duration Comparison

Duration should be compared independently from effort.

Example:

```text
Project A = 8 weeks
Project B = 10 weeks
Project C = 9 weeks
Project D = 14 weeks
```

The 14-week project may have experienced:

- customer delays
- additional scope
- dependency constraints
- deployment windows
- migration issues

It should not automatically redefine the standard duration.

---

# 10. Normalisation

Historical project data should be normalised where necessary.

Examples:

- different working hours
- different resource models
- different delivery teams
- different scope
- different customer sizes
- different project methodology
- different technology versions

Normalisation prevents incomparable projects from distorting the model.

---

# 11. Historical Comparison Matrix

A comparison should support:

| Dimension | Project A | Project B | Project C | Current Baseline |
|---|---:|---:|---:|---:|
| Delivery Effort | | | | |
| Customer Effort | | | | |
| Duration | | | | |
| Users | | | | |
| Queues | | | | |
| Integrations | | | | |
| Architect Flows | | | | |
| Migration | | | | |
| Complexity | | | | |

---

# 12. Historical Benchmarking

The model may establish benchmark ranges.

Example:

```text
Low Benchmark
25th percentile

Typical Benchmark
50th percentile

High Benchmark
75th percentile
```

These benchmarks should be used as evidence rather than automatic estimates.

---

# 13. Outlier Management

Outliers should be identified.

Potential causes:

- unusual customer
- unusual technology
- exceptional scope
- major defect
- major migration issue
- staffing problem
- exceptional complexity

Outliers should be retained historically but may be excluded from baseline calculations where justified.

---

# 14. Historical Comparison Rules

Do not:

- overwrite historical actuals
- remove inconvenient projects without explanation
- treat all projects as equivalent
- blindly average unrelated projects
- ignore scope differences
- ignore complexity
- ignore technology changes

Do:

- preserve source evidence
- document exclusions
- identify comparable projects
- explain differences
- use multiple projects where possible
- record confidence

---

# 15. Historical Calibration Output

The comparison should produce:

- comparable project set
- benchmark ranges
- task benchmarks
- capability benchmarks
- domain benchmarks
- role benchmarks
- duration benchmarks
- complexity patterns
- outlier analysis
- calibration recommendations

---

# 16. Definition of Done

Historical project comparison is complete when:

- completed projects are identified
- project data is validated
- comparability is assessed
- complexity is assessed
- relevant tasks are compared
- capabilities are compared
- domains are compared
- roles are compared
- durations are compared
- outliers are reviewed
- benchmark ranges are identified
- calibration recommendations are documented

---

# Phase Completion

Historical project comparison provides the empirical evidence required to validate whether Layer 10 baseline assumptions remain appropriate for future Genesys Cloud deployments.