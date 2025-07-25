TCP vs UDP (Main Topic)
TCP (Transmission Control Protocol)
Connection-oriented protocol

Reliable: Ensures all packets are delivered and in order

Slower due to error checking and acknowledgment

Used in: Web browsing (HTTP/HTTPS), emails, file transfers

UDP (User Datagram Protocol)
Connectionless protocol

Unreliable: No guarantee of packet delivery or order

Faster and lightweight

Used in: Live streaming, gaming, DNS lookups
| Feature               | **TCP (Transmission Control Protocol)**       | **UDP (User Datagram Protocol)**               |
| --------------------- | --------------------------------------------- | ---------------------------------------------- |
| **Connection Type**   | Connection-oriented                           | Connectionless                                 |
| **Reliability**       | Reliable – ensures data is delivered in order | Unreliable – no guarantee of delivery or order |
| **Error Checking**    | Yes, with error recovery and acknowledgments  | Yes, but no error recovery                     |
| **Speed**             | Slower (due to handshaking and checks)        | Faster (minimal overhead)                      |
| **Data Transmission** | Stream-based (continuous flow of data)        | Message-based (individual packets)             |
| **Overhead**          | Higher                                        | Lower                                          |
| **Acknowledgment**    | Sent after                                    |                                                |


Key Networking & Cybersecurity Terms
NAT Network (Network Address Translation)
Maps private IP addresses to a public one

Allows multiple devices to access the internet using a single IP

Bridge Network
Connects two network segments, making them act as a single network

Common in virtualization to connect VMs with host network

Subnet (Subnetwork)
Smaller network inside a larger network

Helps in efficient IP management and security

IP Address
Static IP: Manually assigned, fixed address

Dynamic IP: Assigned by DHCP, changes over time

Network
A system of interconnected computers/devices for sharing data/resources

IPv4 vs IPv6
IPv4: 32-bit address, supports ~4.3 billion devices (e.g. 192.168.1.1)

IPv6: 128-bit address, supports trillions of devices (e.g. 2001:db8::1)

UAC (User Account Control)
A Windows security feature that prevents unauthorized system changes

Prompts when admin access is requested

Data Mining
The process of discovering patterns in large data sets using statistics, AI, etc.

MAC ID (Media Access Control Address)
Unique identifier assigned to a device’s network interface card (NIC)

Port Forwarding
Redirects communication requests from one port/address to another

Used to access internal servers from outside a network

Reconnaissance
The first stage of a cyberattack: attacker gathers information about the target

Types:
Active Information Gathering: Direct interaction (e.g., ping, scanning)

Passive Information Gathering: No direct interaction (e.g., social media, public data)

Nmap Command Breakdown
bash
Copy
Edit
nmap -Pn -A -sV -O -oN <filename> --script <script> -vv -p <port> -sS -sT
-Pn: Skip host discovery

-A: Aggressive scan (OS detection, version, script)

-sV: Service/version detection

-O: OS detection

-oN: Save output to a file

--script: Run a script or script category

-vv: Very verbose

-p: Specify port(s)

-sS: Stealth SYN scan

-sT: TCP connect scan

Useful Websites
Have I Been Pwned: Check if your email or password was in a data breach

Wayback Machine: View archived versions of websites

Bug Bounty Platforms:

HackerOne

Bugcrowd

Open Bug Bounty

API Functionality
APIs allow software to communicate and access services/data (e.g., login, fetch user data)

Vulnerabilities here can lead to data leaks, unauthorized access
