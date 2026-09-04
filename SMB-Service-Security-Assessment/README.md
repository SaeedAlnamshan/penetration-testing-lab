# SMB Service Security Assessment

## Overview

This project documents a controlled security assessment of a Windows system, focusing on network reconnaissance, SMB service enumeration, share discovery, access-control assessment, and exposed file access.

## Assessment Objectives

- Identify exposed network services.
- Enumerate the SMB service and available shares.
- Assess SMB authentication and access controls.
- Identify accessible network shares.
- Validate the security impact of weak SMB share permissions.

## Environment

- Target OS: Windows
- Testing Environment: Authorized cybersecurity training lab
- Attacker Machine: Kali Linux
- Assessment Type: Black-box penetration testing

## Reconnaissance & Enumeration

Network reconnaissance was performed to identify exposed ports and running services on the target system.

Enumeration identified the SMB service operating over TCP port 445.

## SMB Security Assessment

The SMB service was enumerated to identify available network shares and assess their access controls.

An accessible share was identified that permitted access without a valid password. The share contained files that could be accessed and downloaded from the target system.

## Skills Demonstrated

- Network reconnaissance
- SMB service enumeration
- Network share enumeration
- SMB access-control assessment
- Windows file-sharing security assessment
- Linux command-line usage
- Security misconfiguration identification
- Security assessment methodology

## Key Takeaways

This assessment demonstrated the security risks associated with improperly configured SMB shares and weak access controls.

Restricting anonymous or unauthenticated access, applying appropriate share permissions, and regularly reviewing exposed network resources are important measures for reducing unauthorized information disclosure.
