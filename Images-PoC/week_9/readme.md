## WEEK 9 REVIEW (Day 57 – Day 63)
**Focus:** 
Blue Team operations, heavy emphasis on BTLO scenarios (Forensics, Malware, Networking), and Splunk BOTS.

**Key Skills Gained:** 
- **Forensics:** File recovery and metadata analysis (ExifTool, PhotoRec).  
- **Script Analysis:** PowerShell de-obfuscation and JWT manipulation.  
- **Frameworks:** Applied MITRE D3FEND for countermeasure selection.  
- **SIEM:** Enhanced Splunk SPL skills via BOTS datasets.

## DAY 57
**Activity:**
Completed Advent of Cyber 2025.

**Learning and Outcome:**
- **C2 Detection:** Used Zeek and RITA to identify beaconing behavior and Command & Control channels.  
- **AWS Security:** Explored cloud-specific vulnerabilities and IAM misconfigurations.  
- **Exploitation:** Practiced data exfiltration and interaction using `curl`.

**Proof of Concept:**
- [day_57](day_57.png)
- [day_57_1](day_57_1.png)
- [day_57_2](day_57_2.png)
- [day_57_3](day_57_3.png)

---

## DAY 58
**Activity:**
Completed two challenges from Blue Team Labs Online (BTLO) focusing on forensics and malware.

**Learning and Outcome:** 
- **Image Steganography:** Used tools like `exiftool` to inspect metadata and uncover hidden information within image files.  
- **Malware Analysis:** Analyzed suspicious files to determine capabilities and indicators of compromise (IOCs).  

**Proof of Concept:** 
- [day_58](day_58.png)
- [day_58_1](day_58_1.png)


---

## DAY 59
**Activity:** 
Completed multiple BTLO scenarios: *PowerShell*, *Secrets*, *Log Analysis*, and *Employee of the Year*.

**Learning and Outcome:**
- **PowerShell De-obfuscation:** Analyzed suspicious scripts using text editors and VirusTotal to understand execution flow and payload behavior.  
- **Web Identity (JWT):** Decoded JSON Web Tokens, identified privilege escalation risks via admin claims, and generated secure low-privilege tokens.  
- **Log Analysis:** Investigated web application logic abuse to detect root access exploits that bypassed standard bash history logging.  
- **Digital Forensics:** Recovered deleted files and extracted hidden flags using forensic tools like `PhotoRec`, `Scalpel`, `strings`, and `exiftool`.

**Proof of Concept:**
- [day_59](day_59.png)
- [day_59_1](day_59_1.png)
- [day_59_2](day_59_2.png)
- [day_59_3](day_59_3.png)



---

## DAY 60
**Activity:**
Completed the *Introduction to Splunk* module by Splunk BOTS (Boss of the SOC).

**Learning and Outcome:**
- **SPL Proficiency:** Gained hands-on experience with core commands including `stats`, `eval`, and `lookups`.  
- **Data Enrichment:** Learned how lookups enrich raw log data with external context.  

**Proof of Concept:** 
- [day_60](day_60.png)

---

## DAY 61
**Activity:**
Completed a Network Analysis challenge on BTLO.

**Learning and Outcome:** 
- **Traffic Analysis:** Analyzed PCAP files to identify malicious traffic patterns.  
- **Protocol Inspection:** Investigated packet headers and payloads to reconstruct network events.

**Proof of Concept:** 
- [day_61](day_61.png)

---

## DAY 62
**Activity:** 
Completed a Reverse Engineering challenge on BTLO.

**Learning and Outcome:**
- **Static Analysis:** Examined binary properties without execution to identify strings and potential functionality.  
- **Code Logic:** Understood basic assembly or decompiled code flow to determine the program's objective.

**Proof of Concept:**
- [day_62](day_62.png)

---

## DAY 63
**Activity:** 
Completed the *D3FEND* challenge on BTLO.

**Learning and Outcome:** 
- **MITRE D3FEND:** Applied the MITRE D3FEND framework to map defensive countermeasures against specific offensive techniques.  
- **Defensive Architecture:** Learned how to select appropriate artifacts and defensive mechanisms for specific threat scenarios.

**Proof of Concept:**
- [day_63](day_63.png)

---
