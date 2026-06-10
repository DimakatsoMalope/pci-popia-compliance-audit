# PCI-DSS v4.0 & POPIA Compliance Audit Simulation

## Overview

This project simulates a professional compliance assessment conducted for a fictional South African e-commerce company, SecureShop SA.

The objective was to evaluate compliance against:

* PCI-DSS v4.0
* POPIA (Protection of Personal Information Act)

The assessment included:

* Data flow mapping
* Asset inventory development
* PCI-DSS control assessment
* POPIA compliance review
* Identity and Access Management (IAM) assessment
* Risk assessment and risk register creation
* Evidence collection
* Formal audit reporting
* Remediation roadmap development

---

## Project Architecture

[INSERT SCREENSHOT #1 – Architecture Diagram Here]

Recommended File:

data-flow/Architecture-Diagram.png

This diagram illustrates the flow of customer, payment, and support data through the SecureShop SA environment, including Azure infrastructure, Microsoft Entra ID, Azure SQL Database, Key Vault, Microsoft Sentinel, and supporting security controls.

---

## Audit Scope

The assessment covered:

* Microsoft Azure
* Microsoft Entra ID
* Azure SQL Database
* Azure Storage Accounts
* Azure Key Vault
* Microsoft Sentinel
* Customer Support Portal
* Administrative Portal
* E-Commerce Platform

### Frameworks Assessed

* PCI-DSS v4.0
* POPIA

---

## Data Flow Analysis

[INSERT SCREENSHOT #2 – Data Flow Register Here]

Recommended File:

screenshots/data-flow-register.png

Key outcomes:

* Identified regulated payment card data flows.
* Classified personal information according to POPIA.
* Identified systems processing sensitive information.
* Defined PCI-DSS scope boundaries.

---

## Asset Inventory

[INSERT SCREENSHOT #3 – Asset Inventory Here]

Recommended File:

screenshots/asset-inventory.png

The asset inventory established ownership, classification, and criticality ratings for all in-scope systems and information assets.

---

## Identity & Access Management Review

[INSERT SCREENSHOT #4 – Entra ID Roles & Administrators]

Recommended Screenshot:

Entra ID → Roles and Administrators

Evidence Demonstrated:

* Privileged account inventory
* Role assignment review
* Least privilege assessment

---

[INSERT SCREENSHOT #5 – Conditional Access Policies]

Recommended Screenshot:

Entra ID → Protection → Conditional Access

Evidence Demonstrated:

* MFA enforcement
* Administrative access controls
* Authentication protection measures

---

## PCI-DSS Control Assessment

The environment was assessed against selected PCI-DSS v4.0 requirements.

### Key Areas Reviewed

* Network Security Controls
* Encryption Controls
* Authentication Controls
* Access Management
* Logging and Monitoring
* Security Testing

[INSERT SCREENSHOT #6 – Azure Key Vault]

Evidence Demonstrated:

* Encryption key protection
* Secrets management
* PCI-DSS Requirement 3

---

[INSERT SCREENSHOT #7 – Azure SQL TDE]

Evidence Demonstrated:

* Encryption at rest
* Protection of cardholder-related information

---

## Security Monitoring

[INSERT SCREENSHOT #8 – Microsoft Sentinel Dashboard]

Evidence Demonstrated:

* Centralized monitoring
* SIEM functionality
* Security event visibility

---

[INSERT SCREENSHOT #9 – Log Analytics Workspace]

Evidence Demonstrated:

* Log retention
* Audit trail generation
* Compliance monitoring

---

## POPIA Assessment

The assessment evaluated compliance against the following POPIA principles:

* Accountability
* Processing Limitation
* Purpose Specification
* Information Quality
* Openness
* Security Safeguards
* Data Subject Participation

Key findings identified opportunities to improve:

* Data retention governance
* DSAR procedures
* Privacy governance documentation

---

## Risk Assessment

A formal risk assessment identified technical and compliance risks affecting the organization.

### Example Risks

| Risk ID | Risk                             | Rating   |
| ------- | -------------------------------- | -------- |
| R001    | Administrator Account Compromise | Critical |
| R002    | Customer Data Exposure           | Critical |
| R003    | Missing Retention Policy         | High     |
| R004    | Excessive Privileged Access      | High     |

[INSERT SCREENSHOT #10 – Risk Register]

Recommended File:

risk-register/Risk-Register.xlsx

---

## Compliance Results

| Framework    | Compliance Score |
| ------------ | ---------------- |
| PCI-DSS v4.0 | 82%              |
| POPIA        | 78%              |

### Major Findings

* Excessive privileged access
* Missing formal retention schedule
* Incomplete DSAR process
* Vendor governance gaps

---

## Remediation Roadmap

The remediation roadmap prioritizes findings according to risk and business impact.

### Immediate Actions

* Review privileged accounts
* Conduct access reviews
* Remove dormant accounts

### Short-Term Actions

* Implement retention policy
* Formalize DSAR procedures
* Review RBAC permissions

### Long-Term Actions

* Establish privacy governance framework
* Mature vendor risk management
* Improve data classification controls

---

## Repository Structure

pci-popia-compliance-audit/

├── audit-report/

├── control-mapping/

├── data-flow/

├── risk-register/

├── remediation-plan/

├── evidence/

│ ├── screenshots/

│ ├── exports/

│ └── policies/

├── docs/

└── README.md

---

## Skills Demonstrated

* PCI-DSS v4.0 Compliance
* POPIA Compliance
* Governance, Risk & Compliance (GRC)
* Information Security Auditing
* Identity & Access Management
* Data Classification
* Risk Assessment
* Control Testing
* Security Monitoring
* Microsoft Sentinel
* Microsoft Entra ID
* Azure Security Controls
* Audit Reporting
* Remediation Planning

---

## Disclaimer

This project is a simulated compliance engagement created for educational and portfolio purposes. No production systems, real customer information, or live payment card data were used during the assessment.

