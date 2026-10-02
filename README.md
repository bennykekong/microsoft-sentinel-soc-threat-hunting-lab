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
