# Phase 05 — Platform Foundation & Environment Build

## 1. Purpose

Establish and validate the foundational Genesys Cloud platform configuration required to support the solution defined during Phase 04 — Solution Architecture & Detailed Design.

This phase creates the technical foundation upon which all subsequent Genesys Cloud configuration, integrations, testing and deployment activities will be built.

The objective is to ensure that the Genesys Cloud environment is:

- Correctly provisioned
- Correctly structured
- Secure
- Accessible
- Network-ready
- Identity-ready
- Environment-ready
- Configured according to the approved architecture
- Ready for feature configuration and solution build

This phase should establish the platform foundation without prematurely implementing detailed business functionality that belongs in later build phases.

---

# 2. Phase Objective

By the end of Phase 05:

- Genesys Cloud organisation(s) are provisioned.
- Correct Genesys Cloud region is confirmed.
- Licensing is confirmed.
- Organisation settings are configured.
- Environment strategy is implemented.
- Divisions are established.
- Identity provider integration is configured.
- SSO is configured where applicable.
- MFA requirements are implemented where applicable.
- SCIM provisioning is configured where applicable.
- Administrative groups are established.
- Initial roles and permissions are configured.
- Core users are provisioned.
- Locations and sites are configured where required.
- Telephony foundation is established.
- Carrier / BYOC prerequisites are configured where applicable.
- Network prerequisites are validated.
- DNS / firewall / proxy requirements are validated.
- OAuth applications are established where required.
- Integration foundation is established.
- Naming standards are implemented.
- Configuration standards are established.
- Initial platform validation is completed.
- Platform foundation defects are resolved.
- Environment is ready for Phase 06 — Feature Configuration & Solution Build.

---

# 3. Phase Entry Criteria

Phase 05 should not commence until the following have been completed:

- Phase 04 — Solution Architecture & Detailed Design is approved.
- Gate 04 has passed.
- Genesys Cloud architecture is approved.
- Environment strategy is approved.
- Identity architecture is approved.
- Security architecture is approved.
- Telephony architecture is approved.
- Network architecture is approved.
- Licensing requirements are understood.
- Customer technical contacts are identified.
- Required third-party contacts are identified.
- Required provisioning information is available.
- Build sequence is approved.

---

# 4. Platform Foundation Workstreams

The phase is structured into the following workstreams:

### 05.01 Organisation Provisioning
### 05.02 Region & Licensing Validation
### 05.03 Organisation Configuration
### 05.04 Environment Establishment
### 05.05 Division Foundation
### 05.06 Identity Provider Foundation
### 05.07 SSO Foundation
### 05.08 MFA & Authentication Foundation
### 05.09 SCIM / User Provisioning Foundation
### 05.10 Groups, Roles & Permissions Foundation
### 05.11 Core User Provisioning
### 05.12 Sites & Locations
### 05.13 Network Foundation
### 05.14 Telephony Foundation
### 05.15 Carrier / BYOC Foundation
### 05.16 Number Provisioning Foundation
### 05.17 OAuth & API Foundation
### 05.18 Integration Foundation
### 05.19 Configuration Standards
### 05.20 Platform Monitoring & Audit Foundation
### 05.21 Platform Validation
### 05.22 Foundation Defect Resolution
### 05.23 Phase Gate Preparation

---

# 5. Organisation Provisioning

Establish the Genesys Cloud organisation(s) required by the approved environment strategy.

## Activities

1. Confirm organisation requirements.
2. Confirm organisation ownership.
3. Confirm organisation region.
4. Confirm organisation naming.
5. Provision required Genesys Cloud organisation(s).
6. Confirm organisation access.
7. Confirm organisation administrator.
8. Confirm organisation licensing.
9. Confirm organisation status.
10. Document organisation identifiers.
11. Document organisation URLs.
12. Document administrative ownership.

## Validate

- Organisation exists.
- Correct region is assigned.
- Correct organisation is being used.
- Administrative access is available.
- Required licensing is available.

## Output

**Genesys Cloud Organisation Provisioning Record**

---

# 6. Region & Licensing Validation

Validate that the deployed platform aligns with the approved architecture and commercial requirements.

## Activities

1. Confirm Genesys Cloud region.
2. Confirm data residency requirements.
3. Confirm available licences.
4. Confirm purchased licences.
5. Confirm feature entitlements.
6. Confirm user licence requirements.
7. Confirm WEM licences where applicable.
8. Confirm digital licences where applicable.
9. Confirm recording requirements.
10. Confirm telephony entitlements.
11. Confirm third-party licensing.
12. Identify licensing gaps.

## Output

**Licensing & Entitlement Validation**

---

# 7. Organisation Configuration

Configure organisation-level settings that form the platform baseline.

## Activities

Configure as required:

- Organisation name
- Time zone
- Language
- Date / time format
- Business units
- Organisation preferences
- Security settings
- Password policies where applicable
- Session policies
- Notification settings
- Email configuration
- General platform settings

## Validate

Configuration must match the approved solution design.

## Output

**Organisation Configuration Baseline**

---

# 8. Environment Establishment

Implement the approved environment strategy.

Potential model:

```text
Development
     ↓
System Integration Testing
     ↓
User Acceptance Testing
     ↓
Production
```

## Activities

1. Confirm required environments.
2. Confirm organisation allocation.
3. Establish required organisations.
4. Establish environment naming.
5. Establish environment ownership.
6. Define environment access.
7. Define environment-specific credentials.
8. Define environment-specific URLs.
9. Define environment-specific integrations.
10. Define environment-specific data.
11. Document configuration promotion process.

## Environment Matrix

| Environment | Purpose | Organisation | Owner | Data | Integrations |
|---|---|---|---|---|---|
| Development | Build | TBD | TBD | Test | Mock / Test |
| SIT | Integration testing | TBD | TBD | Test | Test |
| UAT | Business acceptance | TBD | TBD | Sanitised / Test | UAT |
| Production | Live service | TBD | TBD | Production | Production |

## Output

**Environment Configuration Matrix**

---

# 9. Division Foundation

Establish the division structure defined in Phase 04.

## Activities

1. Create divisions.
2. Apply division naming standards.
3. Define division descriptions.
4. Assign initial administrative access.
5. Validate division visibility.
6. Confirm object ownership strategy.
7. Document division assignments.

## Validate

- Divisions exist.
- Naming follows standards.
- Administrative access is correct.
- Security boundaries are working as designed.

## Output

**Division Configuration Baseline**

---

# 10. Identity Provider Foundation

Establish the identity integration required for user authentication.

## Activities

1. Confirm identity provider.
2. Confirm authentication protocol.
3. Confirm metadata.
4. Confirm certificates.
5. Confirm domains.
6. Configure identity provider integration.
7. Configure trust relationships.
8. Validate identity provider connectivity.
9. Validate certificate validity.
10. Document configuration.

## Supported Architecture

Depending on the approved design, configure:

- SAML
- OpenID Connect
- Microsoft Entra ID
- Okta
- Other supported identity provider

## Output

**Identity Provider Configuration**

---

# 11. SSO Foundation

Configure Single Sign-On where required.

## Activities

1. Configure SSO.
2. Configure identity provider metadata.
3. Configure service provider settings.
4. Configure claims.
5. Configure user identifiers.
6. Configure group claims where required.
7. Validate authentication.
8. Test administrator login.
9. Test standard user login.
10. Test failed authentication.
11. Document SSO configuration.

## Test Scenarios

- Valid login
- Invalid login
- User not provisioned
- Disabled user
- Expired credentials
- MFA challenge
- Session timeout
- Logout

## Output

**SSO Configuration & Validation Record**

---

# 12. MFA & Authentication Foundation

Implement approved authentication security controls.

## Activities

Configure as applicable:

- MFA
- Authentication policies
- Password requirements
- Session timeout
- Login restrictions
- Trusted devices
- Conditional access
- Identity provider policies

## Validate

Security controls must align with:

- Security architecture
- Customer security policy
- Compliance requirements

## Output

**Authentication Security Baseline**

---

# 13. SCIM / User Provisioning Foundation

Where applicable, configure automated user and group provisioning.

## Activities

1. Configure SCIM integration.
2. Configure provisioning credentials.
3. Configure user mapping.
4. Configure group mapping.
5. Configure attribute mapping.
6. Configure provisioning rules.
7. Configure deprovisioning.
8. Validate user creation.
9. Validate user updates.
10. Validate user disablement.
11. Validate user deletion behaviour.
12. Validate group provisioning.

## Test

```text
Identity Provider
       ↓
SCIM
       ↓
Genesys Cloud
       ↓
User
       ↓
Group
       ↓
Role / Permission
```

## Output

**SCIM Provisioning Configuration**

---

# 14. Groups, Roles & Permissions Foundation

Establish the foundational RBAC model.

## Activities

1. Create security groups.
2. Create administrative groups.
3. Create required roles.
4. Configure permissions.
5. Configure division access.
6. Configure group membership.
7. Configure licence assignments.
8. Validate permission inheritance.
9. Validate administrative boundaries.
10. Document RBAC configuration.

## Role Validation

Test representative personas:

- Platform Administrator
- Technical Administrator
- Supervisor
- Agent
- Reporting User
- WEM User
- Integration User

## Output

**RBAC Configuration Baseline**

---

# 15. Core User Provisioning

Create or provision the initial users required for platform administration and implementation.

## Activities

Provision:

- Platform administrators
- Solution architects
- Technical leads
- Build team
- Test team
- Customer administrators
- Integration service users where applicable

## Configure

- Name
- Email
- Division
- Groups
- Roles
- Licences
- Skills where required
- Languages where required

## Validate

Each user must be able to perform the activities appropriate to their assigned role and no more.

## Output

**Initial User Provisioning Record**

---

# 16. Sites & Locations

Establish physical and logical locations where required.

## Activities

1. Define site naming.
2. Create locations.
3. Configure addresses.
4. Configure time zones.
5. Configure site settings.
6. Configure network associations.
7. Configure telephony associations.
8. Validate location structure.

## Consider

- Contact centre locations
- Branches
- Offices
- Remote work
- Disaster recovery sites
- Virtual / logical locations

## Output

**Sites & Locations Configuration**

---

# 17. Network Foundation

Validate network readiness for Genesys Cloud.

## Activities

1. Validate Internet connectivity.
2. Validate DNS.
3. Validate firewall rules.
4. Validate proxy configuration.
5. Validate WebRTC connectivity.
6. Validate SIP connectivity.
7. Validate RTP connectivity.
8. Validate TLS connectivity.
9. Validate required domains.
10. Validate required ports.
11. Validate QoS.
12. Validate bandwidth.
13. Validate remote-user connectivity.

## Network Validation

Measure where appropriate:

- Latency
- Jitter
- Packet loss
- Bandwidth
- DNS resolution
- TLS connectivity

## Voice Quality

Validate that the network supports the required:

- Signalling
- Media
- WebRTC
- SIP
- RTP

## Output

**Network Readiness Validation**

---

# 18. Telephony Foundation

Establish the telephony components required for the approved architecture.

## Activities

Depending on the selected architecture:

### Genesys Cloud Voice

- Confirm telephony configuration.
- Configure sites.
- Configure locations.
- Configure phone settings.
- Prepare number assignment.

### BYOC Cloud

- Configure carrier relationship.
- Configure trunks.
- Configure external trunks.
- Configure phone trunks.
- Configure outbound routes.
- Configure number plans.

### BYOC Premises

- Confirm Edge requirements.
- Validate hardware / virtual requirements.
- Validate network.
- Configure Edges.
- Configure trunks.
- Configure sites.

### Hybrid

Implement the relevant combination of components.

## Output

**Telephony Foundation Configuration**

---

# 19. Carrier / BYOC Foundation

Where applicable, establish carrier connectivity.

## Activities

1. Confirm carrier readiness.
2. Confirm SIP requirements.
3. Configure trunks.
4. Configure authentication.
5. Configure transport.
6. Configure codecs.
7. Configure media settings.
8. Configure failover.
9. Configure outbound routes.
10. Configure inbound routes.
11. Validate carrier connectivity.

## Test

- Inbound call
- Outbound call
- Caller ID
- DTMF
- Transfer
- Hold
- Recording
- RTP
- Call termination
- Failover

## Output

**Carrier Connectivity Validation**

---

# 20. Number Provisioning Foundation

Establish the initial number configuration.

## Activities

1. Confirm number inventory.
2. Confirm number ownership.
3. Confirm porting status.
4. Provision temporary numbers where required.
5. Configure inbound numbers.
6. Configure outbound caller ID.
7. Configure emergency numbers.
8. Configure number associations.
9. Validate number routing.

## Number Register

Maintain:

| Number | Type | Purpose | Carrier | Environment | Destination | Status |
|---|---|---|---|---|---|---|
| TBD | DID | Test | TBD | DEV | TBD | Planned |

## Output

**Number Register**

---

# 21. OAuth & API Foundation

Establish API authentication for platform integrations.

## Activities

1. Identify required OAuth clients.
2. Create OAuth clients.
3. Apply naming standards.
4. Configure grant types.
5. Configure scopes.
6. Configure redirect URIs where required.
7. Secure credentials.
8. Document ownership.
9. Document expiration requirements.
10. Validate authentication.

## Security

OAuth clients must follow least-privilege principles.

Do not use broad administrator permissions unless explicitly required.

## Output

**OAuth Client Register**

---

# 22. Integration Foundation

Establish the foundational components required for integrations.

## Activities

1. Confirm integration endpoints.
2. Confirm DNS.
3. Confirm certificates.
4. Confirm firewall rules.
5. Confirm authentication.
6. Confirm service accounts.
7. Confirm middleware.
8. Confirm API gateways.
9. Confirm development endpoints.
10. Confirm test endpoints.
11. Confirm production endpoints.
12. Validate connectivity.

## Integration Matrix

| Integration | Source | Target | Environment | Authentication | Status |
|---|---|---|---|---|---|
| CRM | Genesys | CRM | DEV | OAuth | Planned |
| Identity | IdP | Genesys | DEV | SAML / SCIM | Planned |

## Output

**Integration Foundation Matrix**

---

# 23. Configuration Standards

Implement the standards defined in Phase 04.

## Standards

Apply naming conventions for:

- Organisations
- Divisions
- Groups
- Users
- Queues
- Skills
- Languages
- Architect flows
- Prompts
- Data Actions
- OAuth clients
- Integrations
- Sites
- Locations
- Phone configuration
- Trunks
- Numbers

## Example

```text
<ENV>-<FUNCTION>-<TYPE>-<NAME>
```

Example:

```text
DEV-CC-QUEUE-CUSTOMER-SERVICE
DEV-INT-DATAACTION-CUSTOMER-LOOKUP
DEV-ARCH-FLOW-INBOUND-MAIN
```

The actual naming convention must follow the project-approved standard.

---

# 24. Platform Monitoring & Audit Foundation

Establish the initial monitoring and audit framework.

## Activities

Configure or validate:

- Audit logging
- Administrative activity monitoring
- API monitoring
- Integration monitoring
- Authentication monitoring
- Security monitoring
- Platform health monitoring
- Alerting
- Operational dashboards

## Define

- Monitoring owner
- Alert owner
- Escalation process
- Notification mechanism
- Retention

## Output

**Platform Monitoring Baseline**

---

# 25. Platform Configuration Management

Establish the method used to manage configuration throughout the deployment.

## Activities

Determine:

- Configuration repository
- Source control
- Manual configuration
- Terraform
- API automation
- CI/CD
- Configuration export
- Configuration import
- Change tracking
- Versioning

## Define

```text
Design
   ↓
Configuration
   ↓
Version Control
   ↓
Review
   ↓
Deployment
   ↓
Validation
```

## Output

**Configuration Management Strategy**

---

# 26. Infrastructure-as-Code Foundation

Where Terraform or other automation is part of the approved design, establish the foundation.

## Activities

1. Create repository structure.
2. Establish provider configuration.
3. Configure authentication.
4. Configure state management.
5. Configure backend.
6. Configure environments.
7. Establish module structure.
8. Establish variable standards.
9. Establish output standards.
10. Establish naming standards.
11. Establish validation.
12. Establish plan process.
13. Establish deployment process.
14. Establish state security.

## Example Structure

```text
terraform/
├── environments/
│   ├── dev/
│   ├── sit/
│   ├── uat/
│   └── prod/
│
├── modules/
│   ├── divisions/
│   ├── users/
│   ├── groups/
│   ├── queues/
│   ├── skills/
│   └── architect/
│
├── variables/
├── policies/
└── README.md
```

The actual structure should follow the project implementation standard.

## Output

**Infrastructure-as-Code Foundation**

---

# 27. Platform Security Validation

Conduct an initial platform security review.

## Validate

- Administrator access
- User access
- SSO
- MFA
- SCIM
- OAuth
- API access
- Division boundaries
- Role permissions
- Service accounts
- Credentials
- Secrets
- Audit logging

## Security Test

Attempt to access resources outside the intended security boundary.

Expected result:

**Access denied**

## Output

**Security Foundation Validation**

---

# 28. Platform Validation

Conduct end-to-end foundation validation.

## Validation Categories

### Organisation

- Organisation accessible
- Correct region
- Correct settings

### Identity

- SSO works
- MFA works
- SCIM works
- Users provision correctly

### Security

- Roles work
- Permissions work
- Divisions work
- Administrative boundaries work

### Network

- DNS works
- Firewall works
- WebRTC works
- SIP works where applicable
- RTP works where applicable

### Telephony

- Platform connectivity works
- Carrier connectivity works
- Test numbers work

### API

- OAuth works
- API connectivity works
- Integration endpoints work

---

# 29. Foundation Test Scenarios

The following minimum tests should be completed.

## Test 01 — Administrator Login

Verify an authorised administrator can authenticate and access the required administration functions.

## Test 02 — Standard User Login

Verify a standard user can authenticate and access only the expected functions.

## Test 03 — SSO

Verify SSO authentication.

## Test 04 — MFA

Verify MFA enforcement where applicable.

## Test 05 — SCIM

Verify user provisioning and deprovisioning.

## Test 06 — Role Permissions

Verify role permissions.

## Test 07 — Division Security

Verify division boundaries.

## Test 08 — API Authentication

Verify OAuth authentication.

## Test 09 — Network

Verify required connectivity.

## Test 10 — Telephony

Verify basic voice connectivity where applicable.

## Test 11 — Carrier

Verify carrier connectivity where applicable.

## Test 12 — Number

Verify test number routing.

## Test 13 — Monitoring

Verify audit and monitoring functionality.

---

# 30. Foundation Defect Resolution

Record and resolve all defects discovered during foundation validation.

## Defect Categories

- Organisation
- Licensing
- Identity
- Security
- Network
- Telephony
- Carrier
- Numbering
- API
- Integration
- Automation
- Configuration

## Defect Register

| ID | Description | Severity | Owner | Status | Resolution |
|---|---|---|---|---|---|
| DEF-001 | TBD | High | TBD | Open | TBD |

## Exit Requirement

No Severity 1 or critical foundation defects may remain open before Phase 05 completion.

Severity 2 defects require explicit approval if they remain open.

---

# 31. Documentation

Update project documentation with the deployed foundation.

## Required Documentation

- Organisation register
- Environment register
- Division register
- User register
- Role / permission matrix
- Licence matrix
- Identity configuration
- SSO configuration
- SCIM configuration
- Site / location register
- Network readiness record
- Telephony configuration
- Carrier configuration
- Number register
- OAuth register
- Integration register
- Configuration standards
- Automation repository
- Monitoring design
- Foundation test results
- Defect register

---

# 32. Phase Deliverables

Phase 05 should produce, at minimum:

1. Genesys Cloud organisation(s)
2. Organisation configuration
3. Licensing validation
4. Environment configuration
5. Division configuration
6. Identity provider configuration
7. SSO configuration
8. MFA configuration
9. SCIM configuration where applicable
10. Groups
11. Roles
12. Permissions
13. Core users
14. Sites
15. Locations
16. Network validation
17. Telephony foundation
18. Carrier / BYOC configuration
19. Number foundation
20. OAuth clients
21. Integration foundation
22. Configuration standards
23. Monitoring foundation
24. Configuration management strategy
25. Infrastructure-as-Code foundation where applicable
26. Security validation
27. Platform validation results
28. Foundation defect register
29. Updated project documentation

---

# 33. Phase Dependencies

## Inputs

Phase 05 depends on:

**Phase 04 — Solution Architecture & Detailed Design**

Required inputs include:

- Solution architecture
- Environment strategy
- Security architecture
- Identity architecture
- Telephony architecture
- Network architecture
- RBAC design
- Integration architecture
- Automation strategy
- Naming standards

## Outputs

Phase 05 provides the foundation for:

**Phase 06 — Feature Configuration & Solution Build**

---

# 34. Build Sequence

The recommended high-level implementation order is:

```text
Organisation Provisioning
        ↓
Region / Licensing Validation
        ↓
Organisation Configuration
        ↓
Environment Establishment
        ↓
Divisions
        ↓
Identity Provider
        ↓
SSO / MFA
        ↓
SCIM
        ↓
Groups / Roles / Permissions
        ↓
Core Users
        ↓
Sites / Locations
        ↓
Network Validation
        ↓
Telephony Foundation
        ↓
Carrier / BYOC
        ↓
Numbers
        ↓
OAuth / API Foundation
        ↓
Integration Foundation
        ↓
Configuration Management
        ↓
Automation / IaC
        ↓
Monitoring
        ↓
Security Validation
        ↓
Platform Validation
        ↓
Foundation Defect Resolution
        ↓
Phase Gate
```

Some workstreams may be executed in parallel where dependencies permit.

---

# 35. Parallel Workstreams

To optimise delivery, the following workstreams may run concurrently once their prerequisites are satisfied.

```text
                    ┌── Identity / SSO
                    │
Organisation ───────┼── Network
                    │
                    ├── Telephony / Carrier
                    │
                    ├── OAuth / API
                    │
                    └── IaC / Automation
```

However, no downstream configuration should begin where it depends on an unresolved foundation component.

---

# 36. Platform Foundation Definition of Done

Phase 05 is considered complete when:

- Organisation is provisioned.
- Region is validated.
- Licensing is validated.
- Organisation settings are configured.
- Required environments exist.
- Divisions are configured.
- Identity provider integration is working.
- SSO is working.
- MFA is working where applicable.
- SCIM is working where applicable.
- Roles are configured.
- Permissions are validated.
- Groups are configured.
- Core users are provisioned.
- Sites and locations are configured.
- Network readiness is confirmed.
- Telephony foundation is operational.
- Carrier connectivity is validated where applicable.
- Test numbers are operational where applicable.
- OAuth clients are configured.
- Integration foundation is available.
- Configuration standards are implemented.
- Monitoring foundation is available.
- Automation foundation is available where applicable.
- Security validation is complete.
- Platform validation is complete.
- Critical defects are resolved.
- Documentation is updated.
- Build team has access to the required environments.
- Phase 06 prerequisites are satisfied.

---

# 37. Phase Gate — Gate 05: Platform Foundation Ready

## Entry Criteria

- Gate 04 passed.
- Solution architecture approved.
- Platform provisioning information available.
- Required licences available.
- Required customer technical resources available.

## Exit Criteria

The platform foundation is ready when:

- Genesys Cloud organisation is available.
- Correct region is confirmed.
- Licensing is confirmed.
- Environment strategy is implemented.
- Divisions are established.
- Identity integration is operational.
- Authentication is operational.
- User provisioning is operational.
- RBAC is operational.
- Network connectivity is validated.
- Telephony foundation is operational where applicable.
- Carrier connectivity is validated where applicable.
- Number foundation is ready.
- API authentication is operational.
- Integration foundation is ready.
- Configuration standards are established.
- Automation foundation is established where applicable.
- Monitoring foundation is established.
- Security validation is complete.
- Foundation testing is complete.
- Critical defects are resolved.
- Required documentation is complete.
- Phase 06 build prerequisites are satisfied.

## Gate Decision

**Gate 05 — PLATFORM FOUNDATION READY**

Status:

- **PASS** — Platform ready for solution build
- **PASS WITH CONDITIONS** — Build may commence with documented actions
- **HOLD** — Foundation issues remain
- **FAIL** — Platform not ready for solution build

---

# 38. Key Roles

| Role | Responsibility |
|---|---|
| Project Manager | Coordinate foundation activities |
| Solution Architect | Validate architecture alignment |
| Genesys Cloud Architect | Own Genesys platform foundation |
| Technical Lead | Coordinate technical implementation |
| Genesys Cloud Engineer | Configure Genesys Cloud |
| IAM Lead | Configure identity / SSO / SCIM |
| Security Architect | Validate security |
| Network Engineer | Validate network |
| Telephony Engineer | Configure voice foundation |
| Carrier Engineer | Configure carrier connectivity |
| Integration Engineer | Configure integration foundation |
| DevOps / Automation Engineer | Establish automation / IaC |
| Customer Administrator | Provide customer-side access |
| Customer Network Team | Validate network |
| Customer IAM Team | Configure identity provider |
| Customer Security Team | Validate security |
| Customer Telephony Team | Validate carrier / voice |
| Genesys / Carrier Support | Assist with platform / carrier issues |

---

# 39. Risks

Potential Phase 05 risks include:

### Identity Dependency

SSO / SCIM configuration may depend on customer IAM resources.

### Network Dependency

Firewall, DNS, proxy or QoS changes may require customer network change processes.

### Carrier Dependency

Carrier provisioning and number porting may have external lead times.

### Licensing Dependency

Required features may not be available under the purchased licence model.

### Environment Dependency

Multiple environments may require additional organisations, licences or implementation effort.

### Security Dependency

Security approvals may delay OAuth, SSO, SCIM or integration configuration.

### Automation Dependency

IaC implementation may require additional engineering effort before feature configuration begins.

---

# 40. Architecture Traceability

Every foundation component should be traceable back to the Phase 04 architecture.

Recommended relationship:

```text
Phase 04 Architecture
        ↓
Foundation Component
        ↓
Configuration
        ↓
Validation
        ↓
Phase 06 Build
```

Examples:

```text
Identity Architecture
        ↓
SSO Configuration
        ↓
SSO Test
        ↓
User Provisioning
```

```text
Telephony Architecture
        ↓
Carrier / Trunk Configuration
        ↓
Voice Test
        ↓
Inbound / Outbound Build
```

```text
Automation Architecture
        ↓
Terraform Foundation
        ↓
Terraform Validation
        ↓
Feature Modules
```

---

# 41. Phase 05 Effort Considerations

Effort is highly dependent on project scope and should be estimated using the project's deployment complexity classification.

## Complexity Factors

Consider:

- Number of environments
- Number of organisations
- Number of users
- Number of sites
- Identity provider complexity
- SSO complexity
- SCIM requirements
- Security requirements
- Number of divisions
- Telephony architecture
- Carrier complexity
- Number porting
- Network complexity
- Number of integrations
- Automation requirements
- Terraform requirements
- Compliance requirements
- Customer change-control requirements

## Complexity Classification

### Small

Single organisation, simple identity, limited telephony and limited integrations.

### Medium

Multiple environments, enterprise identity, carrier integration, multiple sites and several integrations.

### Large

Multiple organisations, complex identity, multiple carriers, multiple sites, extensive integrations, strict security and compliance, and significant automation.

---

# 42. Phase 05 Effort Categories

The final project spreadsheet should estimate effort separately for:

- Project Management
- Solution Architecture
- Genesys Configuration
- Identity / IAM
- Network
- Telephony
- Carrier
- Security
- Integration
- DevOps / Automation
- Testing
- Documentation
- Customer Activities
- Third-Party Activities

Effort should be represented in:

**Person Hours**

and, where useful:

**Person Days**

---

# 43. Recommended Task Decomposition

The master deployment spreadsheet should break Phase 05 into tasks at a level that allows:

- Ownership
- Dependency tracking
- Effort estimation
- Scheduling
- Progress tracking
- Status reporting
- Resource planning

Recommended columns:

| Column | Description |
|---|---|
| Phase | Phase number |
| Workstream | Workstream |
| Task ID | Unique task identifier |
| Parent Task | Parent task |
| Task | Task description |
| Description | Detailed activity |
| Dependency | Required predecessor |
| Role | Primary resource |
| Customer Role | Customer dependency |
| Third Party | Third-party dependency |
| Environment | DEV / SIT / UAT / PROD |
| Automation | Manual / Automated / Hybrid |
| Effort Hours | Estimated effort |
| Duration | Estimated elapsed time |
| Critical Path | Yes / No |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Status | Planned / In Progress / Complete |
| Notes | Additional information |

---

# 44. Phase 05 Task Ordering Principle

Tasks should be sequenced according to technical dependency rather than simply organisational ownership.

The general ordering principle is:

**Provision → Secure → Connect → Configure → Validate → Handover**

More specifically:

```text
Provision
    ↓
Configure
    ↓
Secure
    ↓
Connect
    ↓
Validate
    ↓
Document
    ↓
Approve
```

No feature build should depend on undocumented or unvalidated foundation configuration.

---

# 45. Phase 05 Primary Outputs

At the end of the phase, the implementation team should have:

**A provisioned, secured, connected and validated Genesys Cloud platform foundation that is ready for detailed solution configuration.**

The transition should be:

```text
Phase 04
Solution Architecture
        ↓
Phase 05
Platform Foundation
        ↓
Phase 06
Feature Configuration
```

---

# Layer 1 Position

| Phase | Status |
|---|---|
| **01 — Project Initiation & Mobilisation** | Baseline |
| **02 — Discovery & Current-State Assessment** | Baseline |
| **03 — Requirements & Solution Definition** | Baseline |
| **04 — Solution Architecture & Detailed Design** | Baseline |
| **05 — Platform Foundation & Environment Build** | **Defined** |
| 06 — Feature Configuration & Solution Build | Next |
| 07 — Integration & Data Migration | Pending |
| 08 — Testing & Validation | Pending |
| 09 — Operational Readiness & Cutover Preparation | Pending |
| 10 — Production Deployment & Go-Live | Pending |
| 11 — Hypercare & Stabilisation | Pending |
| 12 — BAU Handover & Project Closure | Pending |

---

## Reference

**Methodology:** Genesys Cloud Deployment Project Template  
**Phase:** 05 — Platform Foundation & Environment Build  
**Phase Gate:** Gate 05 — Platform Foundation Ready  
**Previous Phase:** 04 — Solution Architecture & Detailed Design  
**Next Phase:** 06 — Feature Configuration & Solution Build