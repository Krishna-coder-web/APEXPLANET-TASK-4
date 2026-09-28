# Penetration Testing Methodology

This section documents the reconnaissance and scanning phase of APEX Planet Task 4.

The objective was to follow a structured penetration-testing methodology by identifying the target, establishing connectivity, discovering exposed hosts and services, and gathering information required for later exploitation.

## Methodology

```text
Reconnaissance
      ↓
Host Discovery
      ↓
Port Scanning
      ↓
Service Enumeration
      ↓
OS Detection
      ↓
Exploitation
```

The target was an intentionally vulnerable **Metasploitable2** system in a controlled VMware laboratory.

## Evidence

| Evidence | Activity | Link |
|---|---|---|
| SS-01 | Kali Linux IP address | [View SS-01](../Evidence/1-Penetration-Testing-Methodology/SS-01-kali-ip.png) |
| SS-02 | Metasploitable2 IP address | [View SS-02](../Evidence/1-Penetration-Testing-Methodology/SS-02-metasploitable-ip.png) |
| SS-03 | Connectivity test | [View SS-03](../Evidence/1-Penetration-Testing-Methodology/SS-03-connectivity-test.png) |
| SS-04 | Network host discovery | [View SS-04](../Evidence/1-Penetration-Testing-Methodology/SS-04-network-host-discovery.png) |
| SS-05 | Target DNS reconnaissance | [View SS-05](../Evidence/1-Penetration-Testing-Methodology/SS-05-target-dns-recon.png) |
| SS-06 | Basic target reconnaissance | [View SS-06](../Evidence/1-Penetration-Testing-Methodology/SS-06-basic-target-recon.png) |
| SS-07 | Full TCP port scan | [View SS-07](../Evidence/1-Penetration-Testing-Methodology/SS-07-full-tcp-port-scan.png) |
| SS-08 | Service version detection | [View SS-08](../Evidence/1-Penetration-Testing-Methodology/SS-08-service-version-detection.png) |
| SS-09 | OS detection | [View SS-09](../Evidence/1-Penetration-Testing-Methodology/SS-09-os-detection.png) |
| SS-10 | UDP port scan | [View SS-10](../Evidence/1-Penetration-Testing-Methodology/SS-10-udp-port-scan.png) |
| SS-11 | Consolidated service enumeration | [View SS-11](../Evidence/1-Penetration-Testing-Methodology/SS-11-consolidated-service-enumeration.png) |

## Evidence Summary

The reconnaissance and scanning evidence establishes the target's network identity, exposed ports, available services, and system information used to support the later exploitation phase.
