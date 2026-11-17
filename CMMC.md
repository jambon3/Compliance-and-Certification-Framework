# CMMC – Cybersecurity Maturity Model Certification

## 1. What is CMMC?

**CMMC (Cybersecurity Maturity Model Certification)** is a U.S. Department of Defense (DoD) cybersecurity certification program.

It requires companies working on certain U.S. military and defense contracts, including subcontractors, to demonstrate that they adequately protect sensitive government information.

The purpose of CMMC is to strengthen cybersecurity across the Defense Industrial Base (DIB).

Organizations must meet the cybersecurity requirements associated with the information they handle and the CMMC level specified in their contracts.

---

## 2. What Does CMMC Protect?

CMMC focuses primarily on two types of government information:

| Information | Full Name | Meaning |
|---|---|---|
| FCI | Federal Contract Information | Non-public information provided by or generated for the government under a contract. |
| CUI | Controlled Unclassified Information | Sensitive government information that is not classified but requires protection under applicable laws, regulations, or government policies. |

### Examples of information that may require protection

- Technical drawings and engineering documents.
- Military equipment specifications.
- Defense project documentation.
- Sensitive contract information.
- Certain technical or operational data.
**Important:** CUI is not classified information. However, it must be protected according to applicable government security requirements.

---

## 3. The Three CMMC Levels

CMMC has three levels based on the sensitivity of the information an organization handles.

### Level 1 – Basic Safeguarding of FCI

Purpose: Protect Federal Contract Information.

Requirements:

- 15 basic security requirements.
- Annual self-assessment.
- Annual affirmation of compliance.
- Based on FAR 52.204-21.

### Level 2 – Protection of CUI

Purpose: Protect Controlled Unclassified Information.

Requirements:

- 110 security requirements.
- Based on NIST SP 800-171 Revision 2 under the current CMMC framework.
- Self-assessment or independent third-party assessment, depending on the contract.
- Annual affirmation of compliance.

### Level 3 – Advanced Protection of Critical CUI

Purpose: Provide enhanced protection against advanced cybersecurity threats.

Requirements:

- Includes the 110 Level 2 security requirements.
- Includes 24 additional requirements from NIST SP 800-172.
- Government-led assessment by the Defense Industrial Base Cybersecurity Assessment Center (DIBCAC).

### CMMC Levels – Summary

| Level | Information Protected | Assessment |
|---|---|---|
| Level 1 | FCI | Annual self-assessment |
| Level 2 | CUI | Self-assessment or third-party assessment |
| Level 3 | Critical CUI | Government-led assessment |

**Important distinction:**

- NIST SP 800-171 defines cybersecurity requirements for protecting CUI.
- CMMC is the DoD program used to assess and verify whether defense contractors meet the applicable cybersecurity requirements.

---

## 4. CMMC and NIST SP 800-171

One of the most important standards to understand when studying CMMC is **NIST SP 800-171**.

NIST SP 800-171 Revision 2 contains 110 security requirements organized into 14 security families.

These families cover different areas of information security.

### The 14 NIST SP 800-171 Security Families

| # | Security Family | What It Covers |
|---|---|---|
| 1 | Access Control (AC) | Controlling who can access systems and information. |
| 2 | Awareness and Training (AT) | Security awareness and employee training. |
| 3 | Audit and Accountability (AU) | Logging, monitoring and tracking system activity. |
| 4 | Configuration Management (CM) | Maintaining secure system configurations. |
| 5 | Identification and Authentication (IA) | MFA, passwords and identity verification. |
| 6 | Incident Response (IR) | Detecting, reporting and responding to security incidents. |
| 7 | Maintenance (MA) | Secure system maintenance. |
| 8 | Media Protection (MP) | Protecting removable media and stored information. |
| 9 | Personnel Security (PS) | Managing personnel-related security risks. |
| 10 | Physical Protection (PE) | Controlling physical access to facilities and equipment. |
| 11 | Risk Assessment (RA) | Identifying and evaluating cybersecurity risks. |
| 12 | Security Assessment (CA) | Assessing security controls and documenting compliance. |
| 13 | System and Communications Protection (SC) | Network security, encryption and secure communications. |
| 14 | System and Information Integrity (SI) | Malware protection, vulnerability management and system integrity. |

---

## 5. How CMMC Relates to Real IT Administration

CMMC requirements are directly connected to everyday IT administration and cybersecurity responsibilities.

The following examples show how common enterprise technologies can support security requirements.

| IT Responsibility / Technology | Related Security Family | Example |
|---|---|---|
| Active Directory / Entra ID | AC, IA | User access, authentication and permissions. |
| Multi-Factor Authentication (MFA) | IA | Requiring additional identity verification. |
| Microsoft Intune | CM, AC | Device configuration and security policies. |
| Microsoft Defender | SI | Malware detection and endpoint protection. |
| Windows Updates | SI, CM | Vulnerability remediation and secure configurations. |
| BitLocker | MP, SC | Encrypting data stored on company devices. |
| Microsoft Purview | MP, SC | Information protection and data handling. |
| Microsoft 365 Audit Logs | AU | Recording and reviewing user activity. |
| Firewall / Cisco Meraki | SC | Network protection and traffic filtering. |
| Employee Onboarding / Offboarding | AC, PS | Granting and revoking employee access. |
| Backup and Recovery | Contingency Planning, SC | Supporting data availability and recovery. |
| Security Incident Procedures | IR | Documenting, investigating and responding to incidents. |

**Note:** These technologies can help implement security controls, but simply deploying a product does not automatically satisfy a CMMC requirement. Organizations must implement the appropriate processes, configurations and documentation and maintain evidence that the controls are effective.

---

## 6. Practical Example: Employee Offboarding

Consider an employee leaving a company that handles sensitive government information.

A proper IT offboarding process should include:

1. Disable the employee's Active Directory and Entra ID accounts.
2. Revoke active authentication sessions.
3. Remove access to Microsoft 365, SharePoint, Teams and other company resources.
4. Recover company-owned equipment.
5. Preserve relevant audit logs and records.
6. Document the offboarding process.
7. Verify that access has been removed.

This process supports several security objectives:

- Access Control (AC)
- Identification and Authentication (IA)
- Audit and Accountability (AU)
- Personnel Security (PS)

This is an example of how normal IT administration contributes to cybersecurity compliance.

---

## 7. Important Current Development – November 2026

According to the July 13, 2026 DoD announcement, CMMC Phase 2 implementation requirements originally scheduled for November 10, 2026 were suspended pending a review.

Phase 1 self-assessment requirements remain in place.

However, the underlying obligation to protect FCI and CUI under applicable contract requirements has not disappeared.

Organizations should always verify:

- The latest DoD CMMC implementation guidance.
- Applicable contract clauses.
- Required assessment levels.
- Current assessment and affirmation requirements.

**Important:** Verify the latest official DoD announcements before using this section for compliance decisions.

---

## 8. Official Documentation and Study Resources

The following official resources are useful when learning about CMMC and its underlying security requirements.

1. [DoD CMMC Official Website](https://dodcio.defense.gov/CMMC/) – Program information and implementation updates.
2. [CMMC Assessment Guides and Resources](https://dodcio.defense.gov/CMMC/Documentation/) – Official assessment documentation.
3. [CMMC Frequently Asked Questions](https://dodcio.defense.gov/CMMC/FAQs/) – Common questions about the program.
4. [32 CFR Part 170](https://www.ecfr.gov/current/title-32/subtitle-A/chapter-I/subchapter-D/part-170) – CMMC program regulations.
5. [NIST SP 800-171](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final) – Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations.
6. [NIST SP 800-172](https://csrc.nist.gov/pubs/sp/800/172/final) – Enhanced Security Requirements for Protecting CUI.
7. [FAR 52.204-21](https://www.acquisition.gov/far/52.204-21) – Basic Safeguarding of Covered Contractor Information Systems.
