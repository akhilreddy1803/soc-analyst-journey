# OSI Model

## What is OSI Model?
OSI (Open Systems Interconnection) model explains how data travels between systems in a network. Each layer performs a specific function.

---

## 7 Layers of OSI Model

### 1. Physical Layer
- Transmits raw bits over physical medium (signals)
- Works with electrical, optical, or radio signals
- **Examples:** Ethernet cables, wireless signals
- **Devices:** Hubs, cables, antennas

---

### 2. Data Link Layer
- Responsible for communication within the same network
- Uses MAC addressing and frame transmission
- Performs error detection
- **Examples:** Ethernet (IEEE 802.3), Wi-Fi (IEEE 802.11)
- **Devices:** Switches, NICs, bridges

---

### 3. Network Layer
- Responsible for routing packets between networks
- Uses IP addressing
- **Examples:** IPv4, IPv6, ICMP
- **Devices:** Routers, Layer 3 switches

---

### 4. Transport Layer
- Provides end-to-end communication
- Ensures reliable or fast delivery
- Uses port numbers
- **Examples:** TCP, UDP, SCTP

---

### 5. Session Layer
- Manages sessions between applications
- Handles connection setup and termination
- **Examples:** NetBIOS, RPC

---

### 6. Presentation Layer
- Responsible for data formatting and encryption
- Handles encryption and compression
- **Examples:** TLS/SSL

---

### 7. Application Layer
- Interface between user and network
- Provides services like web, email
- **Examples:** HTTP, FTP, SMTP, DNS

---

## Real Example
When a user opens a website:
- Data moves through all OSI layers
- Each layer processes data step by step
- Server responds back through same layers

---

## Why OSI Model is Important?
- Helps understand network communication
- Useful for troubleshooting issues
- Used in cybersecurity and SOC analysis

---

## Conclusion
OSI model helps in understanding how data flows in a network and is very useful for learning networking concepts.
