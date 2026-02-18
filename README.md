# ISO/IEC 27001:2022 Asset Register – Financial Services SME Simulation

## Project Overview

This project simulates the development of a structured Asset Register for a UK-based financial services SME preparing for ISO/IEC 27001:2022 implementation.

The objective was to formally identify, classify, and assign ownership to organisational information assets to improve governance, accountability, and risk visibility.

The register supports Annex A.5 and A.8 controls relating to asset inventory, ownership, classification, and acceptable use.

---

## Organisation Profile (Simulated)

- Sector: Financial Services (UK)
- Employees: 75
- Infrastructure:
  - Microsoft 365
  - Azure Cloud
  - On-premise file server
  - CRM platform
  - Financial reporting system

---

## Objectives

- Establish a formal asset inventory
- Assign accountable asset owners
- Implement information classification levels
- Identify asset criticality
- Support future risk assessments

---

## Classification Levels Used

Public  
Internal  
Confidential  
Highly Confidential  

---

## Total Assets Documented: 15

This register includes critical information, infrastructure, application, and security assets within ISMS scope.

# Information Classification Framework

Classification Levels:

Public – Approved for public release.
Internal – Non-public operational information.
Confidential – Sensitive business information.
Highly Confidential – Regulated or financially sensitive data requiring strict protection.

Handling Requirements:

- Confidential and Highly Confidential data must be encrypted.
- Access must follow least privilege principles.
- Access reviews conducted quarterly.
- Logs must be retained and monitored.

# Asset Register

| Asset ID | Asset Name | Asset Type | Owner | Department | Classification | Criticality | Location | Backup Status |
|----------|------------|------------|--------|------------|----------------|------------|----------|---------------|
| A001 | Customer Financial Database | Database | IT Manager | IT | Highly Confidential | High | Azure | Daily |
| A002 | CRM Application | Application | Operations Manager | Operations | Confidential | High | Azure | Daily |
| A003 | Microsoft 365 Tenant | Cloud Service | IT Manager | IT | Confidential | High | Cloud | Managed by CSP |
| A004 | Employee HR Records | Database | HR Manager | HR | Confidential | Medium | On-Prem | Weekly |
| A005 | Financial Reporting System | Application | Finance Manager | Finance | Highly Confidential | High | Cloud | Daily |
| A006 | Azure Virtual Machines | Infrastructure | IT Manager | IT | Confidential | High | Azure | Daily |
| A007 | Corporate Laptops | Endpoint Devices | IT Manager | IT | Internal | Medium | Office | Encrypted |
| A008 | Network Firewall | Infrastructure | IT Manager | IT | Confidential | High | Server Room | Config Backup |
| A009 | Active Directory | Identity Service | IT Manager | IT | Highly Confidential | High | On-Prem | Daily |
| A010 | Email Exchange Online | Cloud Service | IT Manager | IT | Confidential | High | Cloud | Managed |
| A011 | Backup Storage Repository | Storage | IT Manager | IT | Highly Confidential | High | Cloud | Daily |
| A012 | SharePoint Online | Collaboration Tool | IT Manager | IT | Confidential | Medium | Cloud | Managed |
| A013 | VPN Gateway | Network Security | IT Manager | IT | Confidential | High | Server Room | Config Backup |
| A014 | Endpoint Protection Platform | Security Tool | IT Manager | IT | Internal | Medium | Cloud | Managed |
| A015 | Corporate Website | Web Application | Marketing Lead | Marketing | Public | Low | Azure | Daily |

Total Assets Documented: 15

# Asset Governance Observations

1. Prior to this exercise, no formally documented asset register existed.
2. Asset ownership roles were informal and undocumented.
3. Classification levels were inconsistently applied.
4. Backup validation procedures were not formally tested.

Risk Implications:

- Reduced accountability
- Incomplete risk visibility
- Increased regulatory exposure
- Weak audit readiness

# ISO 27001:2022 Annex A Control Alignment

A.5.9 – Inventory of Information and Other Associated Assets  
Status: Now Implemented  
Evidence: Formal Asset Register created.

A.5.10 – Acceptable Use of Information  
Status: Partially Implemented  
Gap: Staff acknowledgement process required.

A.5.12 – Classification of Information  
Status: Implemented  
Evidence: Documented classification scheme.

A.8.1 – User Endpoint Devices  
Status: Partially Implemented  
Gap: Central monitoring enhancement required.

# Executive Summary

The implementation of a formal Asset Register significantly improves governance maturity and accountability within the organisation.

15 critical assets have been formally identified, classified, and assigned ownership.

High-value systems such as the Customer Financial Database, Active Directory, and Azure infrastructure are now clearly documented and prioritised for enhanced protection.

This asset register forms the foundation for structured risk assessment and ISO 27001 compliance readiness.

Overall Governance Maturity: Improving





