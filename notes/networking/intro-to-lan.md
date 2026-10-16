# Intro to LAN

## 1. Network Topologies

A **network topology** describes how devices are arranged and connected within a network.

- **Star:** Devices connect to a central switch or hub. Easy to expand and troubleshoot, but the central device is a single point of failure.
- **Bus:** Devices share a single backbone cable. It is inexpensive to set up but has limited redundancy and can suffer from congestion.
- **Ring:** Devices form a loop and forward data between one another. A cable or device failure can disrupt the network unless redundancy is built in.

## 2. Switches and Routers

- **Switch:** Connects devices within a LAN and forwards Ethernet frames to the appropriate port using MAC addresses.
- **Router:** Connects different networks and forwards packets using IP addresses and routing information.

## 3. Subnetting

**Subnetting** divides a network into smaller networks called subnets.

A subnet mask identifies the network and host portions of an IP address.

Example: `192.168.1.0/24`

- **Network address:** `192.168.1.0` — identifies the subnet.
- **Host address:** `192.168.1.100` — identifies a device within the subnet.
- **Default gateway:** The router address used to reach other networks, often `192.168.1.1`.

Subnetting improves network organisation, address management, and security through network separation.

## 4. Address Resolution Protocol (ARP)

**ARP** maps an IPv4 address to a MAC address on a local network.

1. **ARP Request:** Broadcasts a request asking which device owns a particular IPv4 address.
2. **ARP Reply:** The device responds with its MAC address.
3. The mapping is stored temporarily in the ARP cache for future communication.

## 5. Dynamic Host Configuration Protocol (DHCP)

**DHCP** automatically assigns IP configuration to devices joining a network.

The process follows four steps, commonly remembered as **DORA**:

1. **Discover:** The client searches for a DHCP server.
2. **Offer:** The server offers an IP address.
3. **Request:** The client requests the offered address.
4. **Acknowledge:** The server confirms the assignment.

DHCP reduces the need to configure each device manually.

## Key Takeaways

- Topologies describe how network devices connect.
- Switches connect devices within a LAN; routers connect different networks.
- Subnetting divides networks into smaller subnets.
- ARP maps IPv4 addresses to MAC addresses.
- DHCP automatically assigns IP configuration.
