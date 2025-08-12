Cybersecurity Notes – Day 05
1. Ports & Port Numbers
Think of ports as doors into your system — each service/application has its own.

Port number = unique ID for that door.

Range: 0–65535

0–1023 → Well-known ports (e.g., HTTP, FTP)

1024–49151 → Registered ports (specific applications)

49152–65535 → Dynamic/Private ports (temporary connections)

2. Common Service Ports
Example: FTP – Port 21

FTP (File Transfer Protocol)

Port: 21 (control channel)

Purpose: Transfer files between client ↔ server

Drawback: Sends data in plain text (not secure)

Secure Alternative: SFTP – Port 22 (via SSH)

Other key ports:

HTTP → Port 80

HTTPS → Port 443

SSH → Port 22

3. Linux User Types
Root User → Full system control (administrator)

Regular User → Normal, day-to-day account

Service Accounts → Used by applications/services, not humans

4. Privilege Escalation (Linux)
Gaining higher permissions than allowed.

Types:

Vertical: From regular user → root

Horizontal: Access another user’s data without extra privileges

Common methods:

Misconfigured sudo

Weak file permissions

Kernel vulnerabilities

5. Linux Command Spotlight: watch
Runs a command repeatedly, showing updated results.

Syntax:

bash
Copy
Edit
watch [options] command
Example:

bash
Copy
Edit
watch -n 5 date
(Displays the current date/time every 5 seconds)

6. Security Operations Center (SOC)
The “war room” for cybersecurity defense.

Functions: Monitor, detect, and respond to threats in real-time.

Roles:

Tier 1 Analyst: First responder

Tier 2 Analyst: In-depth investigation

Incident Responder: Containment & recovery

7. Cybersecurity Learning Platforms
TryHackMe → Guided labs & hands-on challenges for hacking skills.

Skills covered: Reconnaissance, exploitation, privilege escalation, etc.

Alternatives: HackTheBox, OverTheWire
