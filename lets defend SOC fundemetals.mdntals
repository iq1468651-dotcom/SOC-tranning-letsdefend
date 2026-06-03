# 🛡️ SOC Fundamentals: Core Blue Team Modules & Summaries

This file serves as my comprehensive training log and technical breakdown of the foundational modules completed within the Security Operations Center (SOC) curriculum. Each summary explains complex enterprise infrastructure and analytical methods in simple, clear language.

---

## 🗂️ Module 1: Introduction to the SOC (Security Operations Center)
* **The Big Picture:** A SOC is the central command center of an organization's digital defense. It monitors networks, servers, and databases 24/7/365 to detect and stop cyberattacks before they cause damage.
* **Key Concepts:**
    * **The Triad (People, Process, Technology):** Tools alone can't protect a network. Security requires specialized team roles, highly standardized step-by-step procedures, and modern software running in harmony.
    * **SOC Analyst Triage:** Tier 1 analysts act like emergency room doctors. When an alert triggers, they perform the initial evaluation to decide if it is a false alarm (False Positive) or a real threat (True Positive) requiring escalation.

## 🗄️ Module 2: Log Management & Enterprise Telemetry
* **The Big Picture:** Computers, servers, firewalls, and mail routers generate continuous logs of everything they do. Log Management systems act like a massive security camera infrastructure, recording every single action across the enterprise network.
* **Key Concepts:**
    * **Log Centralization:** Instead of logging into 50 different machines to see what happened, log systems collect telemetry from Firewalls, Exchange Mail Servers, Web Proxies, and Endpoints into one searchable interface.
    * **Log Classification:** Understanding how to recognize a log type instantly (e.g., Identifying traffic from a source IP to a target port like `53` specifically as a **DNS Log**).
    * **Enterprise Scoping:** If an alert flags an endpoint (`LetsDefend`) interacting with a known malicious site (`letsdefend.io`), the analyst uses log queries to sweep the whole company network and ensure no other hidden assets are reaching out to that same domain.

## 📊 Module 3: SIEM 101 (Security Information & Event Management)
* **The Big Picture:** Because a network generates billions of raw log events every day, a human cannot read them all. A SIEM is the brain that automatically parses those logs, looks for bad patterns, and generates actionable alerts.
* **Key Concepts:**
    * **Correlation Rules:** A SIEM combines independent events to find hidden attacks. *Example:* 1 failed login log means nothing. But 50 failed login logs on 50 different servers from the same IP address in 2 minutes creates a "Brute Force Attack" alert.
    * **The Analyst Workspace:** Learning how to query the SIEM database, filter out normal employee traffic, and construct a detailed timeline of an incident.

## 🤖 Module 4: SOAR Basics (Security Orchestration, Automation, and Response)
* **The Big Picture:** When a SIEM creates an alert, there are repetitive tasks an analyst has to do manually (like checking an IP on VirusTotal). SOAR tools automate these boring tasks so human analysts can focus on critical problem-solving.
* **Key Concepts:**
    * **Playbooks:** These are digital flowcharts that run automatically when an alert happens. For example: *If a phishing alert triggers -> automatically isolate the computer from the network -> check the attachment in a sandbox -> notify the user.*
    * **Speeding Up Response:** SOAR scales down incident containment times from hours to fractions of a second.

## ⚠️ Module 5: Common Mistakes Made by SOC Analysts
* **The Big Picture:** This module highlights the analytical blind spots and psychological traps that new analysts often fall into when handling live data.
* **Key Concepts:**
    * **The VirusTotal "Green Screen" Trap:** Relying blindly on a `0/90 undetected` clean score. Attackers design advanced malware using Anti-Virus (AV) bypass techniques that local scanners don't recognize yet. VT is a helper, not the final judge.
    * **Sandbox Timing & Evasion:** Assuming a file is safe because it did nothing in a 3-minute sandbox test. Smart malware uses *Sandbox Detection* (refusing to run if it smells a virtual lab) or *Time-Delayed Execution* (sleeping for 15 minutes before acting malicious) to trick the timer.
    * **Stale Cache Data:** Overlooking scan timestamps on reputation sites. Attackers easily buy an old, clean domain and swap it with malicious payloads after its VT score is logged. Analysts must always push a *fresh live rescan*.

---

## 🚀 Practical Technical Achievements
* **Log Parsing:** Extracted raw IP addresses from dense developer repository proxy paths (e.g., `https://github.com/apache/flink/compare`) to trace automated compromise sources.
* **Network Triage:** Mastered the process of identifying threat movement pathways using internal protocol and port mapping analysis.
* **Threat Intel Sweeping:** Practiced threat checking across major defensive databases (such as VirusTotal and AbuseCH).
