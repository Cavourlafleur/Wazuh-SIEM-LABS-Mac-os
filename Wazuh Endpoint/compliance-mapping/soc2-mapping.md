# SOC 2 Control Mapping


# Wazuh Overview

## Purpose
Wazuh is used in this lab as the primary security monitoring and compliance evidence collection platform.

## Lab Goal
The goal is to demonstrate how Wazuh can support audit readiness by collecting security events, identifying vulnerabilities, monitoring file changes, reviewing endpoint configurations, and generating alerts that can be mapped to compliance requirements.

## Wazuh Capabilities Used

| Capability | Compliance Value |
|---|---|
| File Integrity Monitoring | Shows whether sensitive files were changed |
| Security Configuration Assessment | Identifies insecure endpoint configurations |
| Vulnerability Detection | Finds known vulnerabilities on monitored endpoints |
| Authentication Monitoring | Detects failed logins and suspicious access activity |
| Malware Detection | Supports detection of malicious activity |
| Incident Response | Supports alert review, triage, escalation, and remediation |

## Compliance Use
Wazuh evidence can support compliance frameworks by showing that the organization monitors security events, identifies risks, and takes action to remediate issues.

## Important Note
Wazuh does not make an organization compliant by itself. It provides technical evidence that can support compliance readiness when combined with policies, procedures, risk assessments, and remediation tracking.




## Control 1 - Endpoint Monitoring

Security Control:

Endpoint monitoring and alerting.

Implementation:

Wazuh Agent installed on macOS endpoint.

Evidence:

File Integrity Monitoring alerts generated during testing.

Business Value:

Provides visibility into endpoint activity and unauthorized changes.

---

## Control 2 - Security Logging

Security Control:

Centralized logging.

Implementation:

Endpoint events forwarded to Wazuh Manager.

Evidence:

Security events visible in Wazuh Dashboard.

Business Value:

Supports investigations and incident response activities.

---

## Control 3 - Vulnerability Management

Security Control:

Identification of vulnerabilities.

Implementation:

Wazuh Vulnerability Detection.

Evidence:

Chrome vulnerabilities identified.

Adobe Acrobat vulnerabilities identified.

Wireshark vulnerabilities identified.

Business Value:

Helps reduce risk by identifying vulnerable software.

---

## Control 4 - Risk Assessment

Security Control:

Risk identification and remediation planning.

Implementation:

Risk register created from Wazuh findings.

Evidence:

Documented remediation recommendations.

Business Value:

Helps management understand and prioritize risk.

---

## Control 5 - Change Detection

Security Control:

Monitoring for unauthorized changes.

Implementation:

Wazuh File Integrity Monitoring.

Evidence:

File creation, modification, and deletion alerts.

Business Value:

Helps detect suspicious activity.

---

## What I Learned

SOC 2 is not just about tools.

SOC 2 is about demonstrating security controls, documenting evidence, and proving that security processes are operating effectively.
