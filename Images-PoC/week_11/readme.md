# Week 11

## Daily Progress

## DAY 71
**Activity:**
Completed *Malware Analysis - Ransomware Script* (BTLO).

**Learning and Outcome:**
- **Script Analysis:** Deconstructed a ransomware script to understand encryption methods and propagation logic.
- **IOC Extraction:** Identified indicators of compromise from the malicious script.

**Proof of Concept:**
- [day_71](Images-PoC/day_71.png)

---
---

## DAY 72
**Activity:**
Researched Splunk SOAR and Qualys Vulnerability Management.

**Learning and Outcome:**
- **SOAR:** Explored Splunk SOAR (trial version) to understand automation playbooks.
- **Vulnerability Management:** Researched Qualys to prepare for integrating VM data into the Home Lab.

**Proof of Concept:**
- [day_72](Images-PoC/day_72.png)

---
---

## DAY 73
**Activity:**
Troubleshooted Sysmon/Splunk Duplicate Logs.

**Learning and Outcome:**
- **Troubleshooting:** Identified an issue where multiple Sysmon logs were generated for the same EventID/Command.
- **Configuration:** Fixed the issue by modifying the Sysmon XML configuration.
- **Resource:** [Custom Sysmon Config](https://github.com/rajeshmantri2711/Splunk-SOC-2025/blob/main/Sysmon/Sysmon-Linux/custom_config.xml)

**Proof of Concept:**
- [day_73](Images-PoC/day_73.png)

---
---

## DAY 74
**Activity:**
Completed SOC L1 Triaging Challenge (TryHackMe).

**Learning and Outcome:**
- **Alert Triage:** Practiced differentiating between True Positives and False Positives.
- **Decision Making:** Analyzed context (time, user, parent process) to validate alerts.

**Proof of Concept:**
- [day_74](Images-PoC/day_74.png)

---
---

## DAY 75
**Activity:**
Configured Splunk to Forward Alerts to SOAR.

**Learning and Outcome:**
- **Integration:** Connected Splunk Enterprise to Splunk SOAR to automate incident creation from alerts.
- **Automation:** Established the pipeline required for future playbook execution.

**Proof of Concept:**
- [day_75](Images-PoC/day_75.png)

---
---

## DAY 76
**Activity:**
Wrote Custom Suricata Rules for SSH.

**Learning and Outcome:**
- **Signature Development:** Wrote Suricata rules to specifically detect SSH brute force attempts.
- **Network Defense:** Tuned rules to alert on repeated failed login attempts from external IPs.

**Proof of Concept:**
- [day_76](Images-PoC/day_76.png)


This repository will continue to be updated weekly.
---