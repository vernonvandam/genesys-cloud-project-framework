# Layer 3 — Governance, Architecture & Controls

## Purpose

Layer 3 defines the governance framework that controls how a Genesys Cloud deployment is designed, approved, implemented and changed.

Layer 3 answers:

> **What controls surround the deployment?**

## Objective

Ensure deployments are:

- Governed.
- Reviewable.
- Auditable.
- Secure.
- Consistent.
- Architecturally sound.
- Controlled.
- Traceable.

# Governance Domains

## 3.1 Project Governance

- Project governance
- Steering committee
- Project management
- RAID management
- Scope management
- Change management
- Decision management
- Status reporting

## 3.2 Architecture Governance

- Architecture review
- Solution design authority
- Technical design authority
- Architecture standards
- Architecture decisions
- Design exceptions
- Technical debt

## 3.3 Security Governance

- Security review
- IAM approval
- Data classification
- Privacy
- Compliance
- Security exceptions
- Security acceptance

## 3.4 Change Governance

- Change requests
- Scope changes
- Technical changes
- Emergency changes
- Approval
- Testing
- Rollback

## 3.5 Configuration Governance

- Naming standards
- Configuration standards
- Version control
- Baselines
- Configuration drift
- Documentation

## 3.6 Environment Governance

- Development
- Test
- UAT
- Production
- Environment separation
- Promotion
- Access

# Architecture Governance

Every solution should establish:

- Business architecture
- Application architecture
- Integration architecture
- Data architecture
- Security architecture
- Telephony architecture
- Network architecture
- Operational architecture

# Architecture Decisions

Architecture decisions should be recorded using an ADR-style process.

Each decision should contain:

- Decision ID
- Context
- Problem
- Options
- Decision
- Rationale
- Consequences
- Owner
- Date
- Approval

# RACI

Each project must define:

- Customer responsibility
- Implementation partner responsibility
- Vendor responsibility
- Business ownership
- Technical ownership
- Operational ownership

# Governance Gates

Recommended gates:

```text
Requirements Approved
        ↓
Architecture Approved
        ↓
Build Approved
        ↓
Testing Approved
        ↓
Go-Live Approved
        ↓
Hypercare Exit
        ↓
BAU Acceptance
        ↓
Project Closure
```

# Control Framework

Controls should cover:

- Scope
- Architecture
- Security
- Data
- Configuration
- Change
- Testing
- Release
- Access
- Documentation
- Operations

# Future Documentation

```text
README.md
GOVERNANCE.md
ARCHITECTURE.md
RACI.md
DECISION-RECORDS.md
CHANGE-CONTROL.md
ENVIRONMENT-GOVERNANCE.md
CONFIGURATION-GOVERNANCE.md
APPROVAL-GATES.md
```

# Definition of Done

Layer 3 is complete when governance controls, architecture approvals, ownership, decision processes and acceptance gates are defined and can be applied consistently to a Genesys Cloud project.