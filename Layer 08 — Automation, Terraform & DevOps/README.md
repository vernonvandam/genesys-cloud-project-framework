# Layer 8 — Automation, Terraform & DevOps

## Purpose

Layer 8 defines how Genesys Cloud deployments can be made repeatable, automated, version-controlled and maintainable.

Layer 8 answers:

> **How do we make Genesys Cloud deployments repeatable?**

## Objective

Create an engineering framework covering:

- Terraform
- Infrastructure as Code
- Git
- CI/CD
- Automation
- Validation
- Testing
- Release management

# Terraform

## Core Components

- Genesys Cloud provider
- Resources
- Data sources
- Modules
- Variables
- Outputs
- Locals
- State
- Backend
- Provider versions

## Module Design

Modules should be:

- Reusable
- Composable
- Versioned
- Documented
- Tested
- Parameterised

Potential modules:

- Organisation
- Divisions
- Users
- Roles
- Queues
- Skills
- Data Tables
- Data Table Rows
- Architect
- Routing
- Telephony
- Integrations

# Environment Strategy

Support:

```text
DEV
 ↓
TEST
 ↓
UAT
 ↓
PRODUCTION
```

Where appropriate.

# State Management

Define:

- State backend
- Locking
- Backup
- Access
- Secrets
- Recovery
- State ownership

# Git

Define:

- Repository structure
- Branch strategy
- Pull requests
- Code review
- Branch protection
- Versioning
- Tags
- Releases

# CI/CD

Recommended model:

```text
Developer
    ↓
Git
    ↓
Pull Request
    ↓
Validation
    ↓
Automated Tests
    ↓
Terraform Plan
    ↓
Approval
    ↓
Terraform Apply
    ↓
Post-Deployment Validation
```

# Automation Domains

Automate where appropriate:

- User creation
- Queue creation
- Skills
- Data Tables
- Architect
- Configuration
- Integration
- Testing
- Validation
- Documentation

# Deployment Safety

Automation must consider:

- Dependencies
- Ordering
- Idempotency
- Rollback
- Failure handling
- State
- Drift
- Approval

# Configuration Drift

The methodology should include:

```text
Expected State
      ↓
Actual State
      ↓
Drift Detection
      ↓
Assessment
      ↓
Correction
```

# DevOps Governance

Define:

- Code review
- Change control
- Release management
- Secrets management
- Pipeline access
- Deployment approval
- Rollback

# Future Documentation

```text
README.md
TERRAFORM.md
MODULE-STANDARDS.md
STATE-MANAGEMENT.md
GIT-STANDARDS.md
CI-CD.md
AUTOMATION.md
DEPLOYMENT-PATTERNS.md
DRIFT-MANAGEMENT.md
RELEASE-MANAGEMENT.md
```

# Definition of Done

Layer 8 is complete when repeatable deployment patterns, Terraform standards, repository standards, CI/CD processes and automation patterns exist and can be incorporated into project delivery.