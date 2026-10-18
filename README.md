# Enterprise Network Lab

## 1. Project Overview

This project focuses on designing, configuring, testing, and securing an enterprise network using Cisco Packet Tracer.

The goal is to build a simulated enterprise network with multiple departments, network segmentation, inter-VLAN routing, and security controls.

This is a hands-on learning project designed to develop practical networking and cybersecurity skills relevant to CCNA studies and entry-level cybersecurity roles.

## 2. Project Objectives

The main objectives are:

- Design an enterprise network topology.
- Configure VLANs to separate departments.
- Configure trunk links using IEEE 802.1Q.
- Implement inter-VLAN routing.
- Configure IP addressing and default gateways.
- Apply network security controls.
- Test connectivity and troubleshoot network issues.
- Document configurations, tests, and results.

## 3. Tools and Technologies

- Cisco Packet Tracer
- Cisco IOS command-line interface (CLI)
- Ethernet switching
- IPv4 addressing and subnetting
- VLANs and trunking
- Routing and access control lists (ACLs)

## 4. Current Project Status

**Status: In progress**

The initial LAN has been configured and tested successfully. Two PCs connected to a Cisco switch communicated successfully using IPv4.

VLANs 10 (ADMIN) and 20 (HR) have been created on the switch. The router-to-switch connection and inter-VLAN routing still require verification and configuration.

Only verified results will be recorded as completed.

## 5. Planned Network Segmentation

| VLAN ID | Department | Network |
|---|---|---|
| 10 | ADMIN | 192.168.10.0/24 |
| 20 | HR | 192.168.20.0/24 |
| 30 | DMZ | 192.168.30.0/24 |
| 40 | IT | 192.168.40.0/24 |
| 50 | Finance | 192.168.50.0/24 |
| 99 | Management | 192.168.99.0/24 |

These are the planned VLANs. Their final configuration and connectivity will be verified during the project.

## 6. Project Roadmap

- [x] Build and test a basic two-PC LAN.
- [x] Create VLANs 10 and 20.
- [ ] Verify router-to-switch connectivity.
- [ ] Configure switch trunking.
- [ ] Assign PCs to their intended VLANs.
- [ ] Configure inter-VLAN routing.
- [ ] Apply and test network security controls.
- [ ] Perform final connectivity and troubleshooting tests.
- [ ] Complete the network diagram and final documentation.

## 7. Evidence and Results

Screenshots, configuration files, test results, and troubleshooting notes will be added as the project progresses.

## 8. Learning Outcomes

This project aims to strengthen practical skills in enterprise networking, network segmentation, routing, network security, and troubleshooting.
