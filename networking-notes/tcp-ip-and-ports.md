# TCP/IP Model and Ports

## What is TCP/IP Model?
TCP/IP (Transmission Control Protocol / Internet Protocol) is a practical networking model used in real-world communication (Internet).

---

## 4 Layers of TCP/IP Model

### 1. Application Layer
- Combines OSI Application, Presentation, and Session layers
- Interface between user and system
- **Examples:** HTTP, FTP, SMTP, DNS

---

### 2. Transport Layer
- Provides end-to-end communication between hosts
- Uses port numbers
- **Protocols:** TCP, UDP

---

### 3. Internet Layer
- Responsible for IP addressing and routing
- Similar to OSI Network Layer
- **Protocols:** IP, ICMP

---

### 4. Network Access Layer
- Handles physical transmission of data
- Combines Data Link + Physical layers
- **Examples:** Ethernet, Wi-Fi

---

## TCP vs UDP

### TCP
- Connection-oriented
- Reliable data transfer
- Uses 3-way handshake
- Slower but accurate

### UDP
- Connectionless
- Faster but unreliable
- No guarantee of delivery

---

## Port Numbers

There are 3 types of ports:

- **Well-known ports (0–1023)** → Common services  
- **Registered ports (1024–49151)** → Applications  
- **Dynamic ports (49152–65535)** → Temporary use  

---

## Common Ports and Protocols

| Port | Protocol | Description |
|------|----------|------------|
| 20/21 | FTP | File transfer |
| 22 | SSH | Secure remote login |
| 25 | SMTP | Email sending |
| 53 | DNS | Domain to IP resolution |
| 67/68 | DHCP | IP address assignment |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |
| 110 | POP3 | Email retrieval |
| 143 | IMAP | Email retrieval |
| 445 | SMB | File sharing |
| 389 | LDAP | Directory services |
| 3389 | RDP | Remote desktop |
| 123 | NTP | Time synchronization |
| 3306 | MySQL | Database service |

---

## Conclusion
TCP/IP model is used in real-world networking.  
TCP ensures reliable communication, while UDP provides faster communication.  
Ports help identify different services running on a system.
