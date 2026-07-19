# Future Work

This project establishes a foundation for an AI-assisted Security Operations Center (SOC) workflow using Wazuh, Sysmon, and Atomic Red Team. While the current implementation successfully detects attacks, exports alerts, and produces AI-assisted incident reports with human verification, several enhancements can further improve automation, scalability, and analytical capabilities.

---

## 1. Automated AI Integration

Currently, Wazuh alerts are manually exported in JSON format and submitted to ChatGPT to generate incident reports.

Future versions will include a Python-based automation tool that:

- Automatically monitors exported Wazuh alerts
- Sends alerts to an AI model through an API
- Receives structured incident analysis
- Eliminates manual copying and pasting

---

## 2. Automatic Report Generation

Develop a Python application capable of automatically generating professional incident reports in multiple formats.

Planned outputs include:

- DOCX reports
- PDF reports
- HTML reports
- Executive summary reports

Each report will contain:

- Incident Summary
- Alert Details
- MITRE ATT&CK Mapping
- Indicators of Compromise (IOCs)
- Risk Assessment
- Recommended Mitigation
- AI Confidence Score
- Human Verification Section

---

## 3. Human-in-the-Loop Workflow

Maintain human oversight to ensure the reliability of AI-generated reports.

Future enhancements include:

- Analyst approval system
- Editable AI-generated reports
- Verification status tracking
- Digital approval signatures
- Audit trail for report modifications

---

## 4. Support for Multiple AI Models

Expand compatibility with different Large Language Models (LLMs), including:

- OpenAI GPT
- Llama
- Mistral
- DeepSeek
- Google Gemini
- Microsoft Phi

This enables organizations to choose models based on privacy, performance, or cost requirements.

---

## 5. Automated Severity Classification

Use AI to automatically classify alerts into categories such as:

- Informational
- Low
- Medium
- High
- Critical

The AI can also assign confidence scores to help analysts prioritize investigations.

---

## 6. Batch Alert Processing

Enable the system to process multiple Wazuh alerts simultaneously.

Future capabilities include:

- Bulk JSON analysis
- Daily report generation
- Scheduled report creation
- Alert prioritization

---

## 7. Interactive SOC Dashboard

Develop a web-based dashboard to provide analysts with:

- AI-generated summaries
- Alert statistics
- Severity distribution
- MITRE ATT&CK visualization
- Detection timelines
- Incident history
- Search and filtering options

---

## 8. Expanded Attack Simulations

Increase testing coverage by executing additional Atomic Red Team techniques, including:

- Credential Access
- Persistence
- Privilege Escalation
- Lateral Movement
- Defense Evasion
- Command and Control
- Exfiltration
- Impact

This will improve the diversity of detection scenarios.

---

## 9. Multi-Endpoint Monitoring

Expand the project beyond a single Windows endpoint by integrating:

- Multiple Windows hosts
- Linux endpoints
- Virtual machines
- Cloud-based systems

This enhancement will better simulate enterprise environments.

---

## 10. Threat Intelligence Integration

Integrate external threat intelligence feeds to enrich alert analysis with:

- Malicious IP reputation
- File hash reputation
- Domain reputation
- Known Indicators of Compromise (IOCs)
- CVE information

This additional context will improve incident investigations.

---

## 11. Automated Incident Response

Integrate automated response actions using Wazuh Active Response, such as:

- Blocking malicious IP addresses
- Terminating suspicious processes
- Isolating compromised hosts
- Disabling malicious user accounts
- Quarantining malicious files

---

## 12. Email and Messaging Notifications

Automatically notify analysts when high-severity alerts are detected through:

- Email alerts
- Microsoft Teams
- Slack
- Discord
- Telegram

---

## 13. Machine Learning for Alert Prioritization

Explore machine learning techniques to:

- Reduce false positives
- Prioritize alerts
- Detect anomalous behavior
- Improve incident triage efficiency

---

## 14. Performance Evaluation

Future research will evaluate:

- AI report generation time
- Detection accuracy
- False positive rate
- Resource utilization
- AI response quality
- Analyst time savings

---

## 15. Research Publication

Future work may include conducting a comprehensive experimental evaluation and publishing research on AI-assisted SOC workflows, including comparisons between manual incident analysis and AI-assisted triage.

---

# Long-Term Vision

The long-term objective of this project is to develop a fully automated AI-assisted SOC platform capable of collecting security events, analyzing alerts using artificial intelligence, generating structured incident reports, recommending mitigation strategies, and supporting security analysts through a human-in-the-loop verification process. This approach aims to improve incident response speed while maintaining analyst oversight and decision-making.