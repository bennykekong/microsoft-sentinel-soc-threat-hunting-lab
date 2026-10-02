# Microsoft Sentinel SOC, Threat Hunting & Incident Response Lab

## 🛡️ Project Overview

This project demonstrates the implementation of a Security Operations and Monitoring environment using Microsoft Sentinel and Microsoft Defender for Cloud.

The lab focused on SIEM monitoring, incident management, threat hunting, threat intelligence, and investigation workflows within a Microsoft Azure security environment.

The project was completed as part of my Postgraduate Program in Cyber Security.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Integrate Microsoft Defender for Cloud with Microsoft Sentinel
- Configure security data connectors
- Manage and investigate security incidents
- Perform threat hunting using MITRE ATT&CK tactics
- Ingest Threat Intelligence indicators
- Launch Threat Intelligence-based hunts
- Gain practical experience with SOC investigation workflows

---

## 🧰 Technologies & Security Tools

- Microsoft Sentinel
- Microsoft Defender for Cloud
- Microsoft Azure
- Log Analytics
- Microsoft Defender Threat Intelligence
- MITRE ATT&CK Framework
- Security Information and Event Management (SIEM)
- Security Orchestration, Automation and Response (SOAR)
- Threat Intelligence
- Incident Response

---

## 🏗️ Security Monitoring Architecture

The project used the following general security-monitoring workflow:

```text
Azure / Microsoft Defender for Cloud
              |
              v
        Data Connectors
              |
              v
       Microsoft Sentinel
              |
     ---------------------
     |         |         |
     v         v         v
 Incidents   Hunting   Threat Intelligence
     |         |         |
     -------- Investigation --------
                    |
                    v
             SOC Response

```

---

## 🔵 1. Microsoft Defender Integration


Microsoft Defender for Cloud was integrated with Microsoft Sentinel through the Content Hub and Sentinel data connectors.

### Activities Performed

- Enabled Microsoft Defender for Cloud
- Installed the Defender solution through Microsoft Sentinel Content Hub
- Connected Defender with the Sentinel workspace
- Verified successful data connector status
- Configured analytics functionality for security incidents

---

## 🚨 2. Incident Management

A sample suspected brute-force attack incident was investigated through Microsoft Sentinel.

### SOC Activities Performed

- Located the security incident
- Assigned incident ownership
- Reviewed incident information
- Added investigation comments
- Created an automation rule
- Classified and closed the incident

**Classification:** Benign Positive — Suspicious but Expected

---

## 🔎 3. Threat Hunting with MITRE ATT&CK

Threat hunting was performed using Microsoft Sentinel hunting queries focused on the **MITRE ATT&CK Initial Access** tactic.

### Activities Performed

- Installed hunting content
- Filtered hunting queries by Initial Access
- Executed selected queries
- Reviewed results for anomalous activity and indicators of compromise

---

## 🌐 4. Threat Intelligence Integration

Microsoft Defender Threat Intelligence was integrated with Microsoft Sentinel.

Threat intelligence included:

- IP addresses
- Domains
- File hashes

This provided additional context for security investigations.

---

## 🎯 5. Threat Intelligence-Based Hunting

A dedicated Threat Intelligence hunt was created in Microsoft Sentinel.

### Activities Performed

- Created a Sentinel hunt
- Added TI-based hunting queries
- Executed the queries
- Reviewed findings
- Evaluated results for possible incident creation

---

## 🧠 Skills Demonstrated

- Microsoft Sentinel
- SIEM Monitoring
- SOC Operations
- Incident Response
- Alert Triage
- Threat Hunting
- MITRE ATT&CK
- Threat Intelligence
- Microsoft Defender for Cloud
- Security Automation
- Azure Security Monitoring

---

## ⚠️ Lab Environment Limitations

This project was completed in a controlled lab environment.

Some hunting queries returned no results because the environment did not contain live malicious activity. Sample alerts and test data were used to demonstrate investigation and incident-response workflows.

---

## 🧩 Challenges & Troubleshooting

- Configured appropriate Sentinel and Log Analytics permissions
- Activated Microsoft Defender for Cloud before connector configuration
- Managed Content Hub installation delays
- Adapted investigations to limited lab telemetry

---

## 📚 Key Learnings

- Integrating Microsoft security platforms
- Managing SIEM data connectors
- Investigating and classifying incidents
- Applying MITRE ATT&CK to threat hunting
- Using Threat Intelligence during investigations
- Troubleshooting cloud security configurations

---

## 📸 Project Screenshots

Sanitized implementation screenshots will be stored in the `screenshots/` directory.

---

## 🎓 Project Certification

**Project:** Setting up Security Operations & Monitoring using Microsoft Sentinel  
**Program:** Postgraduate Program in Cyber Security  
**Institution:** Great Learning

---

## 👨‍💻 Author

**Benard Obi Kekong**

Cybersecurity Analyst | CompTIA Security+ | SOC & GRC | Microsoft Sentinel | SIEM | Python
