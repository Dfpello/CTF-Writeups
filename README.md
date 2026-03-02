# Cybersecurity Portfolio: Technical Write-ups 🛡️

Welcome to my security research and CTF repository. This space is dedicated to documenting the exploitation and remediation of various machines from platforms like **DockerLabs**, **HackTheBox**, and **TryHackMe**.

The primary focus is to demonstrate a structured, professional methodology in **Penetration Testing** and **Vulnerability Assessment**.

---

## 🛠️ Technical Stack & Tools

| Category | Tools |
| :--- | :--- |
| **Reconnaissance** | `Nmap`, `Feroxbuster`, `Gobuster`, `WhatWeb`, `Wappalyzer` |
| **Exploitation** | `Burp Suite`, `Netcat`, `Metasploit`, `Exploit-DB` |
| **Privilege Escalation** | `LinPEAS`, `GTFOBins`, `Linux Smart Enumeration (LSE)` |
| **Scripting** | `Python`, `Bash`, `PHP` |

---

## 📖 Methodology
Every write-up in this repository follows a standardized 4-step process to ensure clarity and technical depth:

1.  **Reconnaissance:** High-speed scanning and service fingerprinting.
2.  **Foothold:** Identification of entry-point vulnerabilities (CVEs, misconfigurations).
3.  **Privilege Escalation:** Internal enumeration to move from low-privilege users to **Root/System**.
4.  **Remediation:** Implementation of hardening measures and security patches.

---

## 🚀 Featured Write-ups

| Machine | Platform | Difficulty | Key Vulnerabilities & Techniques |
| :--- | :--- | :--- | :--- |
| [ChocolateLovers](./DockerLabs/Easy-Faciles/ChocolateLovers.md) | DockerLabs | Easy | CVE-2015-6967 (RCE), Sudoers Hijacking, Cronjob Exploitation |
| [Fruits](./HackersLabs/Easy-Faciles/Fruits.md) | HackerLabs | Easy | Local File Inclusion (LFI), SSH Brute Force, Sudo find (GTFOBins)
| [Microchoft](./HackersLabs/Easy-Faciles/Microchoft.md) | HackerLabs | Easy	| MS17-010 (EternalBlue), SMB Exploitation, Metasploit
| [Facts](./HackTheBox/Easy-Facil/Facts.md) | HackTheBox | Easy | soon
| [WingData](./HackTheBox/Easy-Facil/WingData.md) | HackTheBox | Easy | soon

---

## 👤 About Me
I am a cybersecurity enthusiast focused on offensive security and system hardening. Currently developing my skills in web application security and Linux environments.

* **LinkedIn:** [Daniel Fernandez-Pello San Román](https://www.linkedin.com/in/daniel-fern%C3%A1ndez-pello-75691224b/)
---
*Disclaimer: All activities were performed in controlled, authorized environments for educational purposes only.*