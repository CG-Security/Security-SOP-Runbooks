# Monthly Patching Runbook

## Purpose
To define a repeatable workflow for monthly patching and vulnerability remediation.

## Scope
Applies to all servers, endpoints, and applications that receive periodic patches.

## Preconditions
- Latest vulnerability scan available
- Maintenance window approved
- Backup snapshots completed (where applicable)

## Roles
- IT Administrator: Applies patches
- Security Analyst: Reviews vulnerability data
- System Owner: Approves downtime if needed

## Procedure
1. Retrieve the latest vulnerability scan report.
2. Identify critical and high vulnerabilities requiring patching.
3. Prioritize systems based on:
   - Severity
   - Exposure
   - Business impact
4. Schedule maintenance windows as required.
5. Apply OS and application patches.
6. Reboot systems where applicable.
7. Validate post-patch system functionality.
8. Perform targeted rescans to confirm remediation.
9. Document exceptions and deferred systems.

## Evidence Requirements
- Scan results before and after patching
- Change tickets or patch logs
- Exception documentation

## Success Criteria
- Critical and high vulnerabilities remediated.
- System stability maintained.
- Patch cycle fully documented.
