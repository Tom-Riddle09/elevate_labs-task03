# Elevate Labs - Task 03

## Objective  
To perform a basic vulnerability scan of your PC, document the scan results, find critical vulnerabilities and research simple fixes for these vulnerabilites.  

## Tools Used
Lynis - A vulnerability scanner used for auditing, system hardening and compliance for UNIX based systems.  
Debian 12 Bookworm (Minimal CLI installation) VM - used as host.  

## Critical Vulnerabilites
1. Kernel Hardening - Missing some "sysctl" protections.
2. System Services Hardening - Some services are running with unnecessary privileges.
3. SSH Hardening - Default configs not strict enough (likely root login allowed or weak ciphers).

## Quick Fixes for Critical Vulnerabilites
1. Enable kernel hardening by setting recommended "sysctl" parameters for network filtering, address space randomization, and TCP protection.
2. Disable unused or unnecessary system services to reduce attack surface.
3. Harden SSH by disabling root login, enforcing key-based authentication, and using only secure protocols and ciphers.

### Vulnerability Scan Report PDF is uploaded on this repository.

