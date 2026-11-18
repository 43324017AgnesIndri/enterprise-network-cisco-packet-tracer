# Enterprise Network Design and Configuration Using Cisco Packet Tracer

A practical enterprise network infrastructure project designed and implemented using Cisco Packet Tracer.

This project demonstrates multi-router connectivity, IP addressing, subnetting, static routing, inter-LAN communication, and centralized web server deployment.

## Project Overview

The network consists of a central router connected to six branch routers. Each branch provides connectivity to its respective local area network (LAN). A centralized server provides HTTP and HTTPS services and can be accessed by computers across the network.

## Network Architecture

- 7 Routers (1 central router and 6 branch routers)
- 18 PCs distributed across multiple LANs
- Network switches
- 1 centralized server
- Serial point-to-point connections between routers

## Technologies and Concepts

- Cisco Packet Tracer
- IPv4 Addressing
- Subnetting ( /29 and /30 )
- Static Routing
- LAN and WAN Connectivity
- HTTP and HTTPS Services
- Network Connectivity Testing

## IP Addressing

### LAN Networks

| Network | Subnet | Gateway |
|---|---|---|
| Branch 1 | 172.16.0.0/29 | 172.16.0.1 |
| Branch 2 | 172.16.0.8/29 | 172.16.0.9 |
| Branch 3 | 172.16.0.16/29 | 172.16.0.17 |
| Branch 4 | 172.16.0.24/29 | 172.16.0.25 |
| Branch 5 | 172.16.0.32/29 | 172.16.0.33 |
| Branch 6 - LAN 1 | 172.16.0.40/29 | 172.16.0.41 |
| Branch 6 - LAN 2 | 172.16.0.48/29 | 172.16.0.49 |

### WAN Point-to-Point Networks

Point-to-point connections between the central router and branch routers use /30 subnets.

## Implementation

1. Designed the enterprise network topology.
2. Configured router interfaces and IPv4 addresses.
3. Configured serial connections between routers.
4. Implemented static routing.
5. Configured PC network settings and default gateways.
6. Deployed a centralized server with HTTP and HTTPS services.
7. Created a custom web page titled **Portal Infrastruktur Jaringan**.

## Testing and Results

The following connectivity tests were performed:

- PC-to-server connectivity testing.
- Inter-LAN communication testing.
- Router connectivity testing.
- Static routing table verification.
- Web server accessibility testing.

**Result:** All 18 PCs successfully accessed the centralized server, and inter-LAN communication tests were reported successful.

## How to Use

1. Download `enterprise-network-topology.pkt` from this repository.
2. Open Cisco Packet Tracer.
3. Open the downloaded `.pkt` file.
4. Explore the network topology and test connectivity.

## Repository Contents

- `enterprise-network-topology.pkt` — Cisco Packet Tracer simulation file.
- `README.md` — Project documentation.

## Author

**Agnes Siagian**  
Institut Teknologi DEL  
