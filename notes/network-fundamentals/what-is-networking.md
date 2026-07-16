# What is Networking?

## Overview
This file introduces the fundamentals of computer networking, including how devices communicate, how they are identified on a network, and the role of IP and MAC addresses. It also covers the purpose of the `ping` utility for testing network connectivity.

## Key Concepts
- A network consists of two or more connected devices that can communicate.
- The Internet is a global network made up of many interconnected private networks.
- Devices are identified using:
  - **IP addresses** – logical addresses used for communication on a network (public or private).
  - **MAC addresses** – unique hardware addresses assigned to network interfaces.
- Public IP addresses identify devices on the Internet, while private IP addresses identify devices within local networks.
- MAC addresses can be spoofed, highlighting the importance of not relying solely on them for security.
- IPv4 provides approximately 4.3 billion addresses, contributing to address exhaustion as Internet-connected devices continue to grow.

## Important Commands / Tools
- `ping <IP address | hostname>` – Tests connectivity to a host and measures network latency using ICMP Echo Requests and Echo Replies.

## Key Takeaways
- Every networked device requires unique identifiers to communicate effectively.
- Understanding the difference between IP and MAC addresses is fundamental to networking and cybersecurity.
- The `ping` command is an essential troubleshooting tool for verifying network connectivity and response times.

## Skills Demonstrated
- Understanding basic networking concepts.
- Identifying the differences between public/private IP addresses and MAC addresses.
- Using the `ping` command to test network connectivity.
