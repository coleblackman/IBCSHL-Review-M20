- [Topic 3](#topic-3)
  - [Network fundamentals](#network-fundamentals)
    - [3.1.1 <mark>Types of networks</mark>](#311-marktypes-of-networksmark)
    - [3.1.2 Standards](#312-standards)
    - [3.1.3 OSI seven layer model](#313-osi-seven-layer-model)
    - [3.1.4 <mark>VPN</mark>](#314-markvpnmark)
    - [3.1.5 Evaluate usage of VPNs](#315-evaluate-usage-of-vpns)
  - [Data transmission](#data-transmission)
    - [3.1.6](#316)
    - [3.1.7 Protocols](#317-protocols)
    - [3.1.8 speed of data transmission](#318-speed-of-data-transmission)
    - [3.1.9 compression of data necessary across a network](#319-compression-of-data-necessary-across-a-network)
    - [3.1.10 Transmission media](#3110-transmission-media)
    - [3.1.11 <mark> Packet Switching </mark>](#3111-mark-packet-switching-mark)
  - [Wireless](#wireless)
    - [3.1.12 Pros/cons of wireless](#3112-proscons-of-wireless)
    - [3.1.13 Components of wireless networks](#3113-components-of-wireless-networks)
    - [3.1.14 Characteristics](#3114-characteristics)
    - [3.1.15 network security](#3115-network-security)
    - [3.1.16 pros/cons of each type](#3116-proscons-of-each-type)

# Topic 3

## Network fundamentals

file sharing; resource sharing; communication; security

### 3.1.1 <mark>Types of networks</mark>

LAN - within a limited area such as school or university campus
VLAN - Group of devices/LANS configured to communicate as if they were attached when in reality they are on separate segments 
WAN - wide area network - extends over a large geographical distance (internet)
SAN - storage area network - consolidated, block level data storage
WLAN - Wireless network (satellite communication)
PAN - computer network used for data transmission; across devices
P2P - distributed architecture that pratitions tasks between peers

### 3.1.2 Standards

 - Enables compatibility
 - Intranet - private internet for users in an organization
 - Extranet - intranet that has been opened to some other users outside the company

### 3.1.3 OSI seven layer model

  1. Physical; transmission of raw bits; Cables
  2. Data Link; data frame transfer between nodes physically; Frames
  3. Network; operation of the subnet; Packets
  4. Transport; ensures messages are in sequence; TCP
  5. Session; Session establishment between processes on different stations; ports
  6. Presentation; Formats data
  7. Application; Program provides to end user

### 3.1.4 <mark>VPN</mark>

VPN - <mark>extends a private network across a public network; benefit to applications running on the VPN of functionality, security, management of the private network; behaves like a private network despite going over public lines (needs more security for that too); reduces cost because it shares lines with other traffic; requires tunneling

### 3.1.5 Evaluate usage of VPNs

- Requires tunneling protocol, VPN software, and encryption protocols (SSL/TLS)
- Cans save money
- Can share resources like data across a public network, acting as a private network

## Data transmission

### 3.1.6 

> Protocol - 
> Data packet - 

### 3.1.7 Protocols

- Ensures interopability
- Standard - agreement about hardware/software for interopability and compatibility
- Protocol - agreed upon **set of rules** for data transfer between devices
  - Protocols can detect packet loss
  - Flow control
  - Prevention of deadlock
  - Detect errors in data transmission
  
### 3.1.8 speed of data transmission

- Varies across a network
- WiFi - short range
- WiMax - high bandwidth, longer range, wireless, 

### 3.1.9 compression of data necessary across a network

- reduces size, faster information spread

### 3.1.10 Transmission media

- Copper vs fiber optic, wireless, etc

### 3.1.11 <mark> Packet Switching </mark>

> Packet - unit of data on a network with header and data
> Packet switching - use of packets for communication; small chunks of data; can take optimal, different routes to the destination; mitigates corruption; full use of available bandwidth; devices of different speeds can communicate
> Circuit switched - data sent in one, ordered sequence; landline phones

## Wireless

### 3.1.12 Pros/cons of wireless

| Pros                                        | Cons                                         |
|---------------------------------------------|----------------------------------------------|
| Reduces need for wires and wired components | Consumes more energy                         |
| Freedom to move around                      | Depends on number of people per access point |
|                                             | Slower                                       |


### 3.1.13 Components of wireless networks

- Wireless router
- Access points
- Wireless repeaters
- Modem - allows connection to upstream cable

### 3.1.14 Characteristics

### 3.1.15 network security

- Usernames, passwords
- Access control
- Firewalls
- Physical device security
- Encryption

### 3.1.16 pros/cons of each type

Hashing - 2 inputs can give the same output 
    - any sequence into a fixed length hash (MD5)
