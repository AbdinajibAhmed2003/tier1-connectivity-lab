Tier 1 Connectivity Troubleshooting Lab
Overview

This lab simulates a common Tier 1 helpdesk scenario where a user reports no network connectivity. The network was built using Cisco Packet Tracer and includes two PCs, a switch, and a router.

Topology

2 PCs

1 Switch

1 Router

Static IP configuration

IP Addressing
Device	IP Address	Subnet Mask	Default Gateway
PC0	192.168.1.10	255.255.255.0	192.168.1.1
PC1	192.168.1.11	255.255.255.0	192.168.1.1
Router	192.168.1.1	255.255.255.0	N/A
Commands Used

ipconfig — Verify IP configuration

ping 192.168.1.1 — Test connectivity to default gateway

ping 192.168.1.11 — Test same-network communication

What This Lab Demonstrates

Basic LAN configuration

Default gateway functionality

Structured troubleshooting methodology

Tier 1 helpdesk diagnostic workflow

Troubleshooting Method

Verify IP configuration

Ping default gateway

Test local device communication

Identify misconfiguration if connectivity fails
