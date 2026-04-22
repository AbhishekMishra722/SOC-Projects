# 🔐 SOC Monitoring & Incident Response Lab

## 📌 Scenario
Simulated SOC environment where multiple security events were generated and monitored using Splunk SIEM. The objective was to detect, analyze, and respond to potential threats in real time.

## 🎯 Objective
- Monitor security events
- Perform alert triage
- Investigate suspicious activities
- Escalate confirmed incidents

## 🛠️ Tools Used
- Splunk SIEM
- VirusTotal
- AbuseIPDB
- MXToolbox
- MITRE ATT&CK Framework

## 🔎 Investigation Process
Followed standard SOC workflow:
**Detection → Triage → Investigation → Escalation**

- Monitored 500+ log events in Splunk
- Identified 20+ suspicious alerts including:
  - Brute-force attacks
  - Malware activity
  - Unauthorized access attempts

## ⚙️ SPL Queries Used
- Detect multiple failed login attempts
- Identify suspicious IP addresses
- Monitor unusual login patterns

## 📊 Findings
- Detected brute-force attempts from malicious IPs
- Identified malware-related indicators
- Correlated logs to confirm unauthorized access attempts

## 🌐 Threat Intelligence Enrichment
- Validated IOCs (IP, domain, URL, hash) using:
  - VirusTotal
  - AbuseIPDB

## 🧠 MITRE ATT&CK Mapping
- T1110 – Brute Force
- T1071 – Application Layer Protocol
- T1059 – Command Execution

## ⚠️ Conclusion
- Multiple alerts classified as **True Positives**
- Incidents escalated based on severity levels

## 📚 Key Learnings
- Hands-on experience with SIEM monitoring
- Improved alert triage and investigation skills
- Better understanding of SOC workflows and threat detection
