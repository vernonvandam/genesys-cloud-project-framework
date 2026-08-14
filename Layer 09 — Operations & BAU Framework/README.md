# Layer 9 — Operations & BAU Framework

## Purpose

Layer 9 defines how the Genesys Cloud environment is operated, supported, monitored and continuously improved after implementation.

Layer 9 answers:

> **How do we run Genesys Cloud after go-live?**

## Objective

Ensure the platform can be operated independently of the implementation project.

# Operational Domains

## 9.1 Service Management

- Service ownership
- Service Desk
- SLA
- Support model
- Escalation
- Service reporting

## 9.2 Incident Management

Define:

- Severity
- Priority
- Assignment
- Escalation
- Communication
- Resolution
- Closure

## 9.3 Problem Management

Cover:

- Trend analysis
- Root cause
- Corrective action
- Permanent resolution

## 9.4 Change Management

Cover:

- Standard change
- Normal change
- Emergency change
- Testing
- Approval
- Rollback

## 9.5 Release Management

Define:

- Release planning
- Testing
- Approval
- Deployment
- Validation
- Rollback

## 9.6 Monitoring

Monitor:

- Platform
- Telephony
- Integrations
- APIs
- Digital
- WFM
- QM
- Reporting
- Performance

## 9.7 Security Operations

Cover:

- Access reviews
- Privileged access
- OAuth
- Audit
- Security incidents
- Compliance

## 9.8 Configuration Management

Maintain:

- Users
- Queues
- Skills
- Routing
- Architect
- Telephony
- Integrations
- Configuration baselines

## 9.9 Disaster Recovery

Define:

- Recovery objectives
- Dependencies
- Procedures
- Ownership
- Testing

## 9.10 Business Continuity

Plan for:

- Platform outage
- Carrier outage
- Network outage
- IAM outage
- CRM outage
- Integration outage

# BAU Lifecycle

```text
Operate
   ↓
Monitor
   ↓
Incident
   ↓
Problem
   ↓
Change
   ↓
Test
   ↓
Release
   ↓
Validate
   ↓
Operate
```

# Continuous Improvement

The BAU framework should support:

- Optimisation
- Automation
- AI adoption
- Routing improvement
- Reporting improvement
- WFM optimisation
- QM improvement
- Digital improvement
- Cost optimisation

# BAU Ownership

Every capability must have:

- Business owner
- Technical owner
- Operational owner
- Support group
- Escalation path

# Operational Documentation

Recommended:

```text
README.md
SERVICE-MANAGEMENT.md
SUPPORT-MODEL.md
INCIDENT-MANAGEMENT.md
PROBLEM-MANAGEMENT.md
CHANGE-MANAGEMENT.md
RELEASE-MANAGEMENT.md
MONITORING.md
DR.md
BUSINESS-CONTINUITY.md
SECURITY-OPERATIONS.md
CONFIGURATION-MANAGEMENT.md
CONTINUOUS-IMPROVEMENT.md
```

# Definition of Done

Layer 9 is complete when the customer can operate, support, monitor, secure, change and continuously improve the Genesys Cloud environment without dependence on the implementation project.