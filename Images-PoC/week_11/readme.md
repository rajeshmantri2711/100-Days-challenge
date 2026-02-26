# Week 11

## Daily Progress

## DAY 71
**Activity:**
Completed *Malware Analysis - Ransomware Script* (BTLO).

**Learning and Outcome:**
- **Script Analysis:** Deconstructed a ransomware script to understand encryption methods and propagation logic.
- **IOC Extraction:** Identified indicators of compromise from the malicious script.

**Proof of Concept:**
- [day_71](day_71.png)

---
---

## DAY 72
**Activity:**
Researched Splunk SOAR and Qualys Vulnerability Management.

**Learning and Outcome:**
- **SOAR:** Explored Splunk SOAR (trial version) to understand automation playbooks.
- **Vulnerability Management:** Researched Qualys to prepare for integrating VM data into the Home Lab.

**Proof of Concept:**
- [day_72](day_72.png)
- [day_72_1](day_72_1.png)
- [day_72_2](day_72_2.png)

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
- [day_73](day_73.png)
- [day_73_1](day_73_1.png)

---
---

## DAY 74
**Activity:**
Completed SOC L1 Triaging Challenge (TryHackMe).

**Learning and Outcome:**
- **Alert Triage:** Practiced differentiating between True Positives and False Positives.
- **Decision Making:** Analyzed context (time, user, parent process) to validate alerts.

**Proof of Concept:**
- [day_74](day_74.png)
- [day_74_1](day_74_1.png)

---
---

## DAY 75
**Activity:**
Configured Splunk to Forward Alerts to SOAR.

**Learning and Outcome:**
- **Integration:** Connected Splunk Enterprise to Splunk SOAR to automate incident creation from alerts.
- **Automation:** Established the pipeline required for future playbook execution.

**Proof of Concept:**
- [day_75](day_75.png)
- [day_75_1](day_75_1.png)
- [day_75_2](day_75_2.png)

---
---

## DAY 76
**Activity:**
Wrote Custom Suricata Rules for SSH.

**Learning and Outcome:**
- **Signature Development:** Wrote Suricata rules to specifically detect SSH brute force attempts.
- **Network Defense:** Tuned rules to alert on repeated failed login attempts from external IPs.

**Proof of Concept:**
- [day_76](day_76.png)
- [day_76_1](day_76_1.png)
- [day_76_2](day_76_2.png)
- [day_76_3](day_76_3.png)

## DAY 77
**Activity:**
Explored Splunk SOAR features.

**Learning and Outcome:**
- **SOAR Functionality:** Deepened understanding of how SOAR platforms orchestrate responses.
- **Artifact Analysis:** Learned how to analyze artifacts within the SOAR environment to determine incident scope.

**Proof of Concept:**
- [day_77](day_77.png)

---

## WEEK 11 REVIEW (Day 71 – Day 77)
**Focus:** Malware analysis, Vulnerability Management research, and SOAR integration.
**Key Skills Gained:**
- Deconstructing ransomware scripts.
- Sysmon and Suricata custom rule configuration.
- Connecting Splunk Enterprise to Splunk SOAR for automated alerting.

---
