# Endpoint Admin Homelab

Hands-on lab documenting my path from deployment technician to Level 2 / systems engineer.
Everything here is built and tested in my own lab environment.

## About me
Deployment Technician working on a large-scale Windows 11 rollout (SCCM/MECM task sequences,
imaging, post-deployment configuration). Master of Business Analytics (Macquarie University).
Currently preparing for **Microsoft 365 Certified: Endpoint Administrator Associate (MD-102)**.

## Lab environment (in progress)
| Component | Purpose |
|---|---|
| DC01 – Windows Server 2025 | Active Directory, DNS, DHCP, Group Policy |
| CLIENT01 – Windows 11 Enterprise | Domain-joined test device |
| Microsoft 365 tenant | Entra ID, Intune, Autopilot, Defender |
| Entra Cloud Sync | Hybrid identity (on-prem AD → Entra ID) |

## Progress
- [ ] Week 1 – Lab build: VirtualBox, domain controller, domain-joined client
- [ ] Week 2 – Active Directory, Group Policy, DNS/DHCP, PowerShell automation
- [ ] Week 3 – On-prem deployment and task sequence troubleshooting (DISM, logs)
- [ ] Week 4 – Entra ID, device enrolment, hybrid identity
- [ ] Week 5 – Intune configuration profiles, compliance, Win32 app deployment
- [ ] Week 6 – Autopilot, update rings, endpoint security (BitLocker, LAPS, Defender)
- [ ] Week 7 – Monitoring, remote management, co-management
- [ ] MD-102 exam

## Scripts
| Script | What it does |
|---|---|
| _coming soon_ | Bulk AD user creation from CSV |
| _coming soon_ | Device inventory report (serial, model, OS build, RAM) |

## Write-ups
_Troubleshooting notes and lab walkthroughs will be added here._

## Contact
[LinkedIn](https://www.linkedin.com/in/talash-bin-taher-391675208/)
