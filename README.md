# Head First Computer Network

English &nbsp; | &nbsp; [Chinese](./README.zh-CN.md)

## Computer Networks and the Internet

### Concepts

- Computer Network: A collection of interconnected, autonomous computers, classified by coverage into wide area networks, metropolitan area networks, local area networks, and personal area networks.
- Node: Host nodes and data exchange nodes (switches, routers, etc. packet switching devices).
- Communication Link: Access network links and backbone links.
- Entity: Any hardware or software process that can send or receive information.
- Peer Entity: Entities at the same layer that send and receive information.
- Service Access Point: A logical interface for exchanging information between adjacent entities in two layers of the same system, used to distinguish different types of services.
- Protocol Data Unit: Data packets transmitted between peer layers.
- Service Data Unit: Data packets exchanged between layers within the same system.

> Internet: A general term for a network formed by interconnecting multiple computer networks.

> The Internet refers to the specific computer network that is currently the largest and open globally, formed by the interconnection of numerous networks.

### Composition

> Internet/ISP Structure

#### Network Edge

Host Communication Modes:

- Client/Server Mode
- Peer-to-Peer Mode

#### Network Core

Switching: Dynamically allocating transmission line resources in a certain way.

Switching Methods:

- Circuit Switching: The method used by telephone exchanges to connect phone lines, where line resources are exclusively used.
- Packet Switching: Suitable for burst data transmission, with queuing delays and losses.
- Message Switching.

> Routing: Determines the path taken by packets from source to destination.

Router: **Store-and-Forward** packets.

#### Access Network

- Residential Access
- Organizational Access
- Wireless Access

### Performance

| Metric   | Description   |
| -----     |  -----  |
| Rate   | The speed at which hosts connected to a computer network transmit **bits** over a digital channel, measured in bit/s. |
| Bandwidth  | The **maximum data rate** that can be transmitted from one point to another in a network within a unit of time. |
| Throughput | The amount of data transmitted through a network (or channel, interface) in a unit of time. |
| Delay  | Sending delay, propagation delay, queuing delay, and processing delay. |
| Delay-Bandwidth Product | Propagation delay x Bandwidth  | 
| Round-Trip Time | RTT |
| Packet Loss Rate  | The ratio of the number of packets lost during transmission to the total number of packets over a certain time period. |
| Utilization | Channel utilization and network utilization. |

### Layering

> Protocol: Defines the message format and order exchanged between two or more peer **communication entities**, as well as the actions taken during message transmission and reception.

Three Elements of Protocol: Syntax, Semantics, and Synchronization.

OSI Model:

- Application Layer
- Presentation Layer
- Session Layer
- Transport Layer
- Network Layer
- Data Link Layer
- Physical Layer

TCP/IP Model:

- Application Layer
- Transport Layer
- Internet Layer
- Network Interface Layer

> TCP/IP Protocol Suite

### History

> Internet Standardization: [RFC](https://www.ietf.org/rfc/) and IETF

1. 1960 ~ 1980: Development from a single network ARPANET to the Internet (network of networks).
2. 1980 ~ 1990: Three-tier structure of the Internet.
3. 1990 ~ Present: Multi-tier ISP (Internet Service Provider) structure of the Internet.

## Application Layer

### HTTP

> Message

### FTP

### Telnet

### SMTP

### DNS

Domain Names: Root domain, top-level domain, and second-level domain.

### DHCP

### POP3

## Transport Layer

### TCP

Connection-oriented service:

- Reliable, in-order data delivery.
- Flow control.
- Congestion control.

> TCP Segment

### UDP

Connectionless service:

- Unreliable.
- No flow control.
- No congestion control.

> UDP User Datagram

## Network Layer: Data Plane

> IP Datagram

## Network Layer: Control Plane

## Data Link Layer and Local Area Network

> Frames and Bit Streams

## Network Security

## Wireless and Mobile Networks

## Multimedia Networks

## Network Management

## Appendix

