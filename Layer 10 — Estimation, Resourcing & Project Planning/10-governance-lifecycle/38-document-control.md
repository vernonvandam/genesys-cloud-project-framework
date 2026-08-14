# Layer 10 — 10.38 Document Control

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.38 |
| Capability | Document Control |
| Task Catalogue ID | 10.38 |
| Primary Layer 1 Phases | P01, P04, P12 |

## Capability Objective

Control document ownership, status, version, review and supersession.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish document controls |
| P04 | Apply controlled documentation |
| P12 | Review and archive documentation |

## Source Implementation Activities

1. Define document standards.
2. Assign ownership.
3. Control versions.
4. Review documents.
5. Archive superseded documents.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.38-001 — Define Document Control Standard

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define document naming, ownership, status and lifecycle rules.

**Dependencies**

- Repository governance

**Deliverable**

Document control standard.

**Acceptance Criteria**

Control rules are approved.

### Activity 02 — Assign

#### L10-10.38-002 — Assign Document Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assign accountable owners to controlled methodology documents.

**Dependencies**

- L10-10.38-001

**Deliverable**

Document ownership register.

**Acceptance Criteria**

Controlled documents have owners.

### Activity 03 — Review

#### L10-10.38-003 — Review Controlled Documents

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Review documents for accuracy, consistency and current status.

**Dependencies**

- Document ownership

**Deliverable**

Document review record.

**Acceptance Criteria**

Superseded or obsolete documents are identified.

### Activity 04 — Archive

#### L10-10.38-004 — Archive Superseded Documents

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Retain historical documents while clearly identifying superseded status.

**Dependencies**

- L10-10.38-003

**Deliverable**

Controlled document archive.

**Acceptance Criteria**

Superseded documents remain traceable.

## Capability-Level Dependencies

- Repository governance
- Methodology lifecycle

## Capability-Level Estimation Considerations

Effort is driven by document count and review depth.

## Definition of Done

Controlled documents have ownership, lifecycle status and historical traceability.

---