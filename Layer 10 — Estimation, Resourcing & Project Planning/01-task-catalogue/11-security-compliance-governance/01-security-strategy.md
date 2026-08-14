# Layer 10 — 2.11.01 Security Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.01 |
| Capability | Security Strategy |
| Task Catalogue ID | 11.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P08, P09, P10, P12 |

## Capability Objective

Establish the security strategy, objectives, ownership and governance approach for the Genesys Cloud solution.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Identify security stakeholders and ownership |
| P02 | Discover existing security posture |
| P03 | Define security objectives |
| P04 | Establish security strategy |
| P08 | Validate security controls |
| P09 | Establish operational security |
| P10 | Approve production security |
| P12 | Transfer security ownership |

## Source Implementation Activities

1. Identify security stakeholders.
2. Assess customer security requirements.
3. Define security objectives.
4. Establish security strategy.
5. Obtain security approval.

## Implementation Tasks

### Activity 01 — Establish Security Strategy

#### L10-11.01-001 — Identify Security Stakeholders

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify security, privacy, compliance, IAM, infrastructure and operational stakeholders.

**Dependencies**

- Project initiation

**Deliverable**

Security stakeholder register.

**Acceptance Criteria**

All required security stakeholders are identified and ownership is documented.

---

#### L10-11.01-002 — Define Security Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define the target security strategy covering identity, access, data, integrations, monitoring, compliance and operational controls.

**Dependencies**

- L10-11.01-001
- Security requirements
- Solution architecture

**Deliverable**

Security strategy.

**Acceptance Criteria**

Security strategy is documented and approved.

## Capability-Level Dependencies

- Security requirements
- Enterprise security policies
- Solution architecture
- Identity strategy

## Capability-Level Estimation Considerations

Effort varies with:

- regulatory requirements
- number of environments
- security governance complexity
- customer approval process
- number of integrations
- existing security standards

## Definition of Done

Security strategy is approved, traceable to requirements and usable as the baseline for downstream security design.