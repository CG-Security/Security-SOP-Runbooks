# Vendor Onboarding Runbook

## Purpose
To ensure new SaaS platforms or vendors undergo proper security evaluation prior to adoption.

## Scope
All third-party providers handling internal or customer data.

## Preconditions
- Completed vendor intake form
- Security documentation availability (SOC 2, ISO, penetration test)

## Roles
- Security Analyst: Performs assessment
- Procurement: Manages contracting
- System Owner: Validates business need

## Procedure
1. Review vendor intake documentation.
2. Collect available security reports (SOC 2, ISO, pen test, etc.).
3. Identify data types handled by the vendor.
4. Evaluate:
   - Authentication model
   - Encryption practices
   - Logging and audit capabilities
   - Data storage locations
5. Document security risks and recommendations.
6. Approve or deny onboarding based on findings.
7. Record final decision and retain documentation.

## Evidence Requirements
- Vendor intake form
- Security assessment notes
- Approval decision

## Success Criteria
- Risks clearly identified and documented.
- Vendor meets minimum security requirements.

## Framework Alignment

| Framework | Control | Description |
|----------|---------|-------------|
| NIST 800-53 | SA-9 | External system and service provider risk management. |
| NIST 800-53 | SR-3 | Supply chain risk management processes. |
| NIST 800-53 | SR-5 | Assess supplier security documentation and controls. |
| NIST CSF | ID.SC-3 | Suppliers and third-party partners are evaluated for risk. |
| NIST CSF | ID.SC-4 | Supply chain processes are monitored. |
| CIS Controls | 15.1 | Establish third-party security requirements. |
| CIS Controls | 15.4 | Assess service provider compliance. |
