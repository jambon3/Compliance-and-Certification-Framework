# CMMC Level 2

## 1. What Is CMMC Level 2?

CMMC Level 2 focuses on protecting **Controlled Unclassified Information (CUI)** handled by organizations working on U.S. Department of Defense (DoD) contracts.

It is designed to ensure that defense contractors and subcontractors have appropriate cybersecurity controls to protect sensitive government information.

### Main requirements

- 110 security requirements.
- Based on NIST SP 800-171 Revision 2.
- Documented security policies and procedures.
- A System Security Plan (SSP).
- Evidence demonstrating that security controls are implemented.
- Security assessments.
- Annual affirmation of continued compliance.

**Important:** Level 2 is not simply about purchasing security software. Organizations must demonstrate that their security controls are properly implemented and maintained.

---

## 2. Understanding the 110 Security Requirements

The 110 requirements are divided into 14 security families.

| # | Family | Requirements | Main objective |
|---|---|---:|---|
| 1 | Access Control (AC) | 22 | Control access to systems and information. |
| 2 | Awareness and Training (AT) | 3 | Train employees to recognize security risks. |
| 3 | Audit and Accountability (AU) | 9 | Record and monitor system activities. |
| 4 | Configuration Management (CM) | 9 | Maintain secure system configurations. |
| 5 | Identification and Authentication (IA) | 11 | Verify user and device identities. |
| 6 | Incident Response (IR) | 3 | Detect and respond to security incidents. |
| 7 | Maintenance (MA) | 6 | Perform secure system maintenance. |
| 8 | Media Protection (MP) | 9 | Protect information stored on media. |
| 9 | Personnel Security (PS) | 2 | Manage personnel security risks. |
| 10 | Physical Protection (PE) | 6 | Protect facilities and physical equipment. |
| 11 | Risk Assessment (RA) | 3 | Identify and evaluate security risks. |
| 12 | Security Assessment (CA) | 4 | Evaluate and monitor security controls. |
| 13 | System and Communications Protection (SC) | 16 | Protect networks and communications. |
| 14 | System and Information Integrity (SI) | 7 | Protect systems against malware and vulnerabilities. |
| | **Total** | **110** | |

---

## 3. The 14 Security Families Explained

### 3.1 Access Control (AC)

**Objective:** Ensure only authorized users can access company systems and sensitive information.

Examples:

- Create individual user accounts.
- Apply role-based access control (RBAC).
- Restrict access based on job responsibilities.
- Remove access when employees leave.
- Limit administrative privileges.
- Control remote access.
- Restrict access to sensitive files and folders.

### 3.2 Awareness and Training (AT)

**Objective:** Ensure employees understand cybersecurity responsibilities.

Examples:

- Annual cybersecurity training.
- Phishing awareness campaigns.
- Training on handling CUI.
- Reporting suspicious emails.
- Security procedures for employees.

### 3.3 Audit and Accountability (AU)

**Objective:** Record system activities so organizations can identify suspicious behavior and investigate incidents.

Examples:

- Record user login activities.
- Monitor administrative changes.
- Track access to sensitive information.
- Protect audit logs against unauthorized modification.
- Review security events.
- Establish log retention requirements.

### 3.4 Configuration Management (CM)

**Objective:** Ensure systems are configured securely and remain under control.

Examples:

- Establish secure configuration baselines.
- Document approved software.
- Disable unnecessary services.
- Control configuration changes.
- Maintain hardware and software inventories.
- Restrict unauthorized software installations.

### 3.5 Identification and Authentication (IA)

**Objective:** Verify the identity of users, devices and processes before allowing access.

Examples:

- Unique user accounts.
- Multi-factor authentication (MFA).
- Strong authentication procedures.
- Password protection.
- Authentication for privileged accounts.
- Device identification.

### 3.6 Incident Response (IR)

**Objective:** Establish procedures to detect, report, investigate and respond to cybersecurity incidents.

Examples:

- Document incident response procedures.
- Identify security incidents.
- Report incidents to appropriate personnel.
- Contain compromised systems.
- Investigate security events.
- Document lessons learned.

### 3.7 Maintenance (MA)

**Objective:** Ensure maintenance activities do not introduce security risks.

Examples:

- Restrict maintenance access.
- Use authorized maintenance personnel.
- Monitor remote maintenance sessions.
- Control maintenance tools.
- Document maintenance activities.


### 3.8 Media Protection (MP)

**Objective:** Protect information stored on physical and digital media.

Examples:

- Encrypt company laptops.
- Restrict USB storage devices.
- Control removable media.
- Sanitize storage devices before disposal.
- Protect backup media.
- Control access to stored information.


### 3.9 Personnel Security (PS)

**Objective:** Manage security risks associated with employees and other personnel.

Examples:

- Screen personnel as required.
- Control access during employee transfers.
- Revoke access when employment ends.
- Establish personnel security procedures.


### 3.10 Physical Protection (PE)

**Objective:** Prevent unauthorized physical access to facilities, equipment and systems.

Examples:

- Secure server rooms.
- Restrict building access.
- Monitor visitors.
- Protect network equipment.
- Maintain physical access records.
- Control access to areas containing sensitive information.

### 3.11 Risk Assessment (RA)

**Objective:** Identify, analyze and manage cybersecurity risks.

Examples:

- Perform vulnerability scans.
- Identify system weaknesses.
- Evaluate threats.
- Document cybersecurity risks.
- Establish remediation priorities.


### 3.12 Security Assessment (CA)

**Objective:** Evaluate whether security controls are properly implemented and effective.

Examples:

- Assess security controls.
- Document assessment results.
- Correct identified deficiencies.
- Monitor security controls continuously.
- Maintain security documentation.


### 3.13 System and Communications Protection (SC)

**Objective:** Protect systems, networks and communications from unauthorized access and interception.

Examples:

- Use network segmentation.
- Encrypt communications.
- Restrict network traffic.
- Secure remote access.
- Protect system boundaries.
- Monitor network connections.



### 3.14 System and Information Integrity (SI)

**Objective:** Protect systems and information against malware, unauthorized modifications and security vulnerabilities.

Examples:

- Deploy malware protection.
- Monitor system activity.
- Install security updates.
- Identify vulnerabilities.
- Detect unauthorized changes.
- Correct system integrity problems.



---

## 4. Important CMMC Level 2 Documentation

CMMC compliance requires more than technical configurations.

Organizations must document their cybersecurity environment and demonstrate that their security controls are implemented.

Three important concepts are:

### 4.1 System Security Plan (SSP)

An SSP describes how an organization protects its systems and information.

It should document:

- System boundaries.
- Systems that process, store or transmit CUI.
- Network architecture.
- Hardware and software components.
- Security policies.
- Implemented security controls.
- Responsibilities.
- External connections.
- How security requirements are satisfied.

**Example:**

An organization uses:

- Microsoft 365.
- Windows Server.
- Active Directory.
- Microsoft Entra ID.
- Cisco Meraki.
- VMware.
- Microsoft Defender.

The SSP should describe the relevant systems, their security boundaries and how applicable controls are implemented.

### 4.2 Plan of Action and Milestones (POA&M)

A POA&M documents security deficiencies and how the organization intends to correct them.

It generally includes:

- Identified security deficiency.
- Related security requirement.
- Planned corrective action.
- Responsible person.
- Target completion date.
- Current remediation status.

**Example:**

| Item | Description |
|---|---|
| Finding | MFA is not enabled for all privileged accounts. |
| Security area | Identification and Authentication |
| Risk | Unauthorized administrative access. |
| Corrective action | Implement MFA for privileged accounts. |
| Responsible team | IT Department |
| Status | In progress |

**Important:** CMMC does not allow every deficiency to be placed on a POA&M. Only eligible requirements can be included, and applicable deadlines and scoring restrictions must be followed. For Level 2, POA&M closeout is generally required within 180 days.

### 4.3 Evidence and Documentation

Organizations must be able to demonstrate that their security controls actually work.

Examples of evidence:

- Microsoft Entra ID configuration exports.
- MFA policy configurations.
- Intune compliance policies.
- BitLocker encryption reports.
- Firewall configurations.
- Security awareness training records.
- Audit logs.
- Vulnerability scan reports.
- Incident response documentation.
- Access review records.

**Important:** A written policy alone does not prove that a security control is implemented.

For example, having an MFA policy document is not sufficient if MFA is not actually enforced.

---

## 5. Understanding CMMC Level 2 Assessment

There are two Level 2 assessment paths in the CMMC framework.

### Path A – Level 2 Self-Assessment

The organization evaluates its own security controls.

General process:

1. Define the assessment scope.
2. Review the 110 security requirements.
3. Evaluate the implementation of each requirement.
4. Collect supporting evidence.
5. Calculate the assessment score.
6. Submit the results to the Supplier Performance Risk System (SPRS).
7. Submit the required annual affirmation.

Under the current program requirements, Level 2 self-assessments are conducted every three years, with annual affirmations.

### Path B – Level 2 Certification Assessment

An authorized or accredited CMMC Third-Party Assessment Organization (C3PAO) independently evaluates the organization's security controls.

General process:

1. Prepare the organization for assessment.
2. Define the assessment scope.
3. Review the SSP and supporting documentation.
4. Examine technical configurations.
5. Interview responsible personnel.
6. Review evidence.
7. Evaluate the 110 security requirements.
8. Document findings.
9. Submit assessment results through the official CMMC process.

The certification assessment path is required when specified by the applicable contract.

**Current implementation note:** As of November 2026, the official DoD CMMC overview indicates that implementation is paused in Phase 1 and may currently require self-assessments at the applicable levels. The C3PAO assessment path remains part of the regulatory framework. Always check current DoD guidance and the contract before determining which path applies.

---

## 6. Understanding the Assessment Score

NIST SP 800-171 requirements have assigned point values under the CMMC assessment methodology.

The maximum Level 2 score is **110 points**.

An organization does not necessarily receive one point for each requirement.

Some requirements carry more points because of their security importance.

Example:

| Assessment result | Score |
|---|---:|
| Maximum score | 110 |
| Organization's score | 95 |
| Remaining difference | 15 |

A score below 110 indicates that some requirements have not been fully satisfied.

An organization may receive Conditional Level 2 status if its remaining deficiencies meet the applicable POA&M eligibility rules.

The organization must correct eligible deficiencies and complete the required closeout assessment within 180 days.

Not every missing requirement is eligible for a POA&M.

---

## 7. CUI Environment and Assessment Scope

One of the most important parts of CMMC Level 2 is defining the CUI environment.

An organization must identify which systems process, store or transmit CUI.

For example:

```text
                    Corporate Network
                           |
                     Firewall
                           |
              -------------------------
              |                       |
        General Network          CUI Environment
              |                       |
        Office Computers        Engineering Systems
        General Email           CUI File Storage
        Printers                Controlled Servers
                                Authorized Users
```

The organization must determine:

- Which users access CUI.
- Which computers process CUI.
- Which servers store CUI.
- Which networks transmit CUI.
- Which external services are involved.
- Which security controls protect the environment.

The assessment scope is critical because the organization must demonstrate that the systems within scope are adequately protected.

**Important:** Network segmentation can help isolate the CUI environment, but simply creating a separate VLAN does not automatically establish a compliant CUI boundary.

---

## 8. IT Administrator Checklist

The following checklist provides examples of work that can support CMMC Level 2 implementation.

### Identity and Access Management

- [ ] Individual accounts for users.
- [ ] MFA for applicable accounts.
- [ ] Privileged access restrictions.
- [ ] Role-based permissions.
- [ ] Account disabling procedures.
- [ ] Access reviews.
- [ ] Remote access restrictions.

### Endpoint Security

- [ ] BitLocker encryption.
- [ ] Microsoft Defender protection.
- [ ] Windows security updates.
- [ ] Intune security policies.
- [ ] Secure configuration baselines.
- [ ] Local administrator restrictions.
- [ ] Endpoint monitoring.

### Network Security

- [ ] Firewall rules documented.
- [ ] Network segmentation implemented.
- [ ] VPN access secured.
- [ ] Network traffic restricted.
- [ ] Network devices securely configured.
- [ ] External connections reviewed.

### Monitoring and Logging

- [ ] Audit logging enabled.
- [ ] Security events monitored.
- [ ] Administrative activities recorded.
- [ ] Logs protected against unauthorized changes.
- [ ] Incident procedures documented.

### Data Protection

- [ ] CUI identified and classified.
- [ ] Access to CUI restricted.
- [ ] Sensitive information encrypted where required.
- [ ] Removable media controlled.
- [ ] Backup procedures documented.
- [ ] Data disposal procedures established.

### Documentation

- [ ] System Security Plan (SSP).
- [ ] Plan of Action and Milestones (POA&M), if applicable.
- [ ] Security policies.
- [ ] Network diagrams.
- [ ] Asset inventory.
- [ ] Incident response procedures.
- [ ] Employee training records.
- [ ] Assessment evidence.

---

## 10. Official Study Resources

- [DoD CMMC Official Website](https://dodcio.defense.gov/CMMC/)
- [CMMC Level 2 Assessment Guide](https://dodcio.defense.gov/Portals/0/Documents/CMMC/AssessmentGuideL2v2.pdf)
- [CMMC Model Overview](https://dodcio.defense.gov/Portals/0/Documents/CMMC/ModelOverviewv2.pdf)
- [NIST SP 800-171 Revision 2](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final)
- [32 CFR Part 170 – CMMC Regulations](https://www.ecfr.gov/current/title-32/subtitle-A/chapter-I/subchapter-D/part-170)
- [Supplier Performance Risk System (SPRS)](https://www.sprs.csd.disa.mil/)

---

## 11. Key Takeaways

CMMC Level 2 is about demonstrating that an organization can adequately protect Controlled Unclassified Information.

The five major concepts to remember are:

1. **110 security requirements:** Based on NIST SP 800-171 Revision 2.
2. **14 security families:** Cover identity, access, networks, endpoints, monitoring and other security areas.
3. **SSP:** Documents the organization's systems and how security requirements are implemented.
4. **POA&M:** Documents eligible security deficiencies and their remediation.
5. **Assessment and affirmation:** Demonstrate compliance and maintain it over time.

A Systems Administrator helps implement the technical controls, but CMMC compliance is an organization-wide responsibility involving IT, management, security, employees and documented processes.
