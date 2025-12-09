# Security-SOP-Runbooks

[![Category](https://img.shields.io/badge/Type-Security%20Runbooks-blue)]()
[![Focus](https://img.shields.io/badge/Focus-GRC%20%7C%20SecOps-lightgrey)]()
[![Coverage](https://img.shields.io/badge/Includes-SOPs%20%7C%20Templates%20%7C%20Mappings-green)]()
[![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

## Table of Contents
- [Overview](#security-sop-runbooks)
- [Repository Structure](#repository-structure)
- [SOP Summaries](#sop-summaries)
  - [Access Review Runbook](#access-review-runbook)
  - [IAM Lifecycle Runbook](#iam-lifecycle-runbook)
  - [Monthly Patching Runbook](#monthly-patching-runbook)
  - [Vulnerability Management Process](#vulnerability-management-process)
  - [Incident Triage Runbook](#incident-triage-runbook)
  - [Vendor Onboarding Runbook](#vendor-onboarding-runbook)
  - [Vendor Offboarding Runbook](#vendor-offboarding-runbook)
  - [Backup and Recovery Runbook](#backup-and-recovery-runbook)
  - [Audit Evidence Collection Runbook](#audit-evidence-collection-runbook)
  - [Logging and Monitoring Runbook](#logging-and-monitoring-runbook)
- [Templates](#templates)
  - [Access Review Worksheet](#access-review-worksheet)
  - [Incident Intake Form](#incident-intake-form)
  - [Audit Evidence Collection Template](#audit-evidence-collection-template)
  - [Vendor Security Questionnaire](#vendor-security-questionnaire)
  - [Patch Validation Checklist](#patch-validation-checklist)
- [Purpose](#purpose)
- [Roadmap](#roadmap)
- [Contact](#contact)

---

Security-SOP-Runbooks contains security Standard Operating Procedures (SOPs) designed to support consistent, repeatable execution of core security functions. These runbooks document operational workflows that strengthen governance, improve audit readiness, and reduce ambiguity during day-to-day security activities.

The documentation provides clear, practical guidance for processes used in real environments, including identity management, access reviews, patching, vulnerability remediation, vendor evaluation, incident response, audit evidence handling, and logging and monitoring operations.

---

## Repository Structure

The SOPs and templates are stored at the root of this repository or within the `Templates/` folder for ease of navigation.

    access-review-runbook.md
    iam-lifecycle-runbook.md
    monthly-patching-runbook.md
    vulnerability-management-process.md
    incident-triage-runbook.md
    vendor-onboarding-runbook.md
    vendor-offboarding-runbook.md
    backup-and-recovery-runbook.md
    audit-evidence-collection-runbook.md
    logging-and-monitoring-runbook.md

    Templates/
       access-review-worksheet.md
       incident-intake-form.md
       audit-evidence-template.md
       vendor-security-questionnaire.md
       patch-validation-checklist.md

---

## SOP Summaries

### Access Review Runbook
Workflow for performing periodic access reviews, validating user entitlements, privileged access, and service accounts, aligned with least privilege principles and compliance needs.

### IAM Lifecycle Runbook
Defines onboarding, access modification, and offboarding procedures to ensure consistent, secure identity lifecycle management.

### Monthly Patching Runbook
Operational workflow for monthly patch cycles, including prioritization, scheduling, validation, rescans, and documentation requirements.

### Vulnerability Management Process
End-to-end workflow for vulnerability intake, validation, prioritization, remediation tracking, and exception handling.

### Incident Triage Runbook
Structured procedure for evaluating and triaging security events, collecting initial evidence, performing containment, and escalating high-severity cases.

### Vendor Onboarding Runbook
Security evaluation workflow for new SaaS vendors or service providers, including documentation review, authentication model analysis, and risk identification.

### Vendor Offboarding Runbook
Procedures for terminating vendor relationships, performing data extraction or deletion, removing access, and updating inventories.

### Backup and Recovery Runbook
Defines operational expectations for backup scheduling, integrity checks, test restores, and system recovery workflows.

### Audit Evidence Collection Runbook
Standardized procedure for collecting, validating, naming, storing, and transmitting audit evidence for internal and external assessments.

### Logging and Monitoring Runbook
Defines expectations for log collection, retention, health checks, monitoring responsibilities, alert triage workflow, and validation of logging completeness.

---

## Templates

This repository includes a collection of operational templates that support the execution of the SOPs. These templates provide standardized documentation formats used during access reviews, incident handling, audit evidence collection, vendor evaluations, and patch validation.

All templates are located in the `Templates/` folder.

### Access Review Worksheet
A structured table for documenting quarterly or periodic access reviews, including privileged access validation, reviewer notes, identified issues, and required actions.

### Incident Intake Form
Standardized form used to capture initial details of potential security incidents, including reporter information, system impact, evidence, severity estimation, and triage notes.

### Audit Evidence Collection Template
Template aligned with the Audit Evidence SOP for documenting evidence requests, validation checklists, storage details, and reviewer sign-off for audits and assessments.

### Vendor Security Questionnaire
Due-diligence questionnaire aligned to the Vendor Onboarding SOP. Captures information on authentication, encryption, incident response, certifications, and subcontractors.

### Patch Validation Checklist
A repeatable checklist used during monthly patch cycles to verify patch deployment, reboots, service health checks, rescans, and exceptions.

---

## Purpose

These SOPs and templates support organizations in improving consistency across recurring security operations. They help teams operationalize security practices by providing:

- Standardized, repeatable workflows  
- Clear documentation for governance and audit readiness  
- Guidance for IAM, vulnerability management, vendor evaluation, and incident handling  
- Tools for collecting, validating, and organizing audit evidence  
- Operationally mature logging and monitoring processes  

All SOPs and templates are generic and safe for public use.

---

## Roadmap

### Near-Term Additions
- Expand Logging and Monitoring SOP with alerting examples  
- Add Change Management SOP  
- Add Risk Acceptance Workflow SOP  
- Add Data Classification and Handling SOP  
- Add additional templates for evidence review and escalation workflows  

### Enhancements to Existing SOPs
- Add validation checklists to the Access Review SOP  
- Expand decision matrix in the Incident Triage SOP  
- Add remediation SLA guidance to the Vulnerability Management SOP  
- Expand Vendor Onboarding risk evaluation and authentication model review  

### Long-Term Goals
- Add mapping tables across CIS Controls, NIST CSF, and NIST 800-53 for all SOPs  
- Introduce automation examples for evidence collection and IAM reviews  
- Create templates for escalations, approvals, and communication during incidents  
- Add supplementary diagrams or flowcharts for key workflows  

---

## Contact

Questions, suggestions, or contributions can be submitted through GitHub issues.
