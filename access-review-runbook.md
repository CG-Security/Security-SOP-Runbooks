# Access Review Runbook

## Purpose
To provide a standardized process for conducting periodic user and privileged access reviews to ensure least privilege and compliance with organizational requirements.

## Scope
Applies to all user accounts, privileged accounts, service accounts, and application identities within the environment.

## Preconditions
- Access to HR roster or authoritative user directory
- Access to identity and access management system exports
- Defined owner for each system or application

## Roles
- Security Analyst: Coordinates review and validates findings
- System/Application Owners: Verify access appropriateness
- IT Administrator: Implements required access changes

## Procedure
1. Export user and privileged account lists from each relevant system.
2. Export HR roster or authoritative user directory.
3. Compare user accounts against HR roster to identify:
   - Terminated or inactive users
   - Orphaned accounts
   - Duplicate or inconsistent identities
4. Validate privileged and administrative accounts:
   - Confirm business justification
   - Confirm owner acknowledgment
   - Verify MFA enrollment
5. Review service accounts:
   - Confirm ownership
   - Confirm password rotation schedule
6. Document any accounts requiring changes.
7. Submit access removal or modification requests.
8. Verify that changes were implemented by IT.
9. Record completion, approvals, and reviewer sign-off.

## Evidence Requirements
- User and privilege export files
- Comparison results or review worksheet
- Documentation of removed or modified accounts
- Sign-off from system owners

## Success Criteria
- All inappropriate or unnecessary access is removed or corrected.
- All privileged access has documented justification.
- Review results are recorded and auditable.

## Framework Alignment

| Framework | Control | Description |
|----------|---------|-------------|
| NIST 800-53 | AC-2 | Account management and periodic review of accounts. |
| NIST 800-53 | AC-2(3) | Disables accounts when no longer needed. |
| NIST 800-53 | AC-2(7) | Role-based account management. |
| NIST CSF | PR.AC-1 | Identities and credentials are issued, managed, and verified. |
| NIST CSF | PR.AC-4 | Access permissions and authorizations are managed. |
| CIS Controls | 5.3 | Validate access rights for all user accounts. |
| CIS Controls | 6.3 | Require MFA for administrative accounts. |
