[![Category](https://img.shields.io/badge/Type-Security%20Runbooks-blue)]()
[![Focus](https://img.shields.io/badge/Focus-GRC%20%7C%20SecOps-lightgrey)]()
[![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

# Security-SOP-Runbooks

This repository contains security Standard Operating Procedures (SOPs) designed to support consistent, repeatable execution of core security functions. These runbooks document operational workflows that strengthen governance, improve audit readiness, and reduce ambiguity during day-to-day security activities.

The goal is to provide clear, practical guidance for processes used in real environments, including identity management, patching, vulnerability remediation, vendor evaluation, and incident response.

---

## Repository Structure

    SOPs/
    ├─ access-review-runbook.md
    ├─ iam-lifecycle-runbook.md
    ├─ vendor-onboarding-runbook.md
    ├─ vendor-offboarding-runbook.md
    ├─ monthly-patching-runbook.md
    ├─ vulnerability-management-process.md
    ├─ incident-triage-runbook.md
    └─ backup-and-recovery-runbook.md

Each runbook is written in a consistent structure to support clarity, adoption, and auditability.

---

## SOP Summaries

### Access Review Runbook
Defines steps for conducting periodic privileged and standard access reviews. Includes user exports, HR reconciliation, service account validation, least-privilege verification, and documentation requirements.

### IAM Lifecycle Runbook
Outlines onboarding, role changes, and offboarding processes for user identities. Covers access provisioning, separation of duties, role modifications, MFA enrollment, and account deactivation workflows.

### Monthly Patching Runbook
Documents operational workflows for patch cycles including scan review, prioritization, scheduling, deployment steps, validation checks, and exception handling.

### Vulnerability Management Process
Describes the end-to-end workflow for identifying, prioritizing, remediating, and tracking vulnerabilities. Includes intake, classification, and reporting expectations.

### Incident Triage Runbook
Provides a structured method for taking in and evaluating potential security incidents. Covers reporter intake, classification, initial logs, containment steps, severity estimation, and handoff procedures.

### Vendor Onboarding Runbook
Outlines the steps for evaluating new SaaS or vendor platforms including security documentation review, data flow considerations, authentication model analysis, and contract requirements.

### Vendor Offboarding Runbook
Defines the process for removing vendor access or terminating SaaS use, including data extraction or deletion, access revocation, and record retention.

### Backup and Recovery Runbook
Documents data and system backup requirements, verification steps, testing schedules, and restoration procedures.

---

## Purpose

These SOPs are intended for organizations that want to improve consistency across recurring security operations. They support:

- Governance, Risk, and Compliance (GRC) programs  
- Audit preparation and evidence collection  
- IAM and access governance  
- Vulnerability and patch management  
- Vendor security evaluations  
- Operational standardization for security teams  

All content is generic and safe for public use.

---

## Current Work

- Adding additional SOPs for logging and monitoring  
- Creating standardized templates for escalation and communication  
- Expanding evidence collection expectations within each SOP  
- Adding cross-references to NIST CSF, NIST 800-53, and CIS Controls  

---

## Contact

Questions, suggestions, or contribution ideas can be submitted through GitHub issues.
