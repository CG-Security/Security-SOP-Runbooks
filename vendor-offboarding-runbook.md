# Vendor Offboarding Runbook

## Purpose
To ensure the secure offboarding of SaaS vendors or third-party systems.

## Scope
All vendor relationships being terminated.

## Preconditions
- Offboarding approval
- Access to vendor administrative console

## Roles
- Security Analyst: Oversees data deletion and access removal
- IT Administrator: Removes integration points
- System Owner: Confirms data retention requirements

## Procedure
1. Identify assets, integrations, and data associated with the vendor.
2. Revoke user and API access.
3. Extract or migrate data as needed.
4. Request data deletion or obtain proof of deletion.
5. Remove SSO, API keys, and technical integrations.
6. Update asset and vendor inventories.
7. Document closure.

## Evidence Requirements
- Access removal logs
- Data extraction or deletion confirmation
- Inventory updates

## Success Criteria
- All access removed
- Data handled according to retention requirements

## Framework Alignment

| Framework | Control | Description |
|----------|---------|-------------|
| NIST 800-53 | SA-9(2) | Termination of system and service provider relationships. |
| NIST 800-53 | MP-6 | Media sanitization and data deletion. |
| NIST 800-53 | AC-2(8) | Removal of system access when no longer needed. |
| NIST CSF | ID.SC-4 | Termination processes for third-party services. |
| CIS Controls | 15.5 | Ensure proper offboarding of service providers. |
| CIS Controls | 6.6 | Remove accounts and credentials after use. |
