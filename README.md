# Incident Response Analysis: Phishing & Credential Compromise

## Project Overview

This project presents the analysis of a simulated cybersecurity incident
involving a phishing attack that resulted in compromised employee credentials
and unauthorized access to a customer database.

The incident affected the confidentiality and integrity of customer data,
including unauthorized access, modification, and deletion of records.

This analysis was completed as part of my cybersecurity training and applies
the incident response process to identify the attack, assess its impact,
implement security controls, and recover affected systems.

---

## Objectives

- Identify how the security incident occurred.
- Analyze the impact of compromised credentials.
- Evaluate the security controls involved.
- Apply incident response procedures.
- Recommend preventive and detective security measures.
- Document the recovery process.

---

## Incident Response Process

### 1. Identify

The investigation determined that an attacker obtained an intern's username
and password through a phishing email.

The compromised credentials were then used to gain unauthorized access to
customer database records.

### 2. Protect

Several security measures were proposed to reduce the risk of similar attacks:

- Multi-Factor Authentication (MFA)
- Login attempt limitations
- Employee phishing awareness training
- Improved firewall configuration
- Intrusion Prevention System (IPS)

### 3. Detect

To improve the detection of future unauthorized access attempts, the following
controls were considered:

- Firewall logging
- Intrusion Detection System (IDS)
- Monitoring of incoming network traffic
- Detection of unusual account activity

### 4. Respond

The compromised account was disabled to prevent further unauthorized access.

The incident response process also included:

- Reporting the incident to management
- Employee security awareness training
- Notification of affected customers
- Reporting the incident to the appropriate organizations and authorities

### 5. Recover

Deleted customer data would be restored using the organization's most recent
full database backup.

Any information created or modified after the backup would need to be
re-entered after restoration.

---

## Security Findings

The incident demonstrated how a single compromised account can create
significant security risks when authentication relies only on a username
and password.

The attack affected:

- **Confidentiality:** customer information was exposed to an unauthorized actor.
- **Integrity:** customer records were modified or deleted.

The analysis also highlighted the importance of combining preventive controls
with monitoring and detection mechanisms.

---

## Recommendations

Based on the incident analysis, the following security improvements were
identified:

- Implement Multi-Factor Authentication (MFA).
- Provide regular phishing awareness training.
- Monitor authentication and access logs.
- Deploy IDS/IPS solutions.
- Configure alerts for unusual account behavior.
- Maintain reliable and regularly tested backups.

---

## What I Learned

This project helped me understand that incident response is not limited to
stopping an attack.

An effective response requires identifying the source of the incident,
containing the threat, protecting affected systems, recovering data, and
implementing improvements to reduce the likelihood and impact of future
incidents.

---

## Skills Demonstrated

- Incident Response
- Phishing Analysis
- Credential Security
- Access Control
- Security Monitoring
- IDS / IPS
- Firewall Security
- Data Backup & Recovery
- Security Documentation
- Risk Mitigation

---

## Full Incident Report

The complete incident analysis is available in this repository:

[View Incident Report](reports/incident-report.pdf)

---

## Project Context

This project was completed as part of my cybersecurity training through the
Google Cybersecurity Professional Certificate.

The analysis, observations, and documentation presented in this portfolio
reflect my learning and understanding of cybersecurity incident response.

---

Author: Estefanía Quezada  
Jr Cybersecurity Analyst
