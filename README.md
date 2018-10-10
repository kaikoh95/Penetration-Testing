# Penetration_Testing
A brief idea of how a penetration tester would go about doing their daily jobs.

This repository is designed to help understand:
- the kinds of attack vectors that exist
- what an attacker can achieve once they are inside your system. 

Here I used two vulnerability scanners, Nessus and OpenVAS, to scan for vulnerabilities in Metasploitable2 and
Windows XP SP2 virtual machines. 

* Win XP SP2 may not have been pen-tested at this time of committing 

Afterwards, I used the discovered vulnerabilities to exploit those VMs with:
- publicly available exploits in Metasploit
- Armitage. 

Finally, I used Snort to detect these attacks and make alerts when exploit payloads and port scanning activities are present on the network.
