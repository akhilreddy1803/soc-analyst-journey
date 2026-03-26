# OSI Model

## What is OSI Model?
OSI (Open System Interconnection) model describes how data will traverses through the systems and at every layer will have unique protocols 

## 7 Layers of OSI Model

1. Physical Layer
 - Transmission of raw bits over a physical medium.like electrical, optical or
   radio signals. 
 - No protocols used in this layer 
 - **Examples:** Ethernet cables, wireless radio, hubs, etc.
 - **Devices:** Hubs, cables, antennas.

2. Data Link Layer
 - This layer is used to communicate between two devices on a network.
 - The data wil send in frames from one node to another node and used for MAC Addressing, error
   detection/correction.
 - **Examples:** Ethernet(IEEE 8O2.3), Wi-Fi(IEEE 8O2.11), PPP(point-to-point protocol)
 - **Devices:** switches, NICs, bridges.
  
3. Network Layer
 - This layer is responsible for moving of packets across multiple networks to the destination.
 - Used for IP addressing, routing, packet forwarding.
 - **Examples:** IPv4,IPv6, ICMP, ARP.
 - **Devices:** Routers, layer 3 switches.

4. Transport Layer
 - Reliable (or Unreliable) delivery of data between hosts
 - Used for segmentation, error recovery, multiplexing(ports)
 - **Exmaples:** TCP, UDP, SCTP(Stream control transmission protocol)
 - **Devices:** firewalls 

5. Session Layer
 - Manges sessions or connections between applications -- setup, maintenance and teardown
 - Used for Session Establishmnet, dialog control.
 - **Examples:** RPC(remote procedure call), NetBIOS
  
6. Presentation Layer
 - This layer is responsible for Translation, encryption/decryption, and compressiom fo data
 - Used for Data representation, encryption(TLS/SSL)
 - **Examples:** TLS/SSL handshakes, MIME

7. Application Layer
 - This layer is interface between user applications and the network -- provides network services to the end user direclty.
 - Used for application level protocolsm resource sharing , email
 - **Examples:** HTTP, SMTP, FTP, SSH, DHCP(client side).
 - **Devices:** Web browsers, DNS servers
   
##  Real Example
When opening a website:
 - Data passes through all layers
 - Each layer performs a specific function

## Conclusion
 OSI model helps in unerstand about network communication through the systems  
