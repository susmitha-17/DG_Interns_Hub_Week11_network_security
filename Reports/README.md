# Week 11 – SOC: Threat Detection, Alert Correlation & Incident Response

This assessment focuses on core Security Operations Centre (SOC) workflows, including security event monitoring, alert correlation, threat detection, incident investigation, and incident response.

## Technical Topics Covered

### 1. Security Alert Correlation
- Understanding security alert correlation and its importance in identifying suspicious activity.
- Correlating multiple security events to identify potential attack patterns.
- Differentiating between True Positives and False Positives.
- Understanding Indicators of Compromise (IOCs) and their role in threat identification.
- Distinguishing between events, alerts, and incidents.
- Understanding the difference between threat detection and incident response.
- Exploring the responsibilities of L1, L2, and L3 SOC analysts.

### 2. Wazuh Security Monitoring
- Understanding Wazuh SIEM architecture and endpoint monitoring.
- Monitoring authentication events, including successful and failed login attempts.
- Identifying suspicious login patterns and authentication anomalies.
- Monitoring file integrity changes and system-level events.
- Understanding security alerts, rule IDs, severity levels, and agent status.
- Examining how endpoint telemetry supports security investigations.

### 3. Network Intrusion Detection
- Understanding Network Intrusion Detection Systems (NIDS) and Intrusion Prevention Systems (IPS).
- Exploring Snort and Suricata IDS concepts, packet inspection, and signature-based detection.
- Understanding how network traffic analysis helps identify suspicious communication.
- Examining common network activities such as ICMP traffic, port scans, and connection attempts.
- Comparing network-based detection with host-based monitoring through Wazuh.

### 4. Snort and Wazuh Alert Comparison
- Understanding the differences between network-based and host-based security detection.
- Comparing the types of events identified by IDS and SIEM tools.
- Examining detection coverage for ping activity, port scans, and authentication failures.
- Understanding Snort signatures, Suricata signatures, Wazuh rule IDs, and severity classifications.
- Analysing why different security tools may detect different aspects of the same activity.

### 5. SOC Incident Investigation
- Understanding the investigation process for multiple failed login attempts followed by a successful login.
- Identifying event timestamps, targeted accounts, source IP addresses, and failed authentication counts.
- Examining successful authentication and subsequent system activity.
- Correlating authentication logs with available network security events.
- Reviewing detection rules and identifying suspicious behaviour.
- Assessing whether an activity represents a True Positive or False Positive based on supporting evidence.

### 6. Indicator of Compromise (IOC) Identification
- Identifying IP addresses, usernames, suspicious file paths, domains, ports, and protocols.
- Recording event timestamps and relevant detection identifiers.
- Understanding Wazuh Rule IDs and Snort SIDs.
- Organising indicators into structured IOC tables.
- Understanding how IOCs support threat hunting, incident analysis, and security investigations.

### 7. Security Alert Classification
- Understanding the five alert severity categories: Informational, Low, Medium, High, and Critical.
- Classifying security events according to potential impact and risk.
- Evaluating suspicious login activity, port scans, file modifications, and other security events.
- Understanding the importance of prioritising alerts based on severity, context, and available evidence.
- Applying analytical reasoning to distinguish routine activity from potentially malicious behaviour.

### 8. Incident Response Lifecycle
- Understanding the seven stages of incident response:
  - Preparation
  - Identification
  - Analysis
  - Containment
  - Eradication
  - Recovery
  - Lessons Learned
- Exploring methods for investigating, containing, and resolving security incidents.
- Understanding evidence collection, root-cause analysis, system restoration, and preventive measures.

### 9. SOC Incident Ticket Management
- Understanding the structure and purpose of a SOC incident ticket.
- Recording incident IDs, titles, timestamps, severity, affected systems, and detection sources.
- Documenting incident descriptions, evidence, IOCs, investigation findings, and response actions.
- Tracking incident status and providing recommendations for remediation and prevention.
- Understanding the importance of structured incident documentation and escalation.

### 10. SOC Alert Response Playbooks
- Developing structured response procedures for common security scenarios.
- **Multiple Failed Logins:** Detection, investigation, verification, containment, and escalation.
- **Port Scan:** Source identification, authorization verification, traffic investigation, and response.
- **Suspicious File/System Change:** File identification, user and process analysis, investigation, and response.
- Understanding how standardised playbooks improve consistency and efficiency in SOC operations.

## Key Technical Concepts
SOC Operations | SIEM | IDS/IPS | Wazuh | Snort | Suricata | Alert Correlation | Threat Detection | Authentication Monitoring | File Integrity Monitoring | Network Traffic Analysis | Nmap | Wireshark | IOC Analysis | True Positive | False Positive | MITRE ATT&CK | Incident Response | Security Alert Classification | Incident Ticket Management | SOC Playbooks

## Assessment Focus

The overall focus is on understanding how SOC analysts monitor endpoint and network activity, correlate security events, investigate suspicious behaviour, identify indicators of compromise, prioritise alerts, document incidents, and follow structured incident response procedures.
