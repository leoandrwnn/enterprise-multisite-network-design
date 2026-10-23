# Enterprise Multi-Site Network Design

A network engineering project to design and simulate a redundant enterprise network using Cisco Packet Tracer.

## Project Overview

This project simulates the network infrastructure of PT Nusantara Global Indonesia, consisting of a Head Office in Surabaya, a Disaster Recovery Center (DRC) in Bandung, and four branch offices.

## Project Status

**In Progress**

The physical topology is being assembled. Network configuration, connectivity verification, security testing, and failover validation will be documented as they are completed.

## Network Components

- Surabaya Head Office with 10 floors
- Redundant distribution switches and edge routers
- DMZ for public-facing servers
- Bandung Disaster Recovery Center
- Four branch offices
- Dual simulated ISP connections
- Simulated Internet server

## Technologies

- Cisco Packet Tracer
- VLAN and IEEE 802.1Q trunking
- Router-on-a-stick
- HSRP
- Rapid-PVST+
- EtherChannel
- DHCP
- GRE tunnels
- OSPF
- Access Control Lists (ACLs)

## Project Objectives

1. Segment users into separate VLANs.
2. Provide redundant default gateways.
3. Connect branch offices through dual GRE tunnel paths.
4. Configure dynamic routing between sites.
5. Restrict access to the DMZ using ACLs.
6. Simulate disaster recovery connectivity.
7. Verify network connectivity and automatic failover.

## Repository Structure

```text
enterprise-multisite-network-design/
├── README.md
├── NusantaraGlobal.pkt
├── topology/
├── documentation/
├── configs/
└── screenshots/
```

## Verification Plan

- DHCP address assignment
- Inter-VLAN connectivity
- HSRP active and standby states
- EtherChannel status
- OSPF neighbor relationships
- GRE tunnel connectivity
- ACL policy enforcement
- WAN and router failover
- DRC connectivity

Test results will be recorded after each feature is configured and verified.

## How to Open

1. Download the Packet Tracer project file.
2. Open Cisco Packet Tracer.
3. Open the `.pkt` file.
4. Refer to the documentation and screenshots for the network design and verification results.

## Scope and Limitations

This is an educational simulation. The SD-WAN concept is represented using GRE tunnels, dual simulated WAN transports, and OSPF rather than a production SD-WAN controller.

## Author

Network Engineering Portfolio Project

## Disclaimer

This project is intended for educational and portfolio purposes.
