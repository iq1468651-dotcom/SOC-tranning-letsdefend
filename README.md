
# 🛡️ Cybersecurity & SOC Analyst Training Portfolio

Welcome to my cybersecurity portfolio! This repository tracks my hands-on laboratory experiences, theoretical mastery, and practical threat analysis skills developed via blue-team training platforms like LetsDefend.

---

## 🛠️ Hands-on Labs & Technical Progress

### 1. Log Management (SIEM & Log Analysis)
* **Status:** In Progress (50% Concepts Completed) ✅
* **Key Skills Demonstrated:**
    * **Log Centralization:** Understood how log management solutions consolidate data from multiple telemetry sources (Proxy, Exchange, Firewall) to run enterprise-wide queries from a single interface.
    * **Network Triage & Scoping:** Learned how to sweep network logs using Indicators of Compromise (IoCs) to find secondary compromised hosts after an initial SIEM alert triggers.
* **Practical Lab Milestone Questions Solved:**
    * *Identified a suspicious external connection targeting a developer repository route (`https://github.com/apache/flink/compare`) by extracting the raw source IP address from web/proxy telemetry.*
    * *Analyzed and classified log types by mapping network signatures, identifying traffic from source IP `8.8.8.8` to destination port `52567` explicitly as a **DNS log**.*

### 2. Common Mistakes made by SOC Analysts
* **Status:** Training Review Completed ✅
* **Key Skills Demonstrated:**
    * **Advanced Threat Intel Validation:** Learned to avoid over-reliance on a clean VirusTotal status screen by accounting for modern AV evasion techniques. 
    * **Sandbox Evasion Recognition:** Mastered how to counter timing-based malware evasion (stalling execution for 10-15 minutes) by adjusting sandbox analysis constraints.
    * **Cache Integrity:** Identified how to check scan timestamps to avoid relying on stale, cached reputation data for high-risk URLs.

---

## 🚀 Technical Skills Summary
* **Log Analysis & Triage:** SIEM concepts, log correlation across Proxy, Firewall, and Exchange environments.
* **Threat Intelligence:** Querying and analyzing reputation databases (VirusTotal, AbuseCH).
* **Protocol & Port Mapping:** Mapping network activities to standardized services (e.g., Identifying DNS attributes).
* **Incident Investigation:** Enterprise scoping, identifying lateral movement patterns, and isolating compromised assets.

---
*Connect with me if you want to talk security, threat hunting, or blue teaming!*
