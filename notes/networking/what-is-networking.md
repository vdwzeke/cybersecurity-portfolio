# What Is Networking?

## 1. What Is a Network?

A **network** is a group of devices connected to communicate and share resources.

- **Private network:** Used within a home or organisation.
- **Public network:** Accessible to the public, such as the internet.
- **Internet:** A global network of interconnected networks.

The **World Wide Web (WWW)** is a service that operates over the internet, allowing users to access websites and web pages.

## 2. IP Addresses

An **IP address** identifies a device's network interface and enables communication across networks.

- **IPv4:** Uses 32-bit addresses, such as `192.168.1.10`.
- **IPv6:** Uses 128-bit addresses, providing a much larger address space.
- **Public IP:** Used for communication over the internet.
- **Private IP:** Used within private networks and commonly accesses the internet through Network Address Translation (NAT).

Private IPv4 ranges include `10.0.0.0/8`, `172.16.0.0/12`, and `192.168.0.0/16`.

## 3. MAC Addresses

A **MAC address** identifies a network interface at the data-link layer. It is typically represented as six hexadecimal pairs, such as `00:1A:2B:3C:4D:5E`.

- **IP address:** Used for logical addressing and routing.
- **MAC address:** Used for local network delivery.
- **MAC spoofing:** Changing or impersonating a device's MAC address.

## 4. Ping and ICMP

`ping` tests whether a destination responds to network requests. It uses **ICMP (Internet Control Message Protocol)**.

Example:

```bash
ping 192.168.1.1
```

Results can help identify connectivity issues and measure response time. However, a failed ping does not necessarily mean the destination is offline; a firewall may block ICMP traffic.

## Key Takeaways

- Networks allow devices to communicate and share resources.
- IP addresses enable network addressing and routing.
- MAC addresses support communication on local networks.
- Ping uses ICMP to test connectivity.
- Understanding networking is essential for troubleshooting and cybersecurity.
