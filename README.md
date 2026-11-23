# Computer Networks Lab (CSBB 301)

This repository contains the practical work and lab experiment manuals for the **Computer Networks (CSBB 301)** course. It covers fundamental networking concepts, network configuration, routing, transport-layer communication, socket programming, and network simulation and analysis tools.

## Experiments

| Experiment | Topic | Description |
|---|---|---|
| 1 | Network Cables and Crimping | Study of coaxial, twisted-pair, and fibre-optic cables; construction of straight-through and crossover UTP cables using an RJ45 crimping tool. |
| 2 | Basic Network Commands | Practice with command-line utilities for inspecting network configuration, testing connectivity, and troubleshooting routes. |
| 3 | Network Devices | Study and installation of network devices such as NICs, hubs, switches, routers, bridges, repeaters, and access points. |
| 4 | IP Addressing | Study of IPv4 addresses, address classes, public and private addresses, subnet masks, and manual IP configuration. |
| 5 | LAN Connection | Build and verify a local area network using a switch, UTP cables, and a star topology. |
| 6 | Router Configuration using Packet Tracer | Configure a router using Cisco IOS, including hostname, passwords, interface addresses, and saving the configuration. |
| 7 | Peer-to-Peer Network using Switches and a Router | Connect two systems on separate LANs through a router; configure IP addresses and gateways and verify connectivity using `ping`. |
| 8 | Network Address Translation (NAT) | Study and configure Static NAT, Dynamic NAT, and PAT (NAT Overload); inspect translations on a Cisco router. |
| 9 | Routing Protocols | Implement static routing, RIP, and OSPF in a multi-router topology and examine routing tables. |
| 10 | TCP and UDP Client-Server Applications | Implement TCP and UDP client-server echo applications in Python and observe their communication behaviour. |
| 11 | Socket Programming | Study the client-server model and socket functions; implement a multi-threaded chat server in Python for multiple clients. |
| 12 | Network Simulation and Analysis Tools | Explore NS-3, OMNeT++, GNS3, pfSense, Wireshark, and Software-Defined Networking (SDN); inspect packets and test a simple SDN topology. |
| 13 | IP Addressing and DHCP Configuration | Configure network IP addressing statically and dynamically using a DHCP server configured on a router. A Cisco Packet Tracer project file is included. |

## Repository Structure

```text
CN/
├── Exp_1/
│   └── Lab_Experiment_1_Network_Cables_Crimping.pdf
├── Exp_2/
│   └── Lab_Experiment_2_Basic_Network_Commands.pdf
├── Exp_3/
│   └── Lab_Experiment_3_Network_Devices.pdf
├── Exp_4/
│   └── Lab_Experiment_4_IP_Addressing.pdf
├── Exp_5/
│   └── Lab_Experiment_5_LAN_Connection.pdf
├── Exp_6/
│   └── Lab_Experiment_6_Router_Configuration_Packet_Tracer.pdf
├── Exp_7/
│   └── Lab_Experiment_7_Peer_to_Peer_Switch_Router.pdf
├── Exp_8/
│   └── Lab_Experiment_8_Network_Address_Translation.pdf
├── Exp_9/
│   └── Lab_Experiment_9_Routing_Protocols.pdf
├── Exp_10/
│   └── Lab_Experiment_10_TCP_UDP_Client_Server.pdf
├── Exp_11/
│   └── Lab_Experiment_11_Socket_Programming.pdf
├── Exp_12/
│   └── Lab_Experiment_12_NS3_OMNeT_GNS3_pfSense_Wireshark_SDN.pdf
└── Exp_13/
    ├── Lab_Expirement_13.pdf
    └── 13_DHCP_implentation.pkt
```

## Tools and Technologies

The experiment material references or uses the following tools and technologies:

- **Cisco Packet Tracer** — network topology creation and router/DHCP configuration.
- **Python** — TCP/UDP client-server programs and socket programming.
- **Cisco IOS CLI** — router interface and routing configuration.
- **Wireshark** — packet capture and protocol inspection.
- **NS-3, OMNeT++, and GNS3** — network simulation and emulation.
- **pfSense** — network and firewall platform.
- **SDN** — Software-Defined Networking concepts and topology experimentation.

## How to Use

1. Open the folder for the experiment you want to study (`Exp_1` through `Exp_13`).
2. Read the corresponding PDF for the experiment's theory, objectives, procedure, and practical instructions.
3. For Experiment 13, open `13_DHCP_implentation.pkt` in Cisco Packet Tracer to inspect the DHCP configuration project.
4. Use the software specified in the relevant experiment when reproducing the practical work.

## Notes

- The PDFs are the experiment manuals; consult them for the detailed steps and configurations.
- The Packet Tracer `.pkt` file is provided for Experiment 13.
- Tool availability and commands may vary by operating system and software version.

---

**Course:** CSBB 301 — Computer Networks  
**Repository:** Computer Networks Lab Experiments
