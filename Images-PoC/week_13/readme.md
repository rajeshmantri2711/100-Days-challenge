# Week 13

## WEEK 13 REVIEW (Day 85 – Day 91)
**Focus:** LimaCharlie & Splunk Integration, automated threat hunting, and Alert Triage.
**Key Skills Gained:**
- API data pulling and JSON log parsing in Splunk.
- Writing complex D&R rules (VirusTotal lookup + auto-delete).
- Simulated L1/L2 SOC alert triaging.

---

## Daily Progress

## DAY 85
**Activity:**
Integrated LimaCharlie alerts with Splunk.

**Learning and Outcome:**
- **SIEM/EDR Integration:** Successfully configured LimaCharlie to forward detection alerts into the Splunk indexer.

**Proof of Concept:**
- [day_85](day_85.png)

---
---

## DAY 86
**Activity:**
Automated LimaCharlie data ingestion and wrote JSON-parsing SPL.

**Learning and Outcome:**
- **Scripting:** Created a script to automatically pull data from LimaCharlie to a local instance for automatic Splunk indexing.
- **Log Parsing:** Wrote custom SPL to clean up cluttered JSON logs and extract only actionable fields for analysts.

**Proof of Concept:**
- [day_86](day_86.png)
- [day_86_1](day_86_1.png)
- [day_86_2](day_86_2.png)

---
---

## DAY 87
**Activity:**
Refined LimaCharlie D&R rules and integrated VirusTotal lookups.

**Learning and Outcome:**
- **Rule Tuning:** Fixed a runaway rule that was deleting non-malicious files.
- **Threat Intel Integration:** Created a highly specific rule that checks file hashes against the VirusTotal API upon file creation, automatically deleting the file if flagged as malicious.

**Proof of Concept:**
- [day_87](day_87.png)
- [day_87_1](day_87_1.png)

---
---

## DAY 88
**Activity:**
Bash Scripting Revision.

**Learning and Outcome:**
- **Scripting:** Due to a medical emergency limiting lab time, spent available hours reviewing and brushing up on Bash scripting fundamentals.

**Proof of Concept:**
- [day_88](day_88.png)

---
---

## DAY 89
**Activity:**
AI-Assisted Alert Triage Practice.

**Learning and Outcome:**
- **Triage Scenarios:** Leveraged AI to simulate various L1 and L2 alert scenarios to practice response workflows.
- **Goal Setting:** Committed to triaging at least 20 different alerts to improve decision-making speed and accuracy.

**Proof of Concept:**
- [day_89](day_89.png)

---
---

## DAY 90
**Activity:**
Continued Alert Triaging and Log Analysis.

**Learning and Outcome:**
- **Hands-on Analysis:** Applied the triage methodologies practiced on Day 89 to actual log analysis within the lab environment.

**Proof of Concept:**
- [day_90](day_90.png)
- [day_90_1](day_90_1.png)

---
---

## DAY 91
**Activity:**
Completed THM *Network Traffic Rules* and started Cybrary SOC training.

**Learning and Outcome:**
- **Traffic Analysis:** Improved network traffic detection logic.
- **Continuous Learning:** Enrolled in a Cybrary SOC course, committing to 10 modules per day.

**Proof of Concept:**
- [day_91](day_91.png)
- [day_91_1](day_91_1.png)

---
---
