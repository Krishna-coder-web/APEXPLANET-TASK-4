# Password Attacks

This section documents the password-security testing performed during APEX Planet Task 4.

Two techniques were demonstrated in the controlled laboratory environment:

1. SSH password brute-force testing using Hydra
2. Offline password-hash cracking using John the Ripper

## 1. Hydra - SSH Brute-Force Testing

Hydra was used to test SSH authentication against the intentionally vulnerable Metasploitable2 target.

The test demonstrated that weak credentials can be discovered through repeated authentication attempts when appropriate protections are not present.

### SS-16 - Hydra

[View SS-16](../Evidence/3-Password-Attacks/SS-16-hydra.png)

The evidence documents the SSH password attack and the discovered laboratory credentials.

## 2. John the Ripper - Password Hash Cracking

John the Ripper was used to perform offline cracking against password hashes obtained during the controlled exploitation exercise.

### SS-17 - John the Ripper

[View SS-17](../Evidence/3-Password-Attacks/SS-17-Jhon.png)

The evidence documents the password-cracking results.

## Evidence Summary

| Evidence | Tool | Activity |
|---|---|---|
| SS-16 | Hydra | SSH password brute-force testing |
| SS-17 | John the Ripper | Offline password-hash cracking |

## Recommended Defenses

Password attacks can be reduced through:

- Strong and unique passwords
- Appropriate password policies
- SSH key-based authentication
- Account lockout or rate limiting
- Multi-factor authentication where supported
- Monitoring for repeated authentication failures
- Secure password hashing algorithms with appropriate salts and work factors

All testing documented here was performed against the intentionally vulnerable laboratory system.
