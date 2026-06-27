<div align="center">

# 🛡️ Real-Time GRC System Design & Implementation using Eramba

### Governance, Risk & Compliance (GRC) Project

Eramba • Risk Management • Compliance Analysis • GDPR • Incident Management

![Eramba](https://img.shields.io/badge/Eramba-GRC-blue)
![NIST CSF](https://img.shields.io/badge/NIST-CSF%202.0-green)
![GDPR](https://img.shields.io/badge/GDPR-Compliance-orange)
![Risk Management](https://img.shields.io/badge/Risk-Management-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</div>

---

# Overview

This project demonstrates the design and implementation of a centralized Governance, Risk, and Compliance (GRC) environment using the Eramba platform.

The project was developed for a healthcare organization (St Thomas' Hospital) to manage cybersecurity risks, compliance obligations, privacy requirements, internal controls, and incident management activities.

The implementation follows industry best practices and aligns with NIST Cybersecurity Framework (CSF) 2.0 and UK GDPR requirements to improve organizational governance, risk visibility, regulatory compliance, and security resilience.

---

# Organization Profile

## Organization

**St Thomas' Hospital**

## Industry

Healthcare / Hospital Sector

## Business Objectives

- Protect patient health records
- Maintain regulatory compliance
- Reduce cybersecurity risks
- Improve governance processes
- Strengthen incident response capabilities
- Ensure data privacy and accountability

---

# Technologies Used

## GRC Platform

- Eramba 3.27.3

## Compliance Frameworks

- NIST Cybersecurity Framework (CSF) 2.0
- UK GDPR
- ICO Data Protection Guidance

## Risk Management

- Asset-Based Risk Assessment
- Risk Appetite Matrix
- Risk Treatment Planning

## Privacy Management

- GDPR Data Asset Management
- Processing Activities
- Third-Party Management
- Data Flow Mapping

## Incident Management

- Security Incident Tracking
- Incident Lifecycle Management
- Lessons Learned Process

---

# Project Architecture

![Project Architecture](images/grc-architecture.png)

---

# GRC Implementation Overview

```text
Business Units
      │
      ▼
Assets
      │
      ▼
Risks
      │
      ▼
Policies & Controls
      │
      ▼
Compliance Requirements
      │
      ▼
Privacy Management
      │
      ▼
Incident Management
      │
      ▼
Dashboard Reporting
```

---

# Task 1 – Organization Setup

## Business Units

Three business units were created within Eramba:

- Clinical Operations
- Information Technology
- HR & Finance

![Business Units](images/business-units.png)

---

## Assets

Five organizational assets were identified and classified.

Examples:

- Patient Health Records Database
- Payroll Management System
- CCTV Monitoring System
- Hospital Network Infrastructure
- Patient Appointment System

![Assets](images/assets-list.png)

---

# Task 2 – Risk Management

## Risk Register

Five asset-based cybersecurity risks were identified and assessed.

Examples:

- Unauthorized Patient Record Access
- Firewall Misconfiguration
- Payroll Fraud
- Loss of CCTV Footage
- Ransomware Attack

![Risk Register](images/risk-register.png)

---

## Risk Appetite Matrix

Likelihood and impact values were configured to prioritize organizational risks.

![Risk Matrix](images/risk-matrix.png)

---

## Risk Treatment Plans

Treatment plans were created for high-priority risks.

![Risk Treatment Plan](images/risk-treatment-plan.png)

---

# Task 3 – Policy Management

## Policies

Four security policies were implemented:

- Access Control Policy
- Information Security Policy
- Backup & Recovery Policy
- Incident Response Policy

![Policies](images/policies.png)

---

## Policy Reviews & Versions

Policy version history and review cycles were documented.

![Policy Versions](images/policy-versions.png)

---

# Task 4 – Internal Controls

## Internal Controls

Implemented controls include:

- Role-Based Access Control
- Firewall Rule Review
- Daily Backup Verification
- CCTV Monitoring Review

![Controls](images/internal-controls.png)

---

## Audit Records

Control effectiveness was validated through audit activities.

![Control Audits](images/control-audits.png)

---

## Maintenance Records

Control maintenance schedules were documented.

![Maintenance Records](images/maintenance-records.png)

---

# Task 5 – Compliance Analysis

## NIST CSF 2.0 Mapping

Compliance requirements were mapped against NIST CSF 2.0.

![NIST Compliance](images/nist-compliance.png)

---

## UK GDPR Compliance

Privacy and data protection requirements were assessed against UK GDPR guidance.

![GDPR Compliance](images/gdpr-compliance.png)

---

# Task 6 – Data Privacy Management

## Privacy-Focused Data Assets

Three GDPR-sensitive data assets were created:

- Patient Health Records Database
- Patient Appointment Records
- Employee Records Database

![Data Assets](images/data-assets.png)

---

## Processing Activities

GDPR processing activities were documented.

![Processing Activities](images/processing-activities.png)

---

## Third Parties

Third-party organizations involved in data processing were registered.

Examples:

- Payroll Service Provider
- Cloud Backup Provider
- SMS Notification Provider

![Third Parties](images/third-parties.png)

---

## Data Flows

Personal data movement between systems and third parties was documented.

![Data Flows](images/data-flows.png)

---

# Task 7 – Incident Management

## Security Incidents

Four security incidents were created and tracked.

Examples:

- Unauthorized Patient Record Access
- Firewall Rule Misconfiguration
- Payroll Approval Failure
- CCTV Footage Loss

![Incident Register](images/incident-register.png)

---

## Incident Lifecycle

Each incident followed:

```text
Identification
      │
      ▼
Containment
      │
      ▼
Eradication
      │
      ▼
Recovery
      │
      ▼
Communication
      │
      ▼
Lessons Learned
```

![Incident Lifecycle](images/incident-lifecycle.png)

---

# Task 8 – Dashboard & Reporting

## Asset-Based Risk Matrix

Visual representation of organizational risks.

![Dashboard Risk Matrix](images/dashboard-risk-matrix.png)

---

## Compliance Status Dashboard

Overview of compliance posture across frameworks.

![Compliance Dashboard](images/compliance-dashboard.png)

---

# Key Findings

| Finding | Severity |
|----------|----------|
| Unauthorized Patient Record Access | Critical |
| Missing ICO Breach Notification Procedure | High |
| Firewall Misconfiguration | High |
| Payroll Approval Workflow Failure | Medium |
| CCTV Monitoring Control Failure | Medium |

---

# Skills Demonstrated

## Governance

- Governance Framework Design
- Risk Governance
- Compliance Management

## Risk Management

- Asset-Based Risk Assessment
- Risk Analysis
- Risk Treatment Planning

## Compliance

- NIST CSF 2.0 Mapping
- UK GDPR Compliance
- Regulatory Gap Analysis

## Privacy

- GDPR Data Mapping
- Processing Activities
- Third-Party Management
- Data Flow Analysis

## Incident Management

- Incident Lifecycle Management
- Incident Documentation
- Root Cause Analysis

## GRC Platform

- Eramba Administration
- Dashboard Configuration
- Reporting & Auditing

---

# Repository Structure

```text
it8515-eramba-grc-project
│
├── README.md
│
├── images
│   ├── grc-architecture.png
│   ├── business-units.png
│   ├── assets-list.png
│   ├── risk-register.png
│   ├── risk-matrix.png
│   ├── risk-treatment-plan.png
│   ├── policies.png
│   ├── policy-versions.png
│   ├── internal-controls.png
│   ├── control-audits.png
│   ├── maintenance-records.png
│   ├── nist-compliance.png
│   ├── gdpr-compliance.png
│   ├── data-assets.png
│   ├── processing-activities.png
│   ├── third-parties.png
│   ├── data-flows.png
│   ├── incident-register.png
│   ├── incident-lifecycle.png
│   ├── dashboard-risk-matrix.png
│   └── compliance-dashboard.png
```

---

# Key Frameworks

- NIST Cybersecurity Framework (CSF) 2.0
- UK GDPR
- ICO Data Protection Guidance
- Enterprise Risk Management Principles

---
