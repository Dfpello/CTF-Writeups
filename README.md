# Cybersecurity Portfolio: Technical Write-ups 🛡️

Welcome to my security research and CTF repository. This space is dedicated to documenting the exploitation and remediation of various machines from platforms like **DockerLabs**, **HackTheBox**, and **HackersLabs**.

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
| [Fruits](./HackersLabs/Easy-Faciles/Fruits.md) | HackersLabs | Easy | Local File Inclusion (LFI), SSH Brute Force, Sudo find (GTFOBins) |
| [Microchoft](./HackersLabs/Easy-Faciles/Microchoft.md) | HackersLabs | Easy | MS17-010 (EternalBlue), SMB Exploitation, Metasploit |
| [Grillo](./HackersLabs/Easy-Faciles/Grillo.md) | HackersLabs | Easy | Info Disclosure, SSH Brute Force, Sudo Puttygen Hijacking |
| [Mortadela](./HackersLabs/Easy-Faciles/Mortadela.md) | HackersLabs | Easy | MySQL Brute Force, CVE-2023-32784 (KeePass Memory Leak), Custom Python Scripting |
| [ZapasGuapas](./HackersLabs/Easy-Faciles/ZapasGuapas.md) | HackersLabs | Easy | OS Command Injection, ZIP Cracking, Sudo apt/aws Shell Escapes |
| [Cyberpunk](./HackersLabs/Easy-Faciles/Cyberpunk.md) | HackersLabs | Easy | Anonymous FTP, Brainfuck Deciphering, Python Library Hijacking |
| [Papafrita](./HackersLabs/Easy-Faciles/Papafrita.md) | HackersLabs | Easy | Source Code Analysis, Brainfuck Obfuscation, Sudo Node.js Escape |
| [Yuan112](./HackMyVM/Easy-Faciles/Yuan112.md) | HackMyVM | Easy | XML External Entity (XXE), Python Brute-force Scripting, Arbitrary File Write |
| [Academy](./HackersLabs/Easy-Faciles/Academy.md) | HackersLabs | Easy | WordPress Brute Force, Bitfile Manager RCE, Privilege Escalation via Cron |
| [SalYAzucar](./HackersLabs/Easy-Faciles/SalYAzucar.md) | HackersLabs | Easy | SSH Brute Force, Sudo base64 Abuse (GTFOBins), SSH Key Cracking |
| [Facts](./HackTheBox/Easy-Facil/Facts.md) | HackTheBox | Easy | soon |
| [WingData](./HackTheBox/Easy-Facil/WingData.md) | HackTheBox | Easy | soon |

---

## 👤 About Me
I am a cybersecurity enthusiast focused on offensive security and system hardening. Currently developing my skills in web application security and Linux environments.

* **LinkedIn:** [Daniel Fernandez-Pello San Román](https://www.linkedin.com/in/daniel-fern%C3%A1ndez-pello-75691224b/)
---
*Disclaimer: All activities were performed in controlled, authorized environments for educational purposes only.*