# Networking Fundamentals

A structured collection of networking notes, guides and resources built as part of an ongoing cloud computing learning journey. This repository is focused on making foundational networking concepts clear, practical and easy to reference.

## Contents

| File | Description |
|------|-------------|
| [DNS Beginner Guide](./DNS%20Beginner%20guide.pdf) | A comprehensive illustrated guide to the Domain Name System covering DNS records, the lookup process, hierarchy, caching and security |
| [Computer Networks Guide](./Computer_networks_guide.pdf) | A beginner's complete guide to computer networks covering network types, devices, topologies, wired vs wireless, terminology, packet switching and an introduction to the OSI model |
| [IP Addressing](./IP%20ADDRESSING.pdf) | Full coverage of IPv4 and IPv6 structure, address classes, private ranges, subnet masks, CIDR notation, subnetting, NAT and IP addressing in Azure |
| [The Binary Number System](./The%20Binary%20Number%20System.pdf) | A focused guide to binary arithmetic as it applies to IP addressing, including decimal to binary conversion, octet place values, address classification and quick identification hacks |
| [Exercises on Binary Conversion](./Exercises%20on%20Binary%20Conversion.pdf) | Practical exercises covering decimal-to-binary conversion, binary-to-decimal conversion, IP address classification, network and host identification, and public vs private address determination |
| [CIDR Notation and Subnet Masks](./CIDR%20Notation%20and%20Subnet%20Masks.pdf) | A comprehensive guide to CIDR notation and subnet masks covering conversions, host calculations, address ranges, network addresses, broadcast addresses and subnetting fundamentals |
| [The OSI Model](./THE%20OSI%20MODEL.pdf) | A complete guide to all seven OSI layers covering protocols, port numbers, TCP vs UDP, encapsulation, troubleshooting methodology and where Azure services map to each layer |

## Topics Covered

### Domain Name System (DNS)

- What DNS is and why it exists
- Anatomy of a domain name (TLD, SLD, subdomain, FQDN)
- The DNS lookup process, step by step
- DNS hierarchy: Recursive Resolver, Root NS, TLD NS, Authoritative NS
- DNS record types: A, AAAA, CNAME, MX, NS, TXT
- DNS caching and TTL
- DNS security: spoofing, hijacking, DNSSEC and trusted resolvers

### Computer Networks

- What a computer network is and why networks exist
- Network types by size: PAN, LAN, MAN and WAN
- Key networking devices: hub, switch, router, access point, modem, firewall and server
- Network topologies: Bus, Star, Ring, Mesh and Hybrid with diagrams, advantages, disadvantages and real-world use cases
- Wired vs wireless networking comparison
- Essential networking terminology: IP address, MAC address, bandwidth, latency, protocol, DNS, DHCP, packets and Wi-Fi
- How data travels across a network using packet switching

### IP Addressing

- IPv4 structure: octets, binary representation, network vs host portions
- IPv4 address classes (A through E) with first octet ranges, subnet masks and host limits
- Private IP address ranges defined by RFC 1918
- The loopback address (127.0.0.1) and its purpose
- Subnet masks explained in binary and decimal
- CIDR notation and how it replaced the class system
- Practical subnetting example: dividing 192.168.10.0/24 into four equal /26 subnets
- IPv6: 128-bit address format, shortening rules and address types (unicast, multicast, anycast)
- IPv4 vs IPv6 side-by-side comparison
- Network Address Translation (NAT): Static NAT, Dynamic NAT and PAT/NAT Overload
- IP addressing in Azure: VNets, subnets, NAT Gateway, Load Balancer and Azure Bastion

### Binary Number System

- Why computers use binary and what 0 and 1 represent physically
- The 8-bit place value table and why the maximum octet value is always 255
- Step-by-step decimal to binary conversion using repeated division by 2
- Full worked example: converting 192.168.10.5 to binary across all four octets
- How to identify IP address class from the first octet alone
- Four quick identification hacks for classifying any IP address at a glance
- Special addresses to memorize: loopback (127.0.0.1), APIPA (169.254.x.x) and broadcast (255.255.255.255)
- A validity check method for spotting invalid IP addresses instantly

### Binary Conversion Exercises

- Decimal-to-binary conversion exercises with worked solutions
- Binary-to-decimal conversion exercises
- Identifying Class A, B and C IP addresses from decimal and binary formats
- Determining network and host portions of IP addresses
- Public vs private IP address identification exercises
- Practical scenarios designed to reinforce binary arithmetic and IP addressing concepts
- Hands-on exercises that prepare learners for subnetting and CIDR calculations

### CIDR Notation and Subnet Masks

- Understanding the relationship between network and host portions of an IPv4 address
- Subnet masks in binary and dotted-decimal notation
- CIDR notation fundamentals and why CIDR replaced classful networking
- Converting subnet masks to CIDR notation
- Converting CIDR notation to subnet masks
- Binary reference tables for common subnet mask values
- Calculating host bits, total addresses and usable hosts
- Determining network addresses and broadcast addresses
- Calculating usable host ranges
- Full address range analysis using a 192.168.10.0/26 network
- Understanding how subnetting affects network size and address allocation
- Key subnetting concepts used in enterprise and cloud networking

### OSI Model

- All seven layers at a glance with plain-English descriptions
- Layer 7 Application: HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS, SSH, Telnet, SNMP with port numbers
- Layer 6 Presentation: translation, encryption/decryption (TLS/SSL) and compression
- Layer 5 Session: establishment, maintenance, termination and checkpointing
- Layer 4 Transport: TCP vs UDP, port numbers and the TCP three-way handshake
- Layer 3 Network: IP addressing, routing, ICMP, OSPF and BGP
- Layer 2 Data Link: MAC addresses, switches, ARP, Ethernet and Wi-Fi standards
- Layer 1 Physical: cables, connectors, wireless bands, hubs and repeaters
- Encapsulation and decapsulation with PDU table
- OSI vs TCP/IP model comparison
- Complete port reference table
- Systematic bottom-up troubleshooting methodology
- Where Azure services map to OSI layers: VNet, NSGs, Load Balancer, Application Gateway, Azure Firewall, DNS, VPN Gateway and ExpressRoute

## About This Repository

This repository is part of a broader effort to document and share cloud and networking knowledge publicly. Notes are written to be accessible to beginners while remaining technically accurate and useful as reference material for practitioners.

More topics will be added over time including routing, switching, VLANs, subnetting practice labs, load balancing, VPNs and cloud networking concepts on Azure and AWS.

## Connect

If you find any of this useful or have suggestions, feel free to open an issue or connect on [LinkedIn](https://www.linkedin.com/in/divine-uzor).

*Learning in public. Building in the open.*
