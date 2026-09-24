# Networking Foundation Capstone - Cisco Packet Tracer

## Objective

Design, configure and verify a small business network in Cisco Packet Tracer using the networking concepts covered during the course.

This project is intended to consolidate networking fundamentals before moving into Windows Server, Active Directory and infrastructure administration labs.

## Scenario

A small company has multiple departments that must be logically separated while still being able to communicate through controlled routing.

The network should provide:

- Separate VLANs for different departments
- Correct IPv4 addressing and subnetting
- Trunk links between network devices
- Inter-VLAN routing
- Default gateways for end devices
- Connectivity verification
- Basic access control where appropriate
- Troubleshooting and validation

## Technologies

- Cisco Packet Tracer
- Cisco IOS
- IPv4
- Subnetting
- VLANs
- 802.1Q Trunking
- Inter-VLAN Routing
- Static / Default Routing
- NAT
- ACLs
- ICMP
- ARP

## Planned Topology

The exact topology will be documented once the implementation is complete.

A possible structure is:

```text
                    Internet / ISP
                         |
                       Router
                         |
                       Trunk
                         |
                       Switch
              ___________|___________
             |           |           |
          VLAN 10     VLAN 20     VLAN 30
             |           |           |
            IT        Admin       Sales
```

## Implementation Tasks

- [ ] Define the network requirements
- [ ] Create the IP addressing plan
- [ ] Build the Packet Tracer topology
- [ ] Configure VLANs
- [ ] Configure access ports
- [ ] Configure trunk links
- [ ] Configure inter-VLAN routing
- [ ] Configure end-device IP settings and default gateways
- [ ] Configure routing as required
- [ ] Configure NAT where applicable
- [ ] Configure a basic ACL
- [ ] Verify connectivity
- [ ] Introduce and troubleshoot at least one configuration error
- [ ] Add screenshots and relevant command outputs
- [ ] Document findings and lessons learned

## Verification Commands

Examples of commands that may be used during the lab:

```text
show ip interface brief
show vlan brief
show interfaces trunk
show ip route
show running-config
show access-lists
show ip nat translations
ping
traceroute
```

## Troubleshooting Scenario

At least one deliberate configuration issue will be introduced after the network is working.

The troubleshooting section will document:

- Symptom
- Initial hypothesis
- Commands used
- Root cause
- Corrective action
- Final verification

## Evidence

Screenshots will be added for:

- Final topology
- VLAN configuration
- Trunk configuration
- Routing table
- Successful connectivity tests
- Troubleshooting evidence

## What I Learned

To be completed after the project.
