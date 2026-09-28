# System Hardening

This section documents the defensive security activities completed during APEX Planet Task 4.

The objective was to apply basic system-hardening measures to the laboratory environment, including security-update assessment, firewall configuration, and disabling an unnecessary network service.

## 1. Operating System State

The initial operating-system state was recorded before performing the update assessment.

### SS-20A - OS State

[View SS-20A](../Evidence/5-%20System-Hardening/SS-20A-os-state.png)

## 2. Security Update Check

The package repository information was refreshed to determine the available package/update state.

### SS-20B - Update Check

[View SS-20B](../Evidence/5-%20System-Hardening/SS-20B-update-check.png)

## 3. Patch/Upgrade Simulation

A simulated package upgrade was performed to assess available updates without modifying the intentionally vulnerable laboratory system.

### SS-20C - Patch Simulation

[View SS-20C](../Evidence/5-%20System-Hardening/SS-20C-patch-simulation.png)

The actual upgrade was not applied because the target was intentionally vulnerable and was being preserved for the security-testing exercises.

## 4. Firewall Configuration

Inbound firewall rules were configured to allow established connections, SSH access, and loopback traffic while dropping other unmatched inbound traffic.

### SS-21 - Firewall

[View SS-21](../Evidence/5-%20System-Hardening/SS-21-firewall.png)

The final ruleset included:

```text
ESTABLISHED,RELATED  → ACCEPT
TCP/22               → ACCEPT
Loopback             → ACCEPT
Other inbound traffic → DROP
```

## 5. Disable Unused Service

Telnet was identified as an unnecessary service because secure remote administration through SSH was available.

The Telnet service configuration was removed from the relevant service configuration and the service manager was restarted.

### SS-22 - Disable Unused Telnet Service

[View SS-22](../Evidence/5-%20System-Hardening/SS-22-disable-unused-service.png)

Verification confirmed that TCP port 23 was no longer listening.

## Evidence Summary

| Evidence | Hardening Activity |
|---|---|
| SS-20A | OS state |
| SS-20B | Security update check |
| SS-20C | Patch simulation |
| SS-21 | Firewall configuration |
| SS-22 | Unused Telnet service disabled |

## Hardening Principles Demonstrated

- Keep systems updated where operationally appropriate.
- Restrict unnecessary inbound network traffic.
- Allow only required services and ports.
- Disable unnecessary or insecure services.
- Verify the system state after applying security controls.

These controls reduce the attack surface and limit unnecessary exposure.
