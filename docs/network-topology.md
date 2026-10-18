# Network Topology and Device Inventory

## 1. Project Overview

This document describes the current network topology of the Enterprise Network Lab built in Cisco Packet Tracer.

The network is a work in progress. The current topology contains two PCs, one Layer 2 switch, and one router.

## 2. Device Inventory

| Device | Model | Role |
|---|---|---|
| PC0 | PC-PT | End device |
| PC1 | PC-PT | End device |
| Switch0 | Cisco Catalyst 2960-24TT | Layer 2 switching |
| Router2 | Cisco 2911 | Routing |

## 3. Physical Connections

| Source Device | Destination Device | Purpose |
|---|---|---|
| PC0 | Switch0 | Connects the first PC to the LAN |
| PC1 | Switch0 | Connects the second PC to the LAN |
| Router2 | Switch0 | Connects the router to the switch |

Exact interface assignments will be recorded after verification.

## 4. Current Status

- The four devices are present in the Packet Tracer topology.
- The initial two-PC LAN was tested successfully.
- VLANs 10 (ADMIN) and 20 (HR) have been created on the switch.
- Router-to-switch connectivity and trunk configuration require verification.
- Inter-VLAN routing has not yet been verified.

## 5. Verification

The physical links appear active in the captured topology. Green link indicators alone do not prove that routing or end-to-end connectivity works.

Additional interface checks and connectivity tests will be documented as the project progresses.
## 6. Network Topology Diagram

The following diagram shows the initial network topology built in Cisco Packet Tracer.

![Initial Enterprise Network Topology](initial-topology.png)
