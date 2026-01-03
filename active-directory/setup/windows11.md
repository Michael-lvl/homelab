# Windows 11 – Domain Join

## Purpose

This document covers joining a Windows 11 Pro N client machine to the Active Directory domain and validating domain authentication.

## Configuration Details

- Client OS: Windows 11 Pro N
- Domain: Ayowale.com
- Network: NAT Network (Null)

## Steps Performed

1. Installed Windows 11 Pro N in VirtualBox
2. Configured network adapter to NAT Network (Null)
3. Verified connectivity to the domain controller
4. Joined the system to the `Ayowale.com` domain(faced a little issue with getting the windows 11 to use the same network as the server
5. Restarted the machine
6. Logged in using:
   - Domain Administrator
   - Standard domain user account

## Outcome

- Successful domain join
- Domain authentication verified
- Users able to log in using domain credentials
