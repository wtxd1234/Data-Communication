# Tutorial 1
## TCP/IP Concepts Review

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/704d6671-0d81-4499-9420-2a1475bba6ef)

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/5fdb8d35-7a89-477c-9220-83bc69f4873b)


## TCP vs UDP

| TCP | UDP |
| :--- | :--- |
| Connection-oriented protocol | Connectionless protocol |
| Suited for applications that require high reliability, and transmission time is relatively less critical | Suitable for applications that need fast, efficient transmission, such as games. UDP's stateless nature is also useful for servers that answer small queries from huge numbers of clients |
| HTTP, HTTPs, FTP, SMTP, Telnet | DNS, DHCP, TFTP, SNMP, RIP, VOIP |
| Rearranges data packets in the order specified | no inherent order as all packets are independent of each other |
| Does Flow Control. TCP handles reliability and congestion control | Does not have an option for flow control |
| Guarantee that the data transferred remains intact and arrives in the same order in which it was sent. | No guarantee that the messages or packets sent would reach at all. |


![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/fbb01667-6b4c-4544-930d-52d52f4cd6f6)


## IPV4 vs IPV6

|  | IPV4 | IPV6 |
| :--- | :--- | :--- |
| No. of bits on IP Address | 32 | 128 |
| Format | Decimal | Hexadecimal |
| Capable of Addresses | 4.3 billion | infinite |
| How to ping? | ping XXX.XXX.XXX | ping6 |

Advantages of IPv6 over IPv4:
1. IPv6 __simplified the router’s task__ compared to IPv4.
2. IPv6 is __more compatible to mobile networks__ than IPv4.
3. IPv6 allows for __bigger payloads__ than what is allowed in IPv4.
4. IPv6 is used by __less than 1% of the networks__, while IPv4 is still in use by the remaining 99%.


![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/8ada8f8b-4c9b-4f74-acd7-3e958e0d560b)


# Network Topologies and Types

## 1. Bus Topology
- **Description**: Used for small, cheap, temporary networks not relying on high data-transfer speeds.
- **Example**: Ethernet LAN with devices connected to a single coaxial or twisted pair cable.

## 2. Star Topology
- **Usage**: Common in home networks, institutes, airports, hospitals, and banks.
- **Advantages**: Effective for local area networks.

## 3. Ring Topology
- **Application**: Local and wide area networks, and in the telecommunication industry.
- **Example**: Small office networks with few nodes.

## 4. Mesh Topology
- **Type**: Partial mesh topology.
- **Usage**: Peripheral networks connected to a full meshed backbone, like in transportation systems.

## 5. Fully-connected Mesh Topology
- **Applications**: Home automation, traffic control, smart home systems (IoT) with interconnected devices.

# Network Types

## 1. Packet-switch Network
- **Function**: Data is broken into packets for transmission.
- **Usage**: Internet data transmission, video streaming.

## 2. Circuit-switch Network
- **Operation**: Establishes a dedicated communication path between two parties for a call.
- **Common Use**: Traditional telephony, Public Switched Telephone Network (PSTN).

## 3. Virtual Circuit Network
- **Description**: A compromise between circuit switching and packet switching.
- **Usage**: Frame Relay for data transmission.

# TCP/IP Fundamentals

## TCP (Transmission Control Protocol)
- **Nature**: Connection-oriented, reliable, suited for applications needing high reliability.
- **Function**: Data packet rearrangement, flow control, sliding window mechanism.
- **Examples**: HTTP, HTTPS, FTP, SMTP, Telnet.

## UDP (User Datagram Protocol)
- **Nature**: Connectionless, suitable for fast, efficient transmission like in games.
- **Characteristics**: Stateless, does not guarantee reliable delivery, no flow control.
- **Examples**: DNS, DHCP, TFTP, SNMP, RIP, VOIP.

# Networking Concepts and Review Questions

## Networking Terms
- **Datagram**: A self-contained, independent packet with information like source and destination addresses.
- **Packet**: A unit of data in a network, carrying user data or control information.
- **Segment**: Used in TCP/UDP, includes data payload and control information.
- **Fragments**: Smaller pieces of a larger data packet, fitting within the network's MTU.
- **Socket**: An endpoint for network communication, using TCP/UDP, identified by an IP address and port number.
- **Byte Stream**: A continuous sequence of bytes in a network, ensuring ordered transmission.
- **Bit Stream**: The smallest unit of data transmission, used in both TCP and UDP.

## Review Questions
### 1. Network Access Layer Function
- **Purpose**: Enables physical transmission of data over a network medium, addressing devices on the same network segment.

### 2. Transport Layer Tasks
- **Functions**: Segmentation of data, error detection and correction, flow control, reliable and ordered delivery.

### 3. Protocol Definition
- **Explanation**: A set of rules for formatting, transmitting, receiving, and processing data in a communication network.

### 4. Protocol Data Unit (PDU)
- **Description**: A unit of data defined and processed at a specific layer of the OSI or TCP/IP model.

### 5. Protocol Architecture
- **Nature**: A conceptual framework standardizing network communication into layers for modular design and interoperability.

### 6. TCP/IP Overview
- **Description**: A suite of communication protocols for connecting devices and networks on the internet.

### 7. Advantages of TCP/IP Layering
- **Benefits**: Modularity, scalability, easier design, implementation, and troubleshooting.

### 8. Router Function
- **Role**: Connects different networks and routes data packets between them.

### 9. IP Version Prevalence
- **Current State**: IPv4 is most prevalent, with growing adoption of IPv6.

### 10. Internet Traffic and TCP
- **Observation**: Not all internet traffic uses TCP; UDP is also used for low-latency communication.

### 11. IPv4 vs. IPv6 Address Space
- **IPv4**: 32-bit address space with approximately 4.3 billion addresses.
- **IPv6**: 128-bit address space, providing a significantly larger number of addresses.
