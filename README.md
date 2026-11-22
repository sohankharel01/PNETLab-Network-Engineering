# Lab 01 – Simple Network

My first enterprise networking lab built in **PNETLab**. This lab simulates two departments connected through a router, using separate subnets.

## Topology

- 1 Cisco C7200 Router
- 2 Cisco IOL Layer 2 Switches
- 4 PCs (VPCS)
- 2 Printer endpoints (VPCS)
- 2 Departments (IT & HR)

## Network Configuration

| Department | Network | Gateway |
|---|---|---|
| IT | `192.168.40.0/25` | `192.168.40.1` |
| HR | `192.168.40.128/25` | `192.168.40.129` |

### IP Addressing

| Device | IP Address |
|---|---|
| IT-PC1 | `192.168.40.10` |
| IT-Printer | `192.168.40.11` |
| IT-PC2 | `192.168.40.12` |
| HR-PC1 | `192.168.40.130` |
| HR-PC2 | `192.168.40.131` |
| HR-Printer | `192.168.40.132` |

## Tests

- HR-PC1 → HR Gateway: Successful
- HR-PC2 → HR Gateway: Successful
- HR-PC1 → HR-PC2: Successful

## Tools

- PNETLab
- Cisco IOS
- VPCS

## Skills Practiced

- Network topology design
- IPv4 subnetting
- Router and switch configuration
- IP addressing
- Ping testing
- Network troubleshooting

## Author

**SohanSec** — Learning Enterprise Networking & Cybersecurity
