# Networking Fundamentals & Network Simulation Tools

## Week 1 – Internship Task

This repository contains my Week 1 internship task focused on networking fundamentals and hands-on experience with network simulation tools, including Cisco Packet Tracer and GNS3.

The task involved designing and implementing a basic Local Area Network (LAN), configuring static IP addresses, and verifying connectivity between devices using the ping command.

## Objectives

- Understand fundamental networking concepts and communication models.
- Explore Cisco Packet Tracer and GNS3 interfaces.
- Design and implement a basic LAN topology.
- Configure static IPv4 addresses.
- Test connectivity between network devices using ping.
- Develop networking troubleshooting and documentation skills.

## Tools Used

- Cisco Packet Tracer
- GNS3
- PuTTY
- Command Prompt

## Networking Concepts Covered

- Local Area Networks (LAN)
- Network Devices (Switches, Routers, End Devices)
- IPv4 Addressing
- Subnet Masks
- OSI Model
- TCP/IP Model
- ICMP and Ping
- Basic Network Troubleshooting

## Network Topology

A simple LAN topology was designed and implemented in both Cisco Packet Tracer and GNS3.

The topology consists of two end devices connected through a network switch.

**Topology:**

PC1 → Switch → PC2

## IP Address Configuration

| Device | IP Address | Subnet Mask |
|--------|------------|-------------|
| PC0 | 192.168.1.1 | 255.255.255.0 |
| Laptop0 | 192.168.1.2 | 255.255.255.0 |

Both devices were configured within the same subnet to enable communication without requiring a router.

## Connectivity Testing

Connectivity between the devices was verified using the ping command.

From PC1, the following command was executed:

```bash
ping 192.168.1.2
