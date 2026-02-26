# Week 10

## WEEK 10 REVIEW (Day 64 – Day 70)
**Focus:**
Advanced Splunk configuration (Field Extractions, Alerting), SOC Interview preparation, and Case Management.

**Key Skills Gained:**
- **Splunk Admin:** Creating persistent field extractions and optimizing SPL.
- **Detection:** Writing logic for port scan detection.
- **Investigation:** Handling BEC cases and understanding SOC ticketing workflows.

---

## Daily Progress

## DAY 64
**Activity:**
Splunk Exploration: Writing Custom SPL and Field Extractions.

**Learning and Outcome:**
- **Active Endpoint Detection:** Wrote SPL to track endpoints active within the last 5 minutes across Linux (`linux_sysmon_xml`) and Windows (`XmlWinEventLog`).
- **Field Extractions:** Configured permanent field extractions in Splunk Settings to normalize `EventID`, `Image`, and `CommandLine` from XML data, replacing the need for repetitive `rex` commands in searches.
- **Optimization:** Reduced SPL complexity and improved search performance by persisting regex logic.

**Technical Note (SPL):**
*List Active Endpoints:*
```splunk
index=* sourcetype IN ("linux_sysmon_xml", "XmlWinEventLog")
| stats latest(_time) AS last_seen BY host
| where now()-last_seen <= 300
| eval last_seen=strftime(last_seen, "%Y-%m-%d %H:%M:%S")
| table host last_seen
```

**Proof of Concept:**
- [day_64](day_64.png)
- [day_64_1](day_64_1.png)

---
---

## DAY 65
**Activity:**
Studied SOC Interview Questions and Answers (Remote Study).

**Learning and Outcome:**
- **Interview Prep:** Reviewed core SOC concepts often asked in interviews.
- **Theory:** Reinforced knowledge of incident response lifecycles and standard analyst triage procedures.

**Proof of Concept:**
- [day_65](day_65.png)

---
---

## DAY 66
**Activity:**
Continued SOC Interview Preparation.

**Learning and Outcome:**
- **Scenario Analysis:** Studied behavioral and technical questions related to threat handling and false positive differentiation.

**Proof of Concept:**
- [day_66](day_66.png)

---
---

## DAY 67
**Activity:**
Refining Splunk SPL for Log Normalization.

**Learning and Outcome:**
- **Log Formatting:** Wrote SPL to normalize output columns, making logs easier to read and present for reporting.
- **Filtering:** Applied advanced filtering techniques to isolate relevant security events.

**Proof of Concept:**
- [day_67](day_67.png)

---
---

## DAY 68
**Activity:**
Configured Splunk Alerts for Port Scanning.

**Learning and Outcome:**
- **Detection Logic:** Created an alert to trigger if a single IP scans multiple ports on a target within a short timeframe.
- **Alerting:** Configured threshold conditions to detect Nmap-style scanning behavior.

**Proof of Concept:**
- [day_68](day_68.png)
- [day_68_1](day_68_1.png)

---
---

## DAY 69
**Activity:**
Completed *Report 2* Challenge from BTLO.

**Learning and Outcome:**
- **Reporting:** Practiced documenting findings and analyzing evidence provided in the challenge scenario.

**Proof of Concept:**
- [day_69](day_69.png)

---
---

## DAY 70
**Activity:**
Completed *BEC-KY* investigation (BTLO) and explored LetsDefend.

**Learning and Outcome:**
- **BEC Investigation:** Analyzed a Business Email Compromise scenario involving phishing and social engineering.
- **Case Management:** Explored LetsDefend to understand how SOC tickets are generated, assigned, and closed in a case management system.

**Proof of Concept:**
- [day_70](day_70.png)
- [day_70_1](day_70_1.png)

---
---
