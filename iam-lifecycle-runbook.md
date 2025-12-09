# IAM Lifecycle Runbook

## Purpose
To ensure consistent onboarding, modification, and offboarding of user identities across the environment.

## Scope
Covers all user accounts, administrator accounts, and service accounts.

## Preconditions
- Authorized access request or HR onboarding ticket
- Defined access roles and group mappings

## Roles
- IT Administrator: Executes lifecycle steps
- Security Analyst: Oversees governance and adherence
- Hiring Manager / System Owner: Approves required access

## Procedure

### Onboarding
1. Receive approved access request or HR ticket.
2. Create user identity following naming conventions.
3. Assign baseline access groups.
4. Apply role-based access if specified.
5. Enforce MFA enrollment during first login.
6. Provide user with account setup instructions.
7. Document completion in onboarding record.

### Access Modifications
1. Validate modification request and approval.
2. Review current access and role assignments.
3. Adjust group membership or permissions accordingly.
4. Notify requestor and system owner upon completion.
5. Record change in IAM audit log.

### Offboarding
1. Receive termination or separation notice.
2. Disable user account immediately upon effective date.
3. Revoke all administrative roles.
4. Remove access from all applications and systems.
5. Reassign ownership of shared resources if necessary.
6. Document completion in offboarding record.

## Evidence Requirements
- Access requests and approvals
- IAM audit logs
- Onboarding/offboarding checklists

## Success Criteria
- No active access remains after offboarding.
- Users receive only appropriate access.
- All lifecycle actions are fully documented.
