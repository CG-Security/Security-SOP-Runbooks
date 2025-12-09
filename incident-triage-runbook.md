# Incident Triage Runbook

## Purpose
To provide a structured workflow for evaluating and triaging reported security events.

## Scope
Applies to all user-reported incidents, system alerts, and observed suspicious activity.

## Preconditions
- Access to logging tools and security console
- Defined severity classification model

## Roles
- Security Analyst: Performs triage
- IT Support: Assists with containment
- System Owner: Provides system context

## Procedure
1. Gather initial details:
   - Reporter name
   - Timestamp
   - Affected system
   - Description of event
2. Classify event type.
3. Identify potential impact and severity.
4. Collect logs, alerts, or screenshots.
5. Perform initial containment if required.
6. Escalate high-severity incidents to the incident response team.
7. Document initial findings and actions taken.

## Evidence Requirements
- Triage notes
- Logs or screenshots collected
- Severity assessment

## Success Criteria
- Events accurately classified.
- Critical issues escalated immediately.
- Triage records complete and auditable.

## Framework Alignment

| Framework | Control | Description |
|----------|---------|-------------|
| NIST 800-53 | IR-4 | Incident handling and triage. |
| NIST 800-53 | IR-5 | Incident monitoring. |
| NIST 800-53 | AU-6 | Log review and analysis during triage. |
| NIST CSF | DE.CM-1 | Detection of anomalous activity. |
| NIST CSF | DE.AE-2 | Triage events to understand attack scope. |
| NIST CSF | RS.AN-1 | Analyze notifications from detection systems. |
| CIS Controls | 17.4 | Conduct incident analysis. |
| CIS Controls | 17.5 | Maintain incident logs and documentation. |
