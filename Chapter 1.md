# Chapter 1: Fundamentals of Communication
## Trends 
Driving forces behind data communications and networking facilities:
1. __Traffic growth__
2. __Development of new services ad application__
3. __Advances in technology__ - faster, cheaper, intelligence, “everything over IP”, mobility

## Notable Trends
`Trend toward faster and cheaper, in both computing and communication`
- More powerful computers supporting more demanding applications
- The __increasing use__ of optical fiber and high-speed wireless has brought transmission __prices down and greatly increased capacity__

`Today’s networks are more “intelligent”`
- __Differing levels of quality of service (QoS)__
- __Variety of customizable services__ in the areas of network management and security

`The Internet, the Web, and associated applications have emerged as dominant features for both business and 
personal network landscapes`
- __"Everything over IP"__
- Intranets and extranets are being used to __isolate隔离 proprietary专有 information信息__

`Mobility`
- __Handheld devices__ have become drivers of the evolution of business networks and their use
- __Cloud computing__ is being embraced接受/使用

## Data Communication vs Networking
- Communication: Two Nodes

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/57eb3be0-048c-4696-8453-e0ac40953575)

- Networking: Two or more nodes

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/78d35c67-adbf-422b-8b39-8cc521df968b)

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/48c6ccc7-8a22-405e-9847-7c2a361c9b87)


## Components of Communication system

1. Source : __generates data__ to be transmitted
2. Transmitter : __Converts data__ into transmittable signals
3. Transmission System: __Carries data__
4. Receiver : __Converts received signal into data__
5. Destination: __Takes incoming data__

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/49a4e217-0f9c-4cf0-bc88-b87a199b1157)

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/80cf7c1d-cb03-4661-a07b-b47229ebf411)

## Key Communications Tasks沟通主要任务
- Transmission System Utilization
- Interfacing
- Signal Generation
- Synchronization
- Exchange Management
- Error detection and correction
- Addressing and routing
- Recovery
- Message formatting
- Security
- Network Management

## Protocol Architecture
- A protocol architecture is __the layered structure of hardware and software that supports the exchange of data between systems and supports distributed applications软硬件信息交换及分布的主要阶层结构__, such as electronic mail and file transfer.
- At each layer of a protocol architecture, __one or more common protocols are implemented实施 in communicating systems__.
- Each protocol __provides a set of rules__ for the exchange of data between systems.
- The __most widely used__ protocol architecture is the __TCP/IP protocol suite__ (TCP includes __HTTP & HTTPS__)
- Another important protocol architecture is the __seven-layer OSI model__

## Why do we need it?
- Data transmission is a __complex task__.
  - Source must __initiate发起/开始 communication__.
  - Source must __make sure the destination is prepared__ to receive data.
  - Application on the source must __make sure the application on the receiver is ready__ to accept
and store.
  - Must __make sure formats are the same__ (little/big endian).
- __Requires coordination协调 and cooperation合作__ between two computer systems.
- Data transmission task is __broken up into subtasks__

## Key Elements of protocols
- Syntax句法/句子结构
  - Data formats
  - Signal levels
- Semantics语义/语言意义
  - Control information
  - Error handling
- Timing
  - Speed matching
  - Sequencing

## Participating agents
Data communications involve 3 agents:
1. Applications
2. Computers
3. Networks

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/2df65a52-f95c-4c04-a409-b25697ee7386)

## Definitions
- Protocol – A protocol is __a set of rules and formats that govern the communication
between communicating peers__. It __allows the peers to agree on a set of valid messages
and the meaning of each message__.
- A service access point (SAP) -- the __interface between the lower and upper layers__.
- Protocol data units (PDUs) -- __packets exchanged between peer entities in the same
layer__.
- Service data units (SDUs) -- __packets handed to a lower layer by an upper layer__.

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/5bbf097c-d8b2-4101-b445-e087c23643cc)

## Service and Protocol Data Units
- Encapsulation: __Each layer adds a header which
contains protocol control information (PCI)__.
- __Header + Service Data Unit (SDU) = Protocol Data Unit (PDU)__

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/6764bcbc-be0d-41c1-ba18-bed54db18a0a)

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/229ff60d-24cc-47a3-a42f-cbb014348794)

## What is in the header?
examples - __not exhaustive详细__
1. __Transport PDU (segments)__ 
  - Source port Destination port
  - Sequence number 
  - Error-detection code (checksum/frame check sequence) 
2. __Network Access PDU (packet)__
  - Source computer address 
  - Destination computer address 
  - IP version

## Flow of Data 

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/231666c8-8920-4b17-b785-83460a48e706)

## History of TCP/IP
- __ARPANET__ (Advanced Research Projects Agency Network ): __Experimental packet-switched network__
- Funded by __DARPA__ (Defense Advanced Research Projects Agency)
- __Vint Cerf__ and __Bob Kahn__ of ARPA started to __develop methods and protocols for
internetworking__.

## Role of each layer

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/7d10a11f-af11-4afe-b595-4712d2f14be3)

## Protocols at each layer

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/18188563-6381-4d58-af72-8427d3a3805e)

## Encapsulation封装/包装

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/cae65e57-b6dc-4938-8198-337c17080b1a)

## Encapsulation Example

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/6683beeb-5623-4653-8e4e-d3f0671d8921)

## Comparison of the OSI and TCP/IP Protocol Architectures
| OSI | TCP/IP |
| --- | --- |
| In OSI, __reference model__ was done before protocols | In TCP, __protocols__ were done before the model|
| __Standardize first, build later__ | __Build first, standardize later__ |
| OSI __took too long to standardize__  | TCP/IP was __already in wide use__ by the time |

![image](https://github.com/wtxd1234/Data-Communication/assets/41671135/1616cc28-ec55-4a08-9139-a75f9e3c96e9)

## Advantages of layered Architecture
- __Less complex__ : Break up a complex problem into __smaller__, more manageable parts __each 
layer solves only part of the problems__.
- __Easier to develop__: Reduced complexity __allows easier program changes and faster 
product development__. Allows implementations to __change without disturbing the rest of 
the stack__. 
- __Shared functionality__ - many __upper layers can share the services provided by a lower 
layer__
- __Multivendor多供应商 interoperability互操作性__: Creating products to meet the same networking 
standards means that __computers and networking gear from multiple vendors can work 
in the same network__
- __Easier to learn__: Humans can __more easily discuss and learn about the many details of a 
protocol specification__
- __Modular engineering__: One vendor can __write software that implements higher layers__. For 
example, __a web browser and another vendor can write software that implements the 
lower layers__. For example, __Microsoft’s built-in TCP/IP software in its OSs__.

