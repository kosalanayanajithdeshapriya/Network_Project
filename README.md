# Network Project

A computer networking project developed using **Cisco Packet Tracer**. This repository contains the final network design, previous iterative versions of the topology, an academic networking report, and project documentation.

The project demonstrates practical networking concepts through the design, configuration, testing, and documentation of a simulated network environment.

## Repository Contents

| File | Description |
|---|---|
| `network project 1.0.pkt` | Initial version of the Cisco Packet Tracer network topology |
| `network project 2.0.pkt` | Updated topology and configuration version |
| `network project 3.0.pkt` | Further-developed network design |
| `network project 3.1.pkt` | Improved version of the network simulation |
| `network project 3.11.pkt` | Latest/final Cisco Packet Tracer project version |
| `NetworkingReport2022E027.pdf` | Complete networking project report |
| `027_NETWORKPROJECT.docx` | Editable project documentation/report |

## Technologies Used

- Cisco Packet Tracer
- Computer networking concepts
- Router and switch configuration
- IPv4 addressing and subnetting
- LAN/WAN network design
- Network testing and troubleshooting
- Network documentation

## Requirements

To open and explore the network simulation files, install:

- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)

> Use a current Cisco Packet Tracer version for the best compatibility with `.pkt` files.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kosalanayanajithdeshapriya/Network_Project.git
cd Network_Project
```

### 2. Open the final topology

Open the latest project version in Cisco Packet Tracer:

```text
network project 3.11.pkt
```

### 3. Review the documentation

Read the included report to understand the project requirements, network design decisions, configurations, testing approach, and results:

```text
NetworkingReport2022E027.pdf
```

The editable document version is also available:

```text
027_NETWORKPROJECT.docx
```

## Project Workflow

The network was developed iteratively. Each `.pkt` file represents a stage of the project’s development:

```text
Version 1.0
   ↓
Version 2.0
   ↓
Version 3.0
   ↓
Version 3.1
   ↓
Version 3.11 — Final Version
```

This version history makes it possible to review how the network topology and configurations evolved throughout the project.

## How to Test the Network

After opening the Packet Tracer file:

1. Inspect the network topology and connected devices.
2. Review the configuration of routers, switches, PCs, and servers.
3. Check assigned IP addresses, subnet masks, default gateways, and routing configurations.
4. Use the Cisco Packet Tracer **Simulation Mode** to observe packet flow.
5. Use the command prompt on end devices to test connectivity.

Example connectivity test:

```bash
ping <destination-ip-address>
```

Example:

```bash
ping 192.168.1.1
```

A successful reply indicates that the route and device connectivity are working correctly.

## Learning Outcomes

This project provides hands-on experience with:

- Designing a logical and physical network topology
- Configuring network devices in Cisco Packet Tracer
- Planning IPv4 addressing schemes
- Applying subnetting concepts
- Configuring routing and switching components
- Testing network communication using `ping`
- Identifying and troubleshooting connectivity issues
- Producing technical networking documentation

## Documentation

The complete project report is available in two formats:

- **PDF:** `NetworkingReport2022E027.pdf`
- **Word document:** `027_NETWORKPROJECT.docx`

The report should be referred to for detailed information about the proposed solution, diagrams, addressing plan, device configurations, test results, and conclusions.

## Future Improvements

Potential enhancements for this project include:

- Add VLAN segmentation for improved network organization
- Configure inter-VLAN routing
- Add DHCP for automated IP address allocation
- Apply access control lists (ACLs) for security
- Configure NAT/PAT for internet connectivity simulation
- Add wireless network support
- Implement redundancy using multiple switches or routers
- Add server services such as DNS, HTTP, FTP, and email
- Add network monitoring and logging
- Document all IP addressing and device configurations in separate files

## Author

**Kosala Deshapriya**

- GitHub: [@kosalanayanajithdeshapriya](https://github.com/kosalanayanajithdeshapriya)

## License

This project is provided for educational and academic purposes.

If you want to make the project open source, consider adding an appropriate license such as the [MIT License](https://choosealicense.com/licenses/mit/).
