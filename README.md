<div align="center"> .

# 🛡️ Real-Time GRC System Design & Implementation using Eramba

### Governance, Risk & Compliance (GRC) Project

Eramba • Risk Management • Compliance Analysis • UK GDPR • Incident Management

![Eramba](https://img.shields.io/badge/Eramba-GRC-blue)
![NIST](https://img.shields.io/badge/NIST-CSF%202.0-green)
![GDPR](https://img.shields.io/badge/UK-GDPR-orange)
![Risk](https://img.shields.io/badge/Risk-Management-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</div>

---

# Overview

This project demonstrates the implementation of a Governance, Risk, and Compliance (GRC) environment using Eramba.

The project was developed for a healthcare organization, St Thomas' Hospital, to manage cybersecurity risks, regulatory compliance requirements, privacy obligations, and incident management activities.

The implementation aligns with NIST Cybersecurity Framework (CSF) 2.0 and UK GDPR requirements while providing centralized visibility of assets, risks, controls, compliance status, privacy records, and security incidents.

---

# Organization Profile

| Item | Description |
|--------|-------------|
| Organization | St Thomas' Hospital |
| Industry | Healthcare |
| Frameworks | NIST CSF 2.0, UK GDPR |
| Platform | Eramba 3.27.3 |
| Focus Areas | Risk, Compliance, Privacy, Incident Management |

---

# Technologies Used

## Governance, Risk & Compliance

- Eramba

## Compliance Frameworks

- NIST CSF 2.0
- UK GDPR
- ICO Data Protection Guidance

## Risk Management

- Asset-Based Risk Assessment
- Risk Appetite Matrix
- Risk Treatment Planning

## Privacy Management

- Data Assets
- Processing Activities
- Third Parties
- Data Flow Mapping

## Incident Management

- Security Incident Tracking
- Incident Lifecycle Management
- Lessons Learned Process

---

# GRC Architecture

```text
┌────────────────────────────────────┐
│        St Thomas' Hospital         │
└─────────────────┬──────────────────┘
                  │
                  ▼
          Business Units
                  │
                  ▼
               Assets
                  │
                  ▼
                Risks
                  │
                  ▼
      Policies & Internal Controls
                  │
                  ▼
      Compliance Frameworks
       (NIST CSF 2.0 / GDPR)
                  │
                  ▼
         Privacy Management
                  │
                  ▼
        Incident Management
                  │
                  ▼
      Dashboard & Reporting
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

- Patient Health Records Database
- Payroll Management System
- CCTV Monitoring System
- Hospital Network Infrastructure
- Patient Appointment System

![Assets](images/assets-list.png)

---

# Task 2 – Risk Management

## Risk Register and Treatment Plans

Five cybersecurity risks were identified and linked to organizational assets.

Examples include:

- Unauthorized Patient Record Access
- Firewall Misconfiguration
- Payroll Fraud
- CCTV Monitoring Failure
- Ransomware Attack

The identified high-priority risks were evaluated using the organization's risk methodology and assigned treatment plans to reduce their likelihood and impact. Treatment activities included implementing access controls, strengthening firewall management procedures, improving backup verification processes, and enhancing monitoring capabilities.

### Risk Register

![Risk Register](images/risk-register.png)

---

# Task 3 – Policy Management

## Security Policies

Four organizational policies were implemented:

- Information Security Policy
- Access Control Policy
- Backup & Recovery Policy
- Incident Response Policy

![Policies](images/policies.png)

---

# Task 4 – Internal Controls

## Security Controls

Controls were implemented to mitigate identified risks and improve compliance.

Examples:

- Role-Based Access Control
- Firewall Reviews
- Backup Verification
- CCTV Monitoring Reviews

![Internal Controls](images/internal-controls.png)

---

# Task 5 – Compliance Analysis

## Compliance Frameworks

The organization's controls and policies were mapped against regulatory and security requirements.

Frameworks used:

- NIST Cybersecurity Framework (CSF) 2.0
- UK GDPR

![Compliance Frameworks](images/nist-compliance.png)

---

# Task 6 – Data Privacy Management

## Privacy-Focused Data Assets

Privacy-sensitive assets containing personal information were identified and managed within Eramba.

Examples:

- Patient Health Records
- Appointment Records
- Employee Records

![Privacy Assets](images/data-assets.png)

---

## Third-Party Management

External organizations involved in data processing were documented and assessed.

Examples:

- Payroll Provider
- Cloud Backup Provider
- SMS Notification Service

![Third Parties](images/third-parties.png)

---

## Data Flow Mapping

Data flows were documented to track how personal information moves between systems and third parties.

![Data Flows](images/data-flows.png)

---

# Task 7 – Incident Management

## Security Incidents

Security incidents were created and tracked through the incident management process.

Examples:

- Unauthorized Patient Record Access
- Firewall Misconfiguration
- Payroll Approval Failure
- CCTV Footage Loss

![Incident Register](images/incident-register.png)

---

# Task 8 – Dashboard & Reporting

## Risk Matrix and Compliance Dashboard

The dashboard provides centralized visibility of:

- Risk Exposure
- Compliance Status
- Treatment Progress
- Organizational Security Posture

![Dashboard](images/dashboard-risk-matrix.png)

---

# Key Results

| Capability | Status |
|------------|---------|
| Business Units | ✅ |
| Asset Management | ✅ |
| Risk Register | ✅ |
| Risk Treatment Plans | ✅ |
| Policy Management | ✅ |
| Internal Controls | ✅ |
| NIST CSF 2.0 Compliance | ✅ |
| UK GDPR Compliance | ✅ |
| Privacy Management | ✅ |
| Third-Party Management | ✅ |
| Incident Management | ✅ |
| Dashboard Reporting | ✅ |

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
- Gap Analysis

## Privacy

- Data Flow Mapping
- Processing Activities
- Third-Party Risk Management

## Incident Management

- Incident Lifecycle Management
- Root Cause Analysis
- Security Reporting

## GRC Platform Administration

- Eramba Configuration
- Dashboard Configuration
- Compliance Tracking

---

# Repository Structure

```text
it8515-eramba-grc-project
│
├── README.md
│
└── images
    ├── business-units.png
    ├── assets-list.png
    ├── risk-register.png
    ├── risk-treatment-plan.png
    ├── policies.png
    ├── internal-controls.png
    ├── nist-compliance.png
    ├── data-assets.png
    ├── third-parties.png
    ├── data-flows.png
    ├── incident-register.png
    └── dashboard-risk-matrix.png
```
