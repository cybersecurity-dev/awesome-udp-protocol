<div align="center">
  
```mermaid
mindmap
  root((UDP Protocol))

    Overview
      User Datagram Protocol
      Transport Layer
      Connectionless
      Best Effort Delivery

    Characteristics
      No Handshake
      No Reliability
      No Retransmission
      No Flow Control
      No Congestion Control

    Header Fields
      Source Port
      Destination Port
      Length
      Checksum

    Advantages
      Low Latency
      Fast Transmission
      Lightweight
      Low Overhead

    Disadvantages
      Packet Loss
      Out of Order Delivery
      No Acknowledgment
      No Error Recovery

    Applications
      DNS
      DHCP
      SNMP
      TFTP
      VoIP
      Online Gaming
      Video Streaming

    Security Risks
      UDP Flood
      Amplification Attacks
      Reflection Attacks
      Spoofing

    Detection
      NetFlow
      IPFIX
      Wireshark
      Zeek
      Suricata
```
# **`Awesome`** [UDP](https://wikipedia.org/wiki/User_Datagram_Protocol) Protocol [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]() 
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
graph LR

    Lnk[Link] --> Inter[Internet]
    Inter --> Trans[Transport]
    Trans --> App[Application]

    %% Styling
    classDef default fill:#f4f4f4,stroke:#333,stroke-width:1px,color:#4a7ebb,font-weight:bold,font-size:20px;
    classDef highlighted fill:#4a7ebb,stroke:#2a5e9b,stroke-width:1px,color:#fff,font-weight:bold,font-size:20px;

    class App,Inter,Lnk default;
    class Trans highlighted;
```
## 📖 Contents
- [UDP Libraries](#udp-libraries)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)




```mermaid
sequenceDiagram

participant Client
participant Server

Client->>Server: UDP Datagram 1
Client->>Server: UDP Datagram 2
Client->>Server: UDP Datagram 3

Note over Client,Server: No connection establishment

Server-->>Client: UDP Response

Note over Client,Server: No ACK required
```

## UDP Libraries

- [Handshaked UDP](https://github.com/kewl-ua/handshaked_udp) - C library for bidirectional UDP sessions between a client behind CGNAT and a public server, with keep-alives, connection migration and automatic reconnection.

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-udp-protocol/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-udp-protocol-)
