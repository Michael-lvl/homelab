# Windows 11 – Domain Join

This documents joining a Windows 11 Pro N client machine to the Active Directory domain.

## Configuration Details

- Client OS: Windows 11 Pro N
- Domain: Ayowale.com
- Network: NAT Network (Null)

## Steps Performed

1. I installed Windows 11 Pro N iso then added to VirtualBox
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
