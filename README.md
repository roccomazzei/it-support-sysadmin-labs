# IT Systems Administration Labs

Hands-on portfolio documenting practical **System Administration, IT Infrastructure, Networking and Cloud** skills, with a progressive extension toward **Cybersecurity and Security Operations**.

The learning roadmap is aligned with the technical modules of the Udemy course **“Sistemista e Sistemistica: la Masterclass! 44 Ore [NEW 2026]”**, while every portfolio project is implemented, tested and documented independently.

## Current Progress

| Module | Area | Status |
|---|---|---|
| 01 | Networking | 🚧 In Progress |
| 02 | Linux | ⏳ Planned |
| 03 | PowerShell | ⏳ Planned |
| 04 | Infrastructure & Backup | ⏳ Planned |
| 05 | Virtualization | ⏳ Planned |
| 06 | Windows Server & Active Directory | ⏳ Planned |
| 07 | Windows 11 Administration | ⏳ Planned |
| 08 | Microsoft Exchange 2019 | ⏳ Planned |
| 09 | Amazon AWS | ⏳ Planned |
| 10 | Microsoft Azure | ⏳ Planned |

## Portfolio Roadmap

### 01 — Networking

Course topics include Cisco Packet Tracer, IPv4 addressing, subnetting, switching, VLANs, 802.1Q trunks, routing, NAT, ACLs and network troubleshooting.

Projects:

- [Cisco Packet Tracer Networking Capstone](01-networking/cisco-packet-tracer-capstone/) — ✅ Completed
- [Windows Network Troubleshooting](01-networking/windows-network-troubleshooting/) — 🚧 In Progress
- Multi-switch VLAN and trunking exercises — Practice

### 02 — Linux

Planned hands-on areas:

- Linux installation and virtual lab setup
- Shell scripting fundamentals
- Users, files and permissions
- IP configuration and network troubleshooting
- `ip`, `netstat`, `dig`, `tcpdump`
- Nmap and Wireshark
- Linux firewall fundamentals
- Security monitoring fundamentals

### 03 — PowerShell

Planned hands-on areas:

- Filesystem and administration commands
- Variables, conditions, loops and arrays
- Network diagnostics
- Ping and ARP automation
- DNS checks
- Port checks
- Hashing
- Administrative scripting

Portfolio target: **PowerShell Admin Toolkit**.

### 04 — Infrastructure & Backup

Planned hands-on areas:

- Network and server administration
- File services
- DNS / IIS / FTP
- Firewall and VPN fundamentals
- Infrastructure migration concepts
- Veeam backup repositories and jobs
- VM and file restore
- Active Directory recovery
- Backup validation and disaster recovery

Portfolio target: **Backup & Disaster Recovery Lab**.

### 05 — Virtualization

Planned hands-on areas:

- Oracle VirtualBox
- Hyper-V
- VMware / ESXi
- Virtual networking
- Virtual switches
- Storage
- VLANs in virtual environments
- VM lifecycle and snapshots

Virtualization will also provide the infrastructure for later Windows Server and security labs.

### 06 — Windows Server & Active Directory

This is the main enterprise administration block of the portfolio.

Planned labs:

- Windows Server deployment
- Active Directory Domain Services
- Windows client domain join
- Users, groups and Organizational Units
- Share and NTFS permissions
- Group Policy
- Home folders and mapped drives
- FSMO roles
- Secondary Domain Controller
- DNS zones
- Active Directory Sites and Services
- Windows Admin Center
- Domain trusts
- IIS and FTP
- Certification Authority
- Shadow Copies
- DFS
- Remote Desktop Services
- DHCP
- WDS
- WSUS
- Hyper-V
- RADIUS / AD authentication

### 07 — Windows 11 Administration

Planned hands-on areas:

- Disk and update management
- User Account Control
- Microsoft Defender
- Windows Firewall
- Restore points
- BitLocker
- LAN configuration
- File sharing and users
- Local policy
- Windows Registry
- Performance Monitor

Portfolio target: **Windows Endpoint Administration & Hardening Lab**.

### 08 — Microsoft Exchange 2019

Planned hands-on areas:

- Exchange lab deployment
- DNS integration
- ECP administration
- Mail flow
- Send connectors
- Mailbox databases
- Virtual directories
- SSL certificates
- SPF, DKIM and DMARC
- User and shared mailboxes
- Mailbox troubleshooting

### 09 — Amazon AWS

Planned hands-on areas:

- AWS CLI
- IAM and MFA
- EC2
- AMIs
- EBS
- VPC
- Security Groups
- Linux and Windows cloud instances
- Auto Scaling
- ELB / ALB / NLB
- ECS and Docker
- Elastic Beanstalk
- Lambda

Portfolio target: **AWS Infrastructure Lab**.

### 10 — Microsoft Azure

Planned hands-on areas:

- Azure infrastructure
- Virtual machines
- Virtual networking
- Cloud administration
- Backup
- Security fundamentals

Portfolio target: **Azure Infrastructure Lab**.

## Beyond the Course — Security Extension

After the core infrastructure modules, the same lab environment will be extended with:

- Vulnerability assessment and hardening
- Windows Event Logs
- Sysmon
- Wazuh
- SIEM fundamentals
- Detection engineering basics
- Incident investigation and reporting

This connects the System Administration portfolio with the longer-term Cybersecurity path.

## Lab Methodology

Each portfolio project follows the same workflow:

1. Define a realistic technical scenario.
2. Build the environment.
3. Configure the required services.
4. Verify expected behavior.
5. Introduce or encounter a realistic fault.
6. Troubleshoot systematically.
7. Correct the root cause.
8. Verify the fix.
9. Document configuration, evidence and lessons learned.

## Repository Structure

```text
it-systems-administration-labs/
│
├── 01-networking/
├── 02-linux/
├── 03-powershell/
├── 04-infrastructure-backup/
├── 05-virtualization/
├── 06-windows-server-active-directory/
├── 07-windows-11/
├── 08-exchange-2019/
├── 09-aws/
└── 10-azure/
```

Folders are populated as the corresponding hands-on work is completed. The repository is intended to show practical capability rather than simply mirror course lessons.

## Current Focus

Networking fundamentals have been completed at course level.

The **Cisco Packet Tracer Networking Capstone** is complete. The next portfolio task is **Windows Network Troubleshooting**, followed by the Linux module.
