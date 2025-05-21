# TCP-IP-Model

The TCP/IP Model (Transmission Control Protocol/Internet Protocol) is a 4-layer networking model designed by the U.S. Department of Defense in the 1970s. It serves as the foundation of the modern Internet.

#### ✅ Purpose: Defines how data is sent, addressed, transmitted, routed, and received between devices.

![TCP/IP](https://networkwalks.com/wp-content/uploads/2020/10/TCP-Model-3.png)

## 🔍 Detailed Layer-by-Layer Breakdown
### 🔹 Layer 4: Application Layer
Role: Interface between user applications and the network.

##### Functions:

Provides network services to applications (e.g., browsers, email clients)

Handles high-level protocols

##### Examples of Protocols:

HTTP/HTTPS – Web browsing

FTP – File Transfer

SMTP, POP3, IMAP – Email

DNS – Domain name resolution

Telnet, SSH – Remote access

### 🔹 Layer 3: Transport Layer
Role: Provides communication services directly to the application layer.

##### Functions:

Ensures reliable (or unreliable) transmission of data

Manages segmentation, flow control, error handling

#### Key Protocols:

TCP (Transmission Control Protocol) – Reliable, connection-oriented

UDP (User Datagram Protocol) – Fast, connectionless, best-effort delivery

### 🔹 Layer 2: Internet Layer
Role: Handles addressing, routing, and packaging data for transmission.

#### Functions:

Logical addressing using IP

Packet routing across networks

Error reporting and diagnostics

#### Key Protocols:

IP (Internet Protocol) – IPv4, IPv6

ICMP (Internet Control Message Protocol) – Ping, traceroute

ARP (Address Resolution Protocol) – Maps IP to MAC address

### 🔹 Layer 1: Network Access Layer (Link Layer)
Role: Responsible for how data is physically sent over the network.

#### Functions:

Encodes data into signals

Handles MAC addressing and error detection at the hardware level

#### Examples of Technologies:

Ethernet

Wi-Fi (IEEE 802.11)

DSL, Fiber

Hubs, switches, NICs
