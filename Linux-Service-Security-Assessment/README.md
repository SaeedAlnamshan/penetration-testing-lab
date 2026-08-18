# Linux Service Enumeration & Security Assessment
## Overview

This project documents a controlled security assessment of a Linux system, focusing on network reconnaissance, service enumeration, identification of insecure remote access, and verification of root-level access.

## Assessment Objectives

- Identify the target system and exposed network services.
- Enumerate running services and assess their security configuration.
- Identify insecure remote access exposure.
- Validate access to the target system within the authorized lab environment.
- Verify root-level privileges.
  
 ## Environment

- Target OS: Linux
- Testing Environment: Authorized cybersecurity training lab
- Attacker Machine: Kali Linux
- Assessment Type: Black-box penetration testing

 ## Reconnaissance & Enumeration

The assessment began with network reconnaissance and service enumeration to identify the target system, exposed ports, running services, and potential attack vectors.

### Tools Used

- Nmap
- Kali Linux
- Linux command-line utilities

 ## Remote Access Validation

Enumeration identified an exposed Telnet service on the target system.

The service was assessed within the authorized lab environment, revealing an insecure remote access configuration that allowed direct access to the system with root-level privileges.

The resulting access was verified using standard Linux commands.

## Skills Demonstrated

- Network reconnaissance
- Service enumeration
- Telnet service assessment
- Insecure remote access identification
- Linux command-line navigation
- Root access verification
- Security assessment methodology
  
 ## Key Takeaways

This assessment strengthened my practical understanding of network reconnaissance, service enumeration, and the security risks associated with insecure remote access services.

The exercise also demonstrated the importance of identifying exposed legacy protocols such as Telnet and validating their security configuration during an authorized security assessment.

## Root Access Verification

The screenshot below demonstrates successful root-level access obtained during the authorized security assessment. The flag value has been intentionally redacted.

![Root Access Verification](root-access-verification.png)
