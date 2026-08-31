# FTP Service Security Assessment

## Overview

This project documents a controlled security assessment of a Linux system, focusing on network reconnaissance, FTP service enumeration, anonymous authentication, and sensitive file exposure.

## Assessment Objectives

- Identify exposed network services.
- Enumerate the FTP service and its configuration.
- Test anonymous FTP authentication.
- Identify accessible files within the FTP server.
- Validate the security impact of improper FTP access controls.

## Environment

- Target OS: Linux
- Testing Environment: Authorized cybersecurity training lab
- Attacker Machine: Kali Linux
- Assessment Type: Black-box penetration testing

## Reconnaissance & Enumeration

Network reconnaissance was performed to identify exposed ports and running services on the target system.

Enumeration identified an FTP service accessible over TCP port 21.

## FTP Security Assessment

The FTP service was assessed for authentication and access-control weaknesses.

Anonymous authentication was permitted, allowing access to files hosted on the FTP server without requiring authorized user credentials.

## Skills Demonstrated

- Network reconnaissance
- Service enumeration
- FTP enumeration
- Anonymous FTP assessment
- Linux command-line usage
- Security misconfiguration identification
- Security assessment methodology

## Key Takeaways

This assessment demonstrated the security risks associated with improperly configured FTP services and anonymous authentication.

Restricting anonymous access, enforcing appropriate authentication controls, and reviewing exposed files are important measures for reducing unauthorized information disclosure.
