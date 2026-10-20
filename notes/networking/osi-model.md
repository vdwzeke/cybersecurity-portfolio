# OSI Model

## Overview

The **Open Systems Interconnection (OSI) model** is a seven-layer framework that explains how data travels between devices over a network. Each layer has specific responsibilities, helping different systems communicate.

**Encapsulation** occurs when each layer adds relevant information to data as it is prepared for transmission.

## The Seven Layers

| Layer | Name | Main Function |
|---:|---|---|
| 7 | Application | Network services used by applications, such as HTTP and DNS. |
| 6 | Presentation | Data formatting, translation, encryption and compression. |
| 5 | Session | Establishes, manages and terminates communication sessions. |
| 4 | Transport | End-to-end data delivery using TCP or UDP; uses port numbers. |
| 3 | Network | IP addressing and routing packets between networks. |
| 2 | Data Link | Local network delivery using MAC addresses and Ethernet frames. |
| 1 | Physical | Transmits raw bits through cables, radio signals and other physical media. |

## Key Concepts

### TCP vs UDP

- **TCP (Transmission Control Protocol):** Connection-oriented and reliable. Provides ordered delivery, error detection and retransmission when needed. Commonly used for web browsing, email and file transfers.
- **UDP (User Datagram Protocol):** Connectionless with lower overhead. Does not guarantee delivery or ordering. Commonly used for real-time communication, streaming and online gaming.

### Network Devices

- **Layer 2 switch:** Forwards Ethernet frames using MAC addresses.
- **Layer 3 router:** Forwards packets between networks using IP addresses.

### Common Protocols

- **HTTP/HTTPS:** Web communication.
- **DNS:** Resolves domain names to IP addresses.
- **TCP/UDP:** Transport protocols.
- **IP:** Addresses and routes packets between networks.

## Key Takeaways

- The OSI model has seven layers, each with a distinct role.
- Layers 1–3 handle physical transmission, local delivery and routing.
- Layer 4 manages transport between endpoints.
- Layers 5–7 support sessions, data representation and application services.
- Understanding the OSI model helps troubleshoot network problems by identifying which layer may be responsible.
