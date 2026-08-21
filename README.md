# service-desk-labs

A practical portfolio of hands-on IT support labs and simulated service desk tickets. Features detailed incident workflows, root cause analyses, Active Directory and networking diagnostics, and structured Knowledge Base articles complete with proof-of-work documentation.

## Technical Skills Demonstrated

- **Directory Services** -- Active Directory user/group management, OU design, GPO, password policies
- **Networking** -- TCP/IP diagnostics, DNS, DHCP, firewall rules, connectivity troubleshooting
- **OS Administration** -- Windows and Linux system configuration, patch management, performance monitoring
- **Incident Management** -- Ticket lifecycle, SLA tracking, escalation procedures, KB documentation

## Ticket Index

| Ticket ID | Category | Issue Summary | Environment | Status | KB Link |
|-----------|----------|---------------|-------------|--------|---------|
| INC0012847 | Remote Access / Mapped Drives / VPN | Shared drive inaccessible — "Network path not found" | Windows 10/11, VPN (IKEv2/IPSec) | Closed | [KB-1054](tickets/INC0012847.md) |
| INC0012862 | Hardware / Display / Graphics Drivers | Second monitor "No Signal" — graphics driver update | Windows 10/11 | Closed | [KB-1055](tickets/INC0012862.md) |
| INC914231 | Hardware / Laptop Power / ACPI Sleep States | Laptop black screen — deep sleep hang, hard reset | Windows Laptop | Closed | [KB-1056](tickets/INC914231.md) |
| INC0012860 | Identity & Access Management / AD | Department transfer — Engineering → IT Infrastructure group reassignment | Active Directory | Closed | [KB-1057](tickets/INC0012860.md) |
| INC0012870 | Infrastructure / Print Server / Network Services | Site-wide printer outage — hung print server PRINT01 rebooted | Server Room B, Enterprise LAN | Closed | [KB-1058](tickets/INC0012870.md) |
| INC789918 | Identity & Access Management / MFA | Account lockout — desynchronized TOTP tokens via MFA reset | Directory Management, Authenticator App | Closed | [KB-1059](tickets/INC789918.md) |
| INC628205 | MDM / Email Configuration / ActiveSync | Corporate email setup on new mobile device — manual ActiveSync config | iOS/Android, ActiveSync/Exchange | Closed | [KB-1060](tickets/INC628205.md) |
| INC938585 | Endpoint Security / Browser Malware & Adware | Rogue browser push notification pop-ups — permissions revoked & full scan clean | Windows 10/11, SD1020 | Closed | [KB-1061](tickets/INC938585.md) |
| INC943775 | Network Storage / SMB Share Mapping / AD Permissions | Engineering share not mapped post-transfer — manual UNC mapping to FILESERV01 | Windows 10/11, SD1026, VPN, FILESERV01 | Closed | [KB-1062](tickets/INC943775.md) |
| INC755877 | Enterprise Printing / TCP/IP Network Printer | Cafeteria-Printer-E offline — stale IP re-mapped to 10.0.2.54 | Windows 10/11, SD1027 | Closed | [KB-1063](tickets/INC755877.md) |
| INC401329 | Desktop Client Software / Email Application Repair | Mail client stuck on "Trying to connect…" — repaired via Programs and Features | Windows 10/11, SD1010 | Closed | [KB-1064](tickets/INC401329.md) |
| INC654239 | Web Browser Security / Search Hijacking & Performance | Browser hijacked by SearchWave — rogue extension removed & settings reset | Windows 10/11, SD1022 | Closed | [KB-1065](tickets/INC654239.md) |
| INC492525 | Desktop Client Software / Email Authentication Failure | Repeated auth prompts despite correct password — repaired via Programs and Features | Windows 10/11, SD1027 | Closed | [KB-1066](tickets/INC492525.md) |
| INC838819 | Remote Access / SMB File Share Mapping & VPN | Offline mapped drive for remote user — VPN verified & share re-mapped | Windows 10/11, SD1025, VPN, FILESERV01 | Closed | [KB-1067](tickets/INC838819.md) |
| INC220144 | Hardware / Power & Sleep State Failure | Laptop stuck in sleep state (blinking power LED) — hard reset | Windows Laptop | Closed | [KB-1068](tickets/INC220144.md) |
| INC648448 | Application Support / Browser Cache & Cookie Corruption | Web pages timed out (ERR_CONNECTION_TIMED_OUT) — cache & cookies cleared | Windows 10/11, SD1019 (Remote / WFH) | Closed | [KB-1069](tickets/INC648448.md) |
| INC605051 | Mobile Device Management / ActiveSync Email & Client State | Mobile mail "Cannot connect to server" — app reinstall restored sync | Mobile Device (iOS/Android), ActiveSync/Exchange | Closed | [KB-1070](tickets/INC605051.md) |
| INC734073 | Identity & Access Management / AD Cached Credentials & VPN | New password rejected at Windows sign-in — VPN tunnel synced cached credentials | Windows 10/11, SD1025 (Remote / WFH), VPN, AD | Closed | [KB-1071](tickets/INC734073.md) |
| INC389824 | Identity & Access Management / AD Group Provisioning | Managerial access missing post-promotion — added to Management security group | Active Directory / Directory Management | Closed | [KB-1072](tickets/INC389824.md) |
| INC881691 | Hardware Failure / Computer Deployment & Logistics | Dead WFH laptop — replacement provisioned via Cloud Provisioning & shipped | Windows 10/11, Remote (Tampa, FL), Cloud Provisioning / Ship Manager | Closed | [KB-1073](tickets/INC881691.md) |
| INC906404 | Infrastructure / Mail Server Unavailability & Performance | Org-wide email outage — EXCH01 degraded, reboot restored service | Server Room A, EXCH01, Enterprise LAN | Closed | [KB-1074](tickets/INC906404.md) |
| INC295378 | Endpoint Security / BitLocker & Drive Encryption Key Recovery | BitLocker recovery lockout — MFA-verified key retrieval unlocked SD1025 | Windows 10/11, SD1025 (Remote / WFH), BitLocker | Closed | [KB-1075](tickets/INC295378.md) |
| INC897559 | Peripheral Failure / Hardware Logistics & Cable Dispatch | External monitors undetected — DisplayPort cable replaced via Ship Manager | Windows 10/11, Docking Station, DisplayPort, Ship Manager | Closed | [KB-1076](tickets/INC897559.md) |
| INC793328 | Malware / Full-Screen Scareware Tech Support Scam | Screen locked by full-screen scareware — browser process terminated & full scan clean | Windows 10/11, SD1007, Remote Desktop | Closed | [KB-1077](tickets/INC793328.md) |
<!-- Add new ticket rows above this comment -->

