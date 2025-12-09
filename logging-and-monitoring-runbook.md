# Logging and Monitoring Runbook

## Purpose
To define a standardized and repeatable process for enabling, validating, reviewing, and maintaining logging and monitoring practices across critical systems. This SOP ensures sufficient visibility for detecting security events, supporting investigations, and meeting audit requirements.

## Scope
Applies to all systems, applications, cloud resources, endpoints, and network devices required to generate or forward security-relevant logs to the organization's logging platform or SIEM.

## Preconditions
- Central logging/SIEM platform operational (e.g., Splunk, CloudWatch, Sentinel)
- Log sources registered or configured for forwarding
- Defined alerting rules and severity classifications
- Established log retention policy

## Roles
- **Security Analyst:** Reviews alerts, validates log completeness, monitors health, and escalates events.
- **System Owner / IT Administrator:** Ensures system logging is enabled and functioning properly.
- **Incident Response Team:** Engages when escalated alerts indicate a potential incident.

---

## Procedure

### 1. Log Source Onboarding
1. Identify new systems or applications requiring logging.
2. Confirm logging requirements, including:
   - Authentication logs  
   - System events  
   - Change activity  
   - Application-specific logs  
   - Network events  
3. Configure log forwarding agents or native integrations.
4. Verify logs reach the SIEM by:
   - Searching for recent events  
   - Confirming correct host identifiers  
   - Ensuring expected event types are present  
5. Document onboarding completion in the logging inventory.

---

### 2. Daily Monitoring Tasks
Perform the following monitoring tasks at least once per day:

1. Review SIEM alert dashboard for:
   - High-severity alerts  
   - Authentication anomalies  
   - Malware detections  
   - Privileged activity deviations  
   - Unauthorized configuration changes  
2. Acknowledge and triage alerts following the Incident Triage SOP.
3. Investigate false positives and tune alert rules as needed.
4. Document findings and notable events.

---

### 3. Weekly Log Health Checks
1. Validate that all critical log sources are actively forwarding events.
2. Review ingestion or parsing errors.
3. Confirm timestamps and time synchronization are correct.
4. Check for abnormal dips or spikes in event volumes.
5. Verify log retention paths are not nearing capacity.

If gaps are detected:
- Notify system owners  
- Open remediation tickets  
- Document issues in the logging health record  

---

### 4. Monthly Review
1. Review log retention settings for compliance with policy.
2. Validate correct functioning of:
   - Application logs  
   - Security tools  
   - Cloud resource logs (CloudTrail, VPC Flow Logs, etc.)  
3. Assess alert rule coverage; identify missing detection logic.
4. Update the log source inventory if new systems have been added.
5. Perform quarterly sampling of logs to ensure:
   - Required fields are present  
   - Logs have correct formats  
   - Parsers and enrichments function properly  

---

### 5. Alert Rule Management
1. Establish severity levels (Critical, High, Medium, Low).
2. Create new rules based on:
   - Threat intelligence  
   - Prior incidents  
   - Audit findings  
   - Emerging risks  
3. Test rule outputs in a controlled environment.
4. Document changes to detection logic.
5. Review alert volume to ensure that alerts remain actionable.

---

## Evidence Requirements
- Daily and weekly log health check records
- Alert review notes and triage outcomes
- Inventory of log sources and onboarding status
- Documentation of rule changes or tuning actions
- Samples of ingestion validation queries

---

## Success Criteria
- All critical log sources consistently forward events.
- No significant logging gaps are detected.
- Alerts are reviewed and triaged within established SLAs.
- Logging supports effective investigations and compliance audits.
- Rule tuning maintains balance between visibility and noise reduction.

---

## Framework Alignment

| Framework | Control | Description |
|----------|---------|-------------|
| NIST 800-53 | AU-2 | Audit event logging. |
| NIST 800-53 | AU-6 | Review and analysis of audit logs. |
| NIST 800-53 | AU-12 | Log retention and protection. |
| NIST 800-53 | SI-4 | Monitoring for suspicious activity. |
| NIST CSF | DE.CM-1 | Activity is monitored to detect anomalies. |
| NIST CSF | DE.CM-7 | Monitoring for unauthorized access. |
| CIS Controls | 8.2 | Collect audit logs. |
| CIS Controls | 8.5 | Centralize log management. |
| CIS Controls | 6.3 | Monitor administrative activity. |
