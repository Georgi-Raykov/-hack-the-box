Machine: Meow

1. General Information 
IP Address:
Operating System: Linux
Tier: Tier 0
Machine Type: Very Easy

2. Enumeration

Network Scan
Tool: nmap
Command: Command: Standard nmap scan for common TCP ports
Open Ports: 23/tcp
Services: telnet

3. Vulnerability Analysis
Identified Vulnerability: The Telnet service allows access without proper authentication
Reason it exists: The service is misconfigured and does not enforce credentials

4. Exploitation
Access Method: Telnet connection to the target service
How access was obtained:
Access Level: User access

5. Privilege Escalation
Method:
Why it worked: Initial access was already at a high privilege level.

6. Defense and Mitigation
How to prevent this attack: Disable Telnet and enforce proper authentication

7. Lessons Learned
New knowledge gained: Understanding the risks of insecure services such as Telnet


