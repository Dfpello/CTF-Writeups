# Cybersecurity Portfolio: Technical Write-ups 🛡️

Welcome to my security research and CTF repository. This space is dedicated to documenting the exploitation and remediation of various machines from platforms like **DockerLabs**, **HackTheBox**, and **TryHackMe**.

The primary focus is to demonstrate a structured, professional methodology in **Penetration Testing** and **Vulnerability Assessment**.

---

## 🛠️ Technical Stack & Tools

| Category | Tools |
| :--- | :--- |
| **Reconnaissance** | `Nmap`, `Arp-scan`, `Gobuster`, `WPScan`, `Wappalyzer` |
| **Exploitation** | `Burp Suite`, `Netcat`, `Metasploit`, `Exploit-DB` |
| **Privilege Escalation** | `LinPEAS`, `GTFOBins`, `Sudo Hijacking` `CVE-2025-4517`|
| **Scripting** | `Python`, `Bash`, `PHP` |

---

## 📖 Methodology
Every write-up in this repository follows a standardized 4-step process to ensure clarity and technical depth:

1.  **Reconnaissance:** High-speed scanning and service fingerprinting.
2.  **Enumeration:** Deep diving into web directories, CMS versions, and database services.
2.  **Foothold:** Identification of entry-point vulnerabilities (CVEs, misconfigurations).
3.  **Privilege Escalation:** Internal enumeration to move from low-privilege users to **Root/System**.
4.  **Remediation:** Implementation of hardening measures and security patches.

---

## 🚀 Featured Write-ups

| Machine | Platform | Difficulty | Key Vulnerabilities & Techniques |
| :--- | :--- | :--- | :--- |
| [ChocolateLovers](./DockerLabs/Easy-Faciles/ChocolateLovers.md) | DockerLabs | Easy | CVE-2015-6967 (RCE), Sudoers Hijacking, Cronjob Exploitation |
| [Fruits](./HackersLabs/Easy-Faciles/Fruits.md) | HackerLabs | Easy | Local File Inclusion (LFI), SSH Brute Force, Sudo find (GTFOBins) |
| [Microchoft](./HackersLabs/Easy-Faciles/Microchoft.md) | HackerLabs | Easy | MS17-010 (EternalBlue), SMB Exploitation, Metasploit |
| [Grillo](./HackersLabs/Easy-Faciles/Grillo.md) | HackersLabs | Easy | Info Disclosure, SSH Brute Force, Sudo Puttygen Hijacking |
| [Mortadela](./HackersLabs/Easy-Faciles/Mortadela.md) | HackerLabs | Easy | MySQL Brute Force, CVE-2023-32784 (KeePass Memory Leak), Custom Python Scripting |
| [Facts](./HackTheBox/Easy-Facil/Facts.md) | HackTheBox | Easy | soon |
| [WingData](./HackTheBox/Easy-Facil/WingData.md) | HackTheBox | Easy | soon |

---

## 👤 About Me
I am a cybersecurity enthusiast focused on offensive security and system hardening. Currently developing my skills in web application security and Linux environments.

* **LinkedIn:** [Daniel Fernandez-Pello San Román](https://www.linkedin.com/in/daniel-fern%C3%A1ndez-pello-75691224b/)
---
*Disclaimer: All activities were performed in controlled, authorized environments for educational purposes only.*