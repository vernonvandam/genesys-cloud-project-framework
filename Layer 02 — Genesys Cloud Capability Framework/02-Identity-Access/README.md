# Layer 2.02 — Identity & Access

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Capability Framework  
**Domain:** 2.02 — Identity & Access  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the identity, authentication, authorisation, provisioning, privileged-access and access-governance capabilities required to securely operate Genesys Cloud.

---

# 1. Purpose

Identity & Access establishes the security foundation for all users, administrators, integrations and automated processes accessing Genesys Cloud.

The domain covers:

- Human identity
- Authentication
- Federation
- Single sign-on
- Multi-factor authentication
- User provisioning
- User lifecycle
- SCIM
- Groups
- Roles
- Permissions
- Divisions
- Licensing
- API identities
- OAuth clients
- Service identities
- Administrative access
- Emergency access
- Auditability
- Access reviews
- Environment separation

Identity & Access must be designed before detailed configuration of downstream Genesys Cloud capabilities.

---

# 2. Scope

```text
02 Identity & Access
│
├── 02.01 Identity Architecture & Governance
├── 02.02 User Lifecycle Management
├── 02.03 User Provisioning & Deprovisioning
├── 02.04 SSO & Identity Federation
├── 02.05 Authentication & MFA
├── 02.06 SCIM & Automated Provisioning
├── 02.07 Groups
├── 02.08 Roles & Permissions
├── 02.09 Division-Based Access
├── 02.10 Licensing Assignment
├── 02.11 External / Guest Access
├── 02.12 Service Accounts & API Identities
├── 02.13 OAuth Clients & Credentials
├── 02.14 Security & Authentication Policies
├── 02.15 Audit & Administrative Traceability
├── 02.16 Break-Glass & Emergency Access
├── 02.17 Access Reviews & Recertification
├── 02.18 Privileged Administration
├── 02.19 Environment Access
├── 02.20 Integration Identities & Secrets
└── 02.21 Identity & Access Validation
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Identity Architecture & Governance | Required |
| User Lifecycle Management | Required |
| User Provisioning & Deprovisioning | Required |
| SSO & Identity Federation | Conditional |
| Authentication & MFA | Required |
| SCIM & Automated Provisioning | Conditional |
| Groups | Required |
| Roles & Permissions | Required |
| Division-Based Access | Required |
| Licensing Assignment | Required |
| External / Guest Access | Conditional |
| Service Accounts & API Identities | Conditional |
| OAuth Clients & Credentials | Conditional |
| Security & Authentication Policies | Required |
| Audit & Administrative Traceability | Required |
| Break-Glass & Emergency Access | Conditional |
| Access Reviews & Recertification | Required |
| Privileged Administration | Required |
| Environment Access | Required |
| Integration Identities & Secrets | Conditional |
| Identity & Access Validation | Required |

---

# 4. Key Design Principles

1. Use enterprise identity as the authoritative source wherever practical.
2. Avoid unmanaged local credentials where federation is appropriate.
3. Apply least privilege.
4. Separate administrative access from standard operational access.
5. Use role-based access rather than individual permission assignments where practical.
6. Use divisions to establish logical access boundaries where appropriate.
7. Automate joiner/mover/leaver processes where feasible.
8. Do not grant broad administrative permissions to simplify implementation.
9. Treat API identities as security principals requiring lifecycle management.
10. Protect OAuth credentials and secrets.
11. Establish emergency access before production.
12. Review privileged access regularly.
13. Test deprovisioning as rigorously as provisioning.
14. Document all customer-specific deviations from the standard model.
15. Validate all capabilities against current Genesys Cloud functionality, licensing and regional availability.

---

# 5. Dependencies

Identity & Access depends on:

- Core Platform & Organisation
- Organisation region
- Division model
- Customer IAM architecture
- Customer security policies
- Licensing
- Network/security architecture
- Integration architecture

Identity & Access is a prerequisite for:

- Users
- Queues
- Routing
- WEM
- Quality Management
- Analytics
- Digital
- Architect administration
- Integrations
- Production operations

---

# 6. Layer 1 Mapping

| Layer 1 Phase | Identity & Access Activities |
|---|---|
| Phase 1 — Initiation | Identify identity owners and governance |
| Phase 2 — Discovery | Assess IAM architecture |
| Phase 3 — Requirements | Define access requirements |
| Phase 4 — Architecture | Design identity and security architecture |
| Phase 5 — Platform Foundation | Establish identity controls |
| Phase 6 — Solution Build | Configure users, roles and access |
| Phase 7 — Integration & Migration | Configure identity integrations |
| Phase 8 — Testing | Validate authentication and authorisation |
| Phase 9 — Operational Readiness | Establish access-management processes |
| Phase 10 — Production Deployment | Validate production access |
| Phase 11 — Hypercare | Monitor access issues |
| Phase 12 — BAU Handover | Transfer identity administration |

---

# 7. Standard Spreadsheet Task Model

Every activity must be decomposable into:

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | 2 |
| Domain | 02 |
| Capability | Capability name |
| Phase | Layer 1 phase |
| Workstream | Identity & Access |
| Task | Individual activity |
| Description | Implementation detail |
| Classification | Required / Conditional / Optional |
| Dependency | Predecessor |
| Role | Delivery owner |
| Customer Responsibility | Yes / No |
| Environment | DEV / TEST / UAT / PROD |
| Effort | Hours |
| Duration | Elapsed duration |
| Deliverable | Task output |
| Acceptance Criteria | Completion condition |
| Critical Path | Yes / No |

---

# 8. Domain Deliverables

Potential deliverables include:

- Identity architecture
- IAM integration design
- User lifecycle model
- SSO design
- MFA design
- SCIM design
- Group model
- Role/permission matrix
- Division access matrix
- Licensing matrix
- API identity register
- OAuth client register
- Privileged access model
- Break-glass procedure
- Access review process
- Environment access matrix
- Identity test plan
- Access validation evidence
- BAU access-management procedures

---

# 9. Standard Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Incorrect role assignment | High | Role matrix and least-privilege review |
| Excessive administrator access | High | Privileged-access governance |
| Failed SSO | High | Test authentication before production |
| Incorrect SCIM mapping | High | Test joiner/mover/leaver scenarios |
| Deprovisioning failure | Critical | Explicit offboarding tests |
| Licensing mismatch | High | Validate licence mapping |
| API credential exposure | Critical | Secure secret management |
| Division boundaries incorrect | High | Validate resource/access matrix |
| Emergency access unavailable | High | Establish and test break-glass |
| Access review not operationalised | Medium | Define recurring governance process |

---

# 10. Definition of Done

The domain is complete when:

- Identity architecture is approved.
- IAM ownership is defined.
- User lifecycle is documented.
- Authentication model is approved.
- MFA requirements are implemented where required.
- SSO is configured where required.
- SCIM is configured where required.
- Groups are defined.
- Roles and permissions are defined.
- Division access is defined.
- Licensing is mapped.
- API identities are documented.
- OAuth clients are documented where applicable.
- Privileged access is controlled.
- Emergency access is established where required.
- Audit requirements are validated.
- Access review process is established.
- Environment access is controlled.
- Identity testing has passed.
- Customer acceptance has been obtained.

---

# 11. Phase Gate

```text
IDENTITY ARCHITECTURE APPROVED
          +
AUTHENTICATION CONFIGURED
          +
AUTHORISATION MODEL APPROVED
          +
PROVISIONING VALIDATED
          +
PRIVILEGED ACCESS CONTROLLED
          +
IDENTITY TESTING PASSED
          +
CUSTOMER ACCEPTANCE
          ↓
IDENTITY & ACCESS READY
```

---

# 12. Domain File Catalogue

```text
02-Identity-Access/
│
├── README.md
├── 01-Identity-Architecture-Governance.md
├── 02-User-Lifecycle-Management.md
├── 03-User-Provisioning-Deprovisioning.md
├── 04-SSO-Identity-Federation.md
├── 05-Authentication-MFA.md
├── 06-SCIM-Automated-Provisioning.md
├── 07-Groups.md
├── 08-Roles-Permissions.md
├── 09-Division-Based-Access.md
├── 10-Licensing-Assignment.md
├── 11-External-Guest-Access.md
├── 12-Service-Accounts-API-Identities.md
├── 13-OAuth-Clients-Credentials.md
├── 14-Security-Authentication-Policies.md
├── 15-Audit-Administrative-Traceability.md
├── 16-Break-Glass-Emergency-Access.md
├── 17-Access-Reviews-Recertification.md
├── 18-Privileged-Administration.md
├── 19-Environment-Access.md
├── 20-Integration-Identities-Secrets.md
└── 21-Identity-Access-Validation.md
```

---

# 13. Domain Completion

The individual capability documents below form the detailed Layer 2.02 Identity & Access catalogue.

Each document is intended to become the source for detailed project schedule and estimation tasks.

---

# Domain Completion Gate

**Status:** Ready for capability-level estimation and task decomposition.
