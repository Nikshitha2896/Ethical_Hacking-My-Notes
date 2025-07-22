# Introduction to Ethical Hacking

**Ethical Hacking** (aka “white‑hat” hacking) is the authorized practice of probing systems, networks, or applications to find and fix security vulnerabilities before malicious actors can exploit them.

---

## Why Ethical Hacking Matters
- **Proactive Defense**: Identify and fix security holes before they’re abused.  
- **Compliance**: Helps organizations meet industry/regulatory standards (e.g., PCI‑DSS, GDPR).  
- **Trust & Reputation**: Demonstrates commitment to security, building customer and stakeholder confidence.

---

## Key Teams & Roles

### 🔴 Red Team
- **Goal**: Simulate real-world attacks.  
- **Activities**:  
  - Penetration testing  
  - Social engineering (phishing, vishing)  
  - Exploit development  
- **Mindset**: Think like an attacker.

### 🔵 Blue Team
- **Goal**: Defend and detect.  
- **Activities**:  
  - Network & host monitoring  
  - Incident response & forensics  
  - Deploying and tuning security tools (SIEM, EDR, IDS/IPS)  
- **Mindset**: Assume breach; prepare to detect and respond.

### 🟣 Purple Team
- **Goal**: Bridge gaps between Red & Blue.  
- **Activities**:  
  - Facilitate knowledge-sharing and exercises  
  - Turn red‑team findings into defendable detections/rules  
  - Run joint “purple drills” to validate controls  
- **Mindset**: Collaboration for continuous improvement.

---

## The 5 Phases of Ethical Hacking

1. **Reconnaissance (Information Gathering)**  
   - Passive: Public data, WHOIS, social media  
   - Active: Scanning servers, network enumeration  

2. **Scanning & Enumeration**  
   - Port scanning (e.g., Nmap)  
   - Service/version detection  
   - Vulnerability scanning (e.g., Nessus, OpenVAS)

3. **Gaining Access (Exploitation)**  
   - Exploit known vulnerabilities (SQLi, XSS, buffer overflow)  
   - Brute‑force or credential‑stuffing attacks  
   - Maintain least possible footprint

4. **Maintaining Access (Persistence)**  
   - Install backdoors or web shells  
   - Set up cronjobs or scheduled tasks  
   - Ensure return path for future tests

5. **Covering Tracks (Cleanup & Reporting)**  
   - Delete logs or artifacts  
   - Remove created accounts  
   - Compile a clear, actionable report of all findings

---

## Common Frameworks & Methodologies

- **MITRE ATT&CK®**  
  A knowledge base of adversary tactics, techniques, and procedures (TTPs).

- **The Cyber Kill Chain®**  
  1. Reconnaissance  
  2. Weaponization  
  3. Delivery  
  4. Exploitation  
  5. Installation  
  6. Command & Control  
  7. Actions on Objectives

- **OWASP Testing Guide** (for web applications)  
  Covers key areas like authentication, data validation, and business logic.

---

## Getting Started: Tools & Resources

| Tool Category      | Examples                  |
|--------------------|---------------------------|
| Recon & Scanning   | Nmap, Recon-ng, Amass     |
| Exploitation       | Metasploit, SQLmap        |
| Password Attacks   | Hashcat, John the Ripper  |
| Web Testing        | Burp Suite, OWASP ZAP     |
| Blue Team Defense  | Splunk, ELK Stack, Suricata |

**Resources**  
- [Hack The Box](https://www.hackthebox.com)  
- [TryHackMe](https://www.tryhackme.com)  
- [OWASP Foundation](https://owasp.org)  

---

> _Ethical hacking is all about learning attacker behavior to build stronger defenses. Start small, stay curious, and always get proper authorization!_  
