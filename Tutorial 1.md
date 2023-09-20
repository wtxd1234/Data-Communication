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

