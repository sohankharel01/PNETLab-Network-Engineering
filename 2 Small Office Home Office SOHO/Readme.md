# SOHO Network Lab

A small office network built in **PNETLab** to practice VLANs, switching, routing, DHCP, and basic network security.

## Topology

| Device | Description |
|---|---|
| R1 | Cisco 7200 Router |
| SW1 | Cisco IOL Layer 2 Switch |
| AP1 | OpenWrt Access Point |
| PC1–PC5 | Client devices |

<p align="center">
  <img src="images/router.png" width="250" alt="Router">
  &nbsp;&nbsp;&nbsp;
  <img src="images/switch.png" width="250" alt="Switch">
</p>

## VLANs & IP Addressing

| VLAN | Name | Network | Gateway |
|---|---|---|---|
| 10 | ADMIN | 192.168.10.0/24 | 192.168.10.1 |
| 20 | FINANCE | 192.168.20.0/24 | 192.168.20.1 |
| 30 | CUSTOMER | 192.168.30.0/24 | 192.168.30.1 |

## What I Configured

- Created VLANs 10, 20, and 30
- Configured access ports and 802.1Q trunking
- Implemented Router-on-a-Stick
- Configured DHCP for all VLANs
- Tested IP assignment and gateway connectivity
- Saved device configurations

## Tools

- PNETLab
- Cisco IOS
- OpenWrt

## Project Status

**In Progress** — Working on connectivity, troubleshooting, and network security.

## Goal

Build practical networking skills and learn to design, configure, and secure a segmented office network.
