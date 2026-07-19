# AI-SOC-Alert-Triage
AI-assisted SOC Alert Triage using Wazuh, Sysmon, and Atomic Red Team 
## Project Overview

This project demonstrates a Security Operations Center (SOC) workflow for detecting, analyzing, and documenting Windows security events using open-source cybersecurity tools.

The project combines:

- Wazuh SIEM
- Sysmon
- Windows Wazuh Agent
- Atomic Red Team

to simulate adversary techniques based on the MITRE ATT&CK framework and generate structured incident triage reports.

This repository currently contains **Phase 1** of the project. Future versions will integrate AI to automate alert analysis and report generation.

---

# Project Architecture

```
Atomic Red Team
        │
        ▼
Windows Host
        │
        ▼
Sysmon
        │
        ▼
Wazuh Agent
        │
        ▼
Wazuh Manager (Ubuntu)
        │
        ▼
JSON Alerts
        │
        ▼
Manual SOC Triage Reports
        │
        ▼
Future AI Integration
```

---

# Features

- Wazuh All-in-One deployment
- Windows Wazuh Agent configuration
- Sysmon event collection
- Atomic Red Team attack simulation
- MITRE ATT&CK mapping
- Alert investigation
- AI-style incident reports
- Human verification notes

---

# Environment

Manager

- Ubuntu 22.04
- Wazuh 4.x

Endpoint

- Windows 11
- Sysmon

Attack Simulation

- Atomic Red Team

---

# Atomic Tests Executed

| Technique | Description | Status |
|------------|-------------|--------|
| T1016 | System Network Configuration Discovery | Completed |
| T1083 | File and Directory Discovery | Completed |

---

# Repository Structure

```
alerts/
reports/
screenshots/
docs/
diagrams/
README.md
```

---

# Sample Alert Workflow

```
Atomic Test
      ↓
Windows
      ↓
Sysmon
      ↓
Wazuh Alert
      ↓
JSON Export
      ↓
Incident Analysis
      ↓
SOC Report
```

---

# Reports Included

- AI Triage Report – T1016
- AI Triage Report – T1083

Each report contains:

- Executive Summary
- Alert Details
- MITRE ATT&CK Mapping
- Security Analysis
- Risk Assessment
- Analyst Recommendations
- Human Verification

---

# Screenshots

The repository includes screenshots demonstrating:

- Wazuh Dashboard
- Sysmon Event Logs
- Atomic Red Team Execution
- Alert Details

---

# Future Improvements

- Python-based alert parser
- Automatic IOC extraction
- AI-assisted SOC triage
- Local LLM integration (Ollama + Llama 3.2)
- Automated PDF report generation
- Web dashboard
- Multi-alert correlation

---

# Technologies Used

- Wazuh
- Sysmon
- Atomic Red Team
- MITRE ATT&CK
- Windows 11
- Ubuntu Linux
- PowerShell

---

# Author

Amna Naeem

BS Cyber Security

Air University