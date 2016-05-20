# Notes for Pcap 101

### Why
- Troubleshooting
  - Packets don't lie
  - Unless they do (host vs wire)
  - "The network is down..."
- Security
  - Choke points
  - Impartial observation point
  - Encryption challenges
    - Metadata
    - Proxies
    - Pre/post encryption
- Performance Monitoring
  - Packet loss
  - Latency
  - Jitter
  - Retransmits
  - Fragmentation

### How
- Simple host capture
  - Privilege level
- Promiscuous mode
  - Why do we even have promiscuous mode?
- What a switch sees
- What a wifi adapter sees
- Mirror ports
- Taps

### Tools
- Tcpdump
- Wireshark
- Tshark
- Tcpflow
- Bro

### Networking 001
- Encapsulation
- TCP vs UDP
- Fragmentation vs Windowing vs Segmentation
- Disambiguate terms
  - IP protocol field
  - L4 ports
  - Application layer protocol
- Dissect a simple HTTP session running on localhost
- Dissect a more complex HTTP session from real world

