# Three-Tier Enterprise Network Architecture

## Project Overview

This project presents a **Three-Tier Enterprise Network Architecture** designed to simulate a realistic large-scale enterprise environment. The topology combines routing, switching, security, redundancy, network services, and branch connectivity.

The project follows the standard three-tier network model:

- **Core Layer** for high-speed backbone communication.
- **Distribution Layer** for routing, policies, redundancy, and traffic control.
- **Access Layer** for end-user and device connectivity.

The network also includes a branch office connected through secure routing paths. Multiple routing protocols and enterprise technologies are used to demonstrate a complex and reliable network infrastructure.

---

## Network Architecture

### Core Layer

The Core Layer provides fast and reliable communication between different parts of the network.

Main responsibilities:

- High-speed packet forwarding.
- Backbone connectivity.
- Routing between distribution devices.
- Redundant network paths.
- High availability.

### Distribution Layer

The Distribution Layer connects the Core Layer with the Access Layer.

Main responsibilities:

- Inter-VLAN routing.
- Access control policy enforcement.
- Traffic filtering.
- Route distribution.
- Gateway redundancy.
- Load balancing.

### Access Layer

The Access Layer provides network access to end-user devices.

Main responsibilities:

- User and device connectivity.
- VLAN assignment.
- Port security.
- Loop prevention.
- Access port configuration.
- Protection against unauthorized devices.

---

## Core Network Services

The following enterprise network services are included:

| Service | Purpose |
|---|---|
| DNS Server | Resolves domain names into IP addresses. |
| DHCP Server | Automatically assigns IP addresses and network settings. |
| NTP Server | Synchronizes time across all network devices. |
| Syslog Server | Collects logs from network devices for centralized monitoring. |

These services support reliable communication, accurate timestamps, easier device management, and centralized network monitoring.

---

## Routing Technologies

The project uses multiple routing protocols to simulate communication between different enterprise network areas.

### OSPF

Open Shortest Path First is used for internal dynamic routing and area-based network design.

### EIGRP

Enhanced Interior Gateway Routing Protocol is used to demonstrate fast route convergence and internal route sharing.

### BGP

Border Gateway Protocol is used for route exchange between different autonomous systems and external network connections.

### Static and Default Routing

Static and default routes are used where controlled or predictable routing paths are required.

---

## Switching Technologies

The following Layer 2 and Layer 3 switching technologies are configured:

- VLAN segmentation.
- VTP.
- Inter-VLAN routing.
- STP and RSTP.
- EtherChannel.
- DTP.
- Trunk links.
- Access ports.
- LLDP and CDP.
- BPDU Guard.
- Port Security.
- DHCP Snooping.
- IP Helper Address.

These technologies improve network performance, segmentation, security, manageability, and redundancy.

---

## Security Features

The network includes several security controls:

- Standard and extended Access Control Lists.
- Port Security.
- BPDU Guard.
- DHCP Snooping.
- VLAN-based network segmentation.
- Secure VPN tunneling.
- Restricted communication between network zones.
- Controlled access to enterprise services.
- NAT and PAT for private network protection.

These controls help reduce unauthorized access and protect the internal network.

---

## Redundancy and High Availability

The following technologies are used to improve network availability:

### HSRP

Hot Standby Router Protocol provides default gateway redundancy. A standby device can take over when the active gateway becomes unavailable.

### STP and RSTP

Spanning Tree Protocol and Rapid Spanning Tree Protocol prevent switching loops and provide backup Layer 2 paths.

### EtherChannel

EtherChannel combines multiple physical links into one logical connection. This provides greater bandwidth and link redundancy.

### Redundant Connections

Multiple links are used between important network devices to reduce single points of failure.

---

## NAT and PAT

Network Address Translation and Port Address Translation allow internal private devices to communicate with external networks.

Main purposes:

- Preserve public IP addresses.
- Hide internal private IP addresses.
- Allow multiple devices to share one public IP address.
- Control communication between internal and external networks.

---

## VPN Connectivity

VPN tunneling is used to create secure communication between the main enterprise network and the branch network.

The VPN helps protect data when it travels across an untrusted network.

---

## Branch Network

The project includes a separate branch network connected to the main enterprise infrastructure.

The branch network demonstrates:

- Remote office connectivity.
- Secure routing paths.
- OSPF area design.
- BGP route exchange.
- Network segmentation.
- Centralized access to enterprise services.
- Secure communication with the main office.

---

## Technologies and Protocols

| Category | Technologies |
|---|---|
| Routing | OSPF, EIGRP, BGP, Static Routing and Default Routing |
| Switching | VLAN, VTP, STP, RSTP, EtherChannel, DTP and Trunking |
| Redundancy | HSRP, EtherChannel and Redundant Links |
| Security | ACL, Port Security, BPDU Guard and DHCP Snooping |
| Addressing | DHCP, NAT, PAT and IP Helper |
| Monitoring | Syslog, NTP, CDP and LLDP |
| Services | DNS, DHCP, NTP and Syslog |
| Connectivity | VPN Tunneling and Branch Routing |

---

## Project Objectives

The main objectives of this project are:

- Design a realistic enterprise network topology.
- Apply the three-tier network architecture.
- Configure dynamic and external routing protocols.
- Implement VLAN-based network segmentation.
- provide gateway and link redundancy.
- Secure network access and communication.
- Configure centralized enterprise services.
- Connect a branch network securely.
- Improve network availability and scalability.
- Develop practical routing and switching skills.

---

## Key Learning Outcomes

This project helped me strengthen my knowledge and practical skills in:

- Enterprise network design.
- Layer 2 and Layer 3 switching.
- Multi-protocol routing.
- VLAN planning and segmentation.
- Redundancy and high availability.
- Access control and network security.
- Branch network connectivity.
- Network monitoring and logging.
- Infrastructure planning.
- Network troubleshooting.
- Technical documentation.

---

## Project Topology

Add the final network topology image here.

```text
Main Enterprise Network
        │
        ├── Core Layer
        │
        ├── Distribution Layer
        │
        ├── Access Layer
        │
        ├── Enterprise Servers
        │
        └── Secure Branch Network




