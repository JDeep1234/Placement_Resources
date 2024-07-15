# Table of Contents 

| Sl. No. | Topic                                                   |
| ------- | ------------------------------------------------------- |
| 1       | [What is Network](#1-what-is-network)                   |
| 2       | [Types of Network ](#2-types-of-network)                |
| 3       | [Network Devices](#3-network-devices)                   |
| 4       | [Network Topology](#4-network-topology)                 |

---

# 1. What is Network

A computer network is a system that connects many independent computers to share information (data) and resources. The integration of computers and other different devices allows users to communicate more easily. A computer network is a collection of two or more computer systems that are linked together. A network connection can be established using either cable or wireless media. Hardware and software are used to connect computers and tools in any network.

## Functionalities of Computer Network

- Computer Networks help in operating virtually
- Computer Networks integrate on a large scale
- Computer Networks respond very quickly in case of conditions change
- Computer Networks help in providing data security

## Key Components of a Computer Network

In simple terms, a computer network is made up of two main parts: devices (called nodes) and connections (called links). The links connect the devices to each other. The rules for how these connections send information are called communication protocols. The starting and ending points of these communications are often called ports.The key components are :
- Network Devices
- Links
- Communication Protocols
- Network Defense

## How Does a Computer Network Work?
Computer Networks simply work using nodes and links. Data communication equipment is simply termed as Nodes. For example, Modems, Hubs, Switches, etc. whereas links in Computer networks can be referred to as a connection between two nodes. We have several types of links like cable wires, optical fibers, etc. 

Whenever a Computer Network is working, nodes have the work of sending and receiving data via the links. Computer Network provides some set of protocols that help in following the rules and protocols.

## Criteria of a Good Network
- Performance: It can be measured in many ways, including transmit time and response time. Transit time is the amount of time required for a message to travel from one device to another. Response time is the elapsed time between an inquiry and a response. The performance of the network depends on a number of factors, including the number of users, the type of medium & Hardware.
- Reliability: In addition to accuracy is measured by frequency of failure, the time it takes a link to recover from failure, and the network’s robustness in catastrophe. 
- Security: Network security issues include protecting data from unauthorized access, protecting data from damage and development, and implementing policies and procedures for recovery from breaches and data loss.  

# 2. Types of Network 

## Division Based on Area Covered
- Local Area Network (LAN): A LAN is a network that covers an area of around 10 kilometers. For example, a college network or an office network. Depending upon the needs of the organization, a LAN can be a single office, building, or Campus. We can have two PCs and one printer in-home office or it can extend throughout the company and include audio and video devices. Each host in LAN has an identifier, an address that defines hosts in LAN. A packet sent by the host to another host carries both the source host’s and the destination host’s address.
- Metropolitan Area Network (MAN): MAN refers to a network that covers an entire city. For example: consider the cable television network.
- Wide Area Network (WAN): WAN refers to a network that connects countries or continents. For example, the Internet allows users to access a distributed system called www from anywhere around the globe.WAN interconnects connecting devices such as switches, routers, or modems. A LAN is normally privately owned by an organization that uses it. We see two distinct examples of WANs today: point-to-point WANs and Switched WANs 
   - Point To Point: Connects two connecting devices through transmission media. 
   - Switched: A switched WAN is a network with more than two ends.

## Types of Computer Network Architecture
Computer Network Architecture is of two types. These types are mentioned below.

- Client-Server Architecture: Client-Server Architecture is basically the architecture where the clients and the server are connected as two clients can communicate with each other and the devices present work as servers in the network.
- Peer-to-Peer Architecture: Peer-to-Peer Architecture, computers are connected to each other and each computer is equally capable of working as there is no central server here. Each device present here can be used as a client or server.

# 3. Network Devices 

- NIC (Network Interface Card): A network card, often known as a network adapter or NIC (network interface card), is computer hardware that enables computers to communicate via a network. It offers physical access to networking media and, in many cases, MAC addresses serve as a low-level addressing scheme. Each network interface card has a distinct identifier. This is stored on a chip that is attached to the card.
- Repeater: A repeater is an electrical device that receives a signal, cleans it of unwanted noise, regenerates it, and retransmits it at a higher power level or to the opposite side of an obstruction, allowing the signal to travel greater distances without degradation. In the majority of twisted pair Ethernet networks, Repeaters are necessary for cable lengths longer than 100 meters in some systems. Repeaters are based on physics.
- Hub: A hub is a device that joins together many twisted pairs or fiber optic Ethernet devices to give the illusion of a formation of a single network segment. The device can be visualized as a multiport repeater. A network hub is a relatively simple broadcast device. Any packet entering any port is regenerated and broadcast out on all other ports, and hubs do not control any of the traffic that passes through them. Packet collisions occur as a result of every packet being sent out through all other ports, substantially impeding the smooth flow of communication.
- Bridges: Bridges broadcast data to all the ports but not to the one that received the transmission. Bridges, on the other hand, learn which MAC addresses are reachable through specific ports rather than copying messages to all ports as hubs do. Once a port and an address are associated, the bridge will only transport traffic from that address to that port.
- Switches: A switch differs from a hub in that it only forwards frames to the ports that are participating in the communication, rather than all of the ports that are connected. The collision domain is broken by a switch, yet the switch depicts itself as a broadcast domain. Frame-forwarding decisions are made by switches based on MAC addresses.
- Routers: Routers are networking devices that use headers and forwarding tables to find the optimal way to forward data packets between networks. A router is a computer networking device that links two or more computer networks and selectively exchanges data packets between them. A router can use address information in each data packet to determine if the source and destination are on the same network or if the data packet has to be transported between networks. When numerous routers are deployed in a wide collection of interconnected networks, the routers share target system addresses so that each router can develop a table displaying the preferred pathways between any two systems on the associated networks.
- Gateways: To provide system compatibility, a gateway may contain devices such as protocol translators, impedance-matching devices, rate converters, fault isolators, or signal translators. It also necessitates the development of administrative procedures that are acceptable to both networks. By completing the necessary protocol conversions, a protocol translation/mapping gateway joins networks that use distinct network protocol technologies.

# 4. Network Topology

The structure of the network and how each component is connected to the others are defined by the network topology. Different types of network topology are mentioned below:

- Bus Topology
- Ring Topology
- Star Topology
- Mesh Topology
- Tree Topology

## Bus Topology

Every computer and network device is connected to a single cable in a bus topology network. Linear Bus topology is defined as having exactly two terminals.

![screenshot](Images/Bus_Topology.png)

  ## Advantages
   - Installation is simple
   - Compared to mesh, star, and tree topologies, the bus utilizes less cabling
  ## Disadvantages
   - Difficulty in reconfiguring and isolating faults
   - A bus cable malfunction or break interrupts all communication

## Ring Topology

The topology is named ring topology because one computer is connected to another, with the final one being connected to the first. Exactly two neighbors for each device. A signal is passed along the ring in one direction. Each ring incorporates a repeater. 

![screenshot](Images/Ring_Topology.png)

  ## Advantages
   - Data transmission is relatively straightforward because packets only move in one direction
   - There is no requirement for a central controller to manage communication between nodes
   - Easy installation & Reconfiguration
   - Simplified Faulty connections
  ## Disadvantages
   - In a Unidirectional Ring, a data packet must traverse through all nodes
   - All computers must be turned on in order for them to connect with one another

## Star Topology

Each device in a star topology has a dedicated point-to-point link to a central controller, which is commonly referred to as the HUB. There is no direct connection between the devices. Traffic between the devices is not allowed in this topology. As an exchange, the controller is used.

![screenshot](Images/Star_Topology.png)

  ## Advantages
   - When attaching or disconnecting devices, there are no network interruptions
   - It’s simple to set up and configure
   - Identifying and isolating faults is simple
   - Less Expensive than mesh 
   - Easy to install & configure
  ## Disadvantages
   - Nodes attached to the hub, switch, or concentrator is failed if they fail
   - Because of the expense of the hubs, it is more expensive than linear bus topologies
   - More cable is required compared to a bus or ring 
   - Too much dependency on Hub

## Mesh Topology

Every device in a mesh topology has dedicated point-to-point connectivity to every other device. The term “dedicated” refers to the fact that the link exclusively transports data between the two devices it links. To connect n devices, a fully connected mesh network contains n *(n-1)/2 physical channels.

![screenshot](Images/Mesh_Topology.png)
  ## Advantages
   - Data can be sent from multiple devices at the same time. This topology can handle a lot of traffic.
   - Even if one of the connections fails, a backup is always available. As a result, data transit is unaffected.
   - Physical boundaries prevent other users from gaining access to messages.
   - Point to Point links make fault transmission & fault isolation easy.
  ## Disadvantages
   - The amount of cabling and the number of I/O ports that are necessary.
   - The sheer bulk of wiring can be greater than the available space can accommodate.
   - It is difficult to install and reconfigure.

## Tree Topology

The topology of a tree is similar to that of a star. Nodes in a tree, like those in a star, are connected to a central hub that manages network traffic. It has a root node, which is connected to all other nodes, producing a hierarchy. Hierarchical topology is another name for it. The number of Star networks is connected via Bus in Tree Topology.

![screenshot](Images/Tree_Topology.png)

  ## Advantages
   - Network expansion is both possible and simple.
   - We partition the entire network into pieces (star networks) that are easier to manage and maintain.
   - Other segments are unaffected if one segment is damaged.
  ## Disadvantages
   - Tree topology relies largely on the main bus cable because of its basic structure, and if it fails, the entire network is    handicapped.
   - Maintenance becomes more challenging when more nodes and segments are added.




