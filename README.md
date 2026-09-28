# APEX Planet - Task 4
## Exploitation & System Security

This repository contains the work completed for **Task 4: Exploitation & System Security** as part of the **APEX Planet Cybersecurity & Ethical Hacking Internship**.

The task covered a controlled penetration-testing workflow against an intentionally vulnerable **Metasploitable2** lab system, followed by password attacks, malware analysis, and system-hardening activities.

All testing was performed in a controlled laboratory environment for educational and authorized security testing purposes.

## Repository Structure

```text
APEX-Task4/
│
├── README.md
├── Report/
│   └── Penetration_Testing_Report.pdf
│
├── Evidence/
│   ├── 1-Penetration-Testing-Methodology/
│   ├── 2-Exploitation-with-Metasploit/
│   ├── 3-Password-Attacks/
│   ├── 4-Malware-Analysis/
│   └── 5-System-Hardening/
│
├── Penetration-Testing/
│   └── README.md
├── Exploitation/
│   └── README.md
├── Password-Attacks/
│   └── README.md
├── Malware-Analysis/
│   └── README.md
├── System-Hardening/
│   └── README.md
└── Video/
```

## Task Areas

### 1. Penetration Testing Methodology
Covers network configuration, connectivity, host discovery, DNS reconnaissance, target reconnaissance, TCP/UDP scanning, service/version enumeration, and OS detection.

**Evidence:** SS-01 to SS-11

[View Documentation](./Penetration-Testing/README.md)  
[View Evidence](./Evidence/1-Penetration-Testing-Methodology/)

### 2. Exploitation with Metasploit
Covers Metasploit exploit configuration, reverse-shell establishment, system information collection, and password-hash extraction.

**Evidence:** SS-12 to SS-15

[View Documentation](./Exploitation/README.md)  
[View Evidence](./Evidence/2-Exploitation-with-Metasploit/)

### 3. Password Attacks
Covers SSH password brute-force testing using Hydra and offline password-hash cracking using John the Ripper.

**Evidence:** SS-16 to SS-17

[View Documentation](./Password-Attacks/README.md)  
[View Evidence](./Evidence/3-Password-Attacks/)

### 4. Malware Analysis
Covers static and dynamic analysis of a benign simulated sample in a controlled laboratory environment.

**Evidence:** SS-18 to SS-19

[View Documentation](./Malware-Analysis/README.md)  
[View Evidence](./Evidence/4-Malware-Analysis/)

### 5. System Hardening
Covers security-update assessment, firewall configuration, and disabling an unused Telnet service.

**Evidence:** SS-20A, SS-20B, SS-20C, SS-21, SS-22

[View Documentation](./System-Hardening/README.md)  
[View Evidence](./Evidence/5-%20System-Hardening/)

## Report

[View Penetration Testing Report](./Report/Penetration_Testing_Report.pdf)

## Evidence Summary

| Section | Evidence |
|---|---|
| Penetration Testing Methodology | SS-01 to SS-11 |
| Exploitation with Metasploit | SS-12 to SS-15 |
| Password Attacks | SS-16 to SS-17 |
| Malware Analysis | SS-18 to SS-19 |
| System Hardening | SS-20A, SS-20B, SS-20C, SS-21, SS-22 |

## Video

The Task 4 demonstration video is provided in the `Video/` directory.

## Disclaimer

All activities documented in this repository were performed against intentionally vulnerable systems within a controlled and authorized laboratory environment.

The techniques demonstrated should only be used on systems where explicit authorization for security testing has been provided.
