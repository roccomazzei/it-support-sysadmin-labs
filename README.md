# IT Support & System Administration Labs

Hands-on portfolio focused on practical skills for entry-level **IT Support, Help Desk, System Administration and Infrastructure** roles, with a progressive path toward **Cybersecurity and Security Operations**.

This repository documents realistic lab environments, troubleshooting workflows, system administration tasks and infrastructure security exercises.

## About This Repository

The purpose of this project is to turn theoretical knowledge into practical, documented experience.

Each lab is built around a realistic technical scenario and includes:

- Environment setup
- Configuration steps
- Troubleshooting methodology
- Commands and tools used
- Root-cause analysis
- Verification
- Screenshots where useful
- Key takeaways

The main focus is currently **System Administration and IT Infrastructure**, with security-oriented labs progressively added on top of the same environment.

## Core Skills

### System Administration

- Windows 10/11 Administration
- Windows Server
- Active Directory Domain Services
- Users, Groups and Organizational Units
- Group Policy
- DNS & DHCP
- File Server Administration
- NTFS & SMB Permissions
- PowerShell
- Linux Administration
- Virtualization
- Backup & Disaster Recovery

### Networking & Troubleshooting

- TCP/IP
- Subnetting
- VLANs
- 802.1Q Trunking
- Routing fundamentals
- NAT
- ACLs
- DNS
- DHCP
- Cisco Packet Tracer
- Network troubleshooting
- Wireshark
- Packet analysis

### Security

- Infrastructure Hardening
- Vulnerability Assessment
- Windows Event Logs
- Sysmon
- Wazuh
- SIEM fundamentals
- Incident Investigation

## Networking Foundation Project

| Project | Technologies | Status |
|---|---|---|
| [Cisco Packet Tracer Networking Capstone](networking/cisco-packet-tracer-capstone/) | Cisco IOS, VLANs, 802.1Q, Router-on-a-stick, Inter-VLAN Routing | ✅ Completed |

## Lab Roadmap

### IT Support & System Administration

| # | Lab | Technologies | Status |
|---|---|---|---|
| 01 | [Windows Network Troubleshooting](windows/network-troubleshooting/) | Windows, TCP/IP, DNS, PowerShell | 🚧 In Progress |
| 02 | Active Directory Deployment | Windows Server, AD DS, DNS, Windows 11 | ⏳ Planned |
| 03 | Users, Groups, OU & Group Policy | Active Directory, GPO, PowerShell | ⏳ Planned |
| 04 | File Server & Permissions | SMB, NTFS, Active Directory Groups | ⏳ Planned |
| 05 | DNS & DHCP Administration | Windows Server, DNS, DHCP | ⏳ Planned |
| 06 | PowerShell Administration | PowerShell, Windows Administration | ⏳ Planned |
| 07 | Linux Server Administration | Linux, SSH, systemd, networking | ⏳ Planned |
| 08 | Wireshark Packet Analysis | Wireshark, TCP/IP, DNS, HTTP/S | ⏳ Planned |
| 09 | Help Desk & Ticketing | GLPI, Troubleshooting, Documentation | ⏳ Planned |
| 10 | Backup & Disaster Recovery | Veeam, Backup, Restore | ⏳ Planned |

### Security & Monitoring

| # | Lab | Technologies | Status |
|---|---|---|---|
| 11 | Vulnerability Assessment & Hardening | Nmap, Windows/Linux Security | ⏳ Planned |
| 12 | Security Monitoring Lab | Wazuh, Sysmon, Windows Event Logs | ⏳ Planned |
| 13 | Incident Investigation | SIEM, Logs, IOC Analysis, Incident Response | ⏳ Planned |

## Lab Methodology

Each project follows the same workflow:

1. Define a realistic IT scenario.
2. Build or configure the required environment.
3. Reproduce the issue or technical requirement.
4. Investigate using appropriate tools and commands.
5. Identify the root cause.
6. Implement the solution.
7. Verify that the issue is resolved.
8. Document the process and lessons learned.

## Planned Lab Environment

The infrastructure will progressively include:

```text
Virtualization Host
│
├── Windows Server
│   ├── Active Directory Domain Services
│   ├── DNS
│   ├── DHCP
│   └── File Services
│
├── Windows 11 Client
│   └── Domain Joined Workstation
│
└── Linux Server
    ├── SSH
    ├── Network Services
    └── Security / Monitoring Tools
```

Later labs will add:

```text
Sysmon
   ↓
Windows Event Logs
   ↓
Wazuh / SIEM
   ↓
Detection
   ↓
Investigation
   ↓
Incident Report
```

## Current Focus

Completed foundation project:

- **Cisco Packet Tracer Networking Capstone** ✅

Current project:

- **Lab 01 — Windows Network Troubleshooting**

The immediate objective is to complete structured Windows network troubleshooting before moving into **Windows Server and Active Directory administration**.

## Learning Path

The repository follows this progression:

```text
Networking & Troubleshooting
          ↓
Windows / Linux Administration
          ↓
Windows Server & Active Directory
          ↓
PowerShell & Automation
          ↓
Backup / Infrastructure Management
          ↓
Hardening & Vulnerability Assessment
          ↓
Security Monitoring
          ↓
Incident Investigation
```

This progression is designed to build strong infrastructure fundamentals first and then apply them to defensive cybersecurity scenarios.
