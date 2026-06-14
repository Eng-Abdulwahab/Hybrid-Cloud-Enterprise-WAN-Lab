# Hybrid-Cloud-Enterprise-WAN-Lab

A Cisco Packet Tracer simulation of a secure enterprise network architecture, connecting a local corporate branch to a Private Cloud over a WAN backbone.

## Features Implemented

- **Routing & VLSM:** 4-Router topology (Branch, Hub, ISP, Cloud) using optimized IPv4 subnetting.
- **VLAN Segmentation:** Inter-VLAN routing (VLAN 10 & 20) configured via Router-on-a-Stick (RoaS).
- **Security:** Site-to-Site IPsec VPN tunnel between Branch and Cloud gateways (AES, SHA, DH Group 2).
- **NAT Configuration:** Static 1:1 NAT mapping to securely expose internal Web/DNS servers to the public internet.

## Repository Structure

```text
Hybrid-Cloud-Enterprise-WAN-Lab/
├── README.md
├── Hybrid_Cloud_Enterprise_WAN_Report.pdf
├── packet-tracer/
│   └── Hybrid-Cloud-Enterprise-WAN-Lab.pkt
└── report-latex/
    ├── main.tex
    └── images/
```
