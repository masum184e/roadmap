# Socket Programming Learning Path  

## 1. Networking Fundamentals  
- What is a **network** (LAN, WAN, Internet)  
- **IP Addressing** (IPv4 vs IPv6)  
- **Ports** and their role in communication  
- **TCP vs UDP** protocols  
- **DNS** basics  
- **Client-Server model**  
- **HTTP vs WebSocket** vs raw TCP/UDP  

## 2. 🔌 Basics of Sockets  
- What is a **socket**?  
- Types of sockets:  
  - **Stream (TCP)**  
  - **Datagram (UDP)**  
- Socket lifecycle:  
  - **Create → Bind → Listen → Accept → Connect → Send/Recv → Close**  
- Blocking vs Non-blocking sockets  

## 3. Low-Level Socket Programming  
- Using `socket()` in different languages (C, Python, Node.js, etc.)  
- **Server-side socket setup**  
- **Client-side socket connection**  
- Reading and writing data with sockets  
- Error handling (timeouts, disconnections)  

## 4. Advanced Socket Concepts  
- **Socket options** (`setsockopt`, buffer size, keepalive, etc.)  
- **Asynchronous / Non-blocking I/O**  
- **Multiplexing** (select, poll, epoll, kqueue)  
- **Threaded vs Event-driven** servers  
- Handling **multiple clients**  

## 5. Security & Reliability  
- **TLS/SSL** with sockets  
- **Encryption & Authentication**  
- **Firewall & NAT traversal**  
- **Error recovery & retransmission**  

## 6. Real-World Implementations  
- **Chat application** with sockets  
- **File transfer** via sockets  
- **WebSocket server/client**  
- **UDP-based real-time apps** (VoIP, gaming)  

## 7. Performance & Scaling  
- **Connection pooling**  
- **Load balancing**  
- **Optimizing buffer sizes**  
- **Handling high concurrency** (thousands of connections)  

## 8. Tools & Debugging  
- `netstat`, `ss`, `lsof`  
- `tcpdump`, `wireshark`  
- Testing with `telnet` / `nc` (netcat)  
- Simulating packet loss / delay  

## 9. Protocols & Standards (Optional Advanced)  
- **HTTP/1.1, HTTP/2, HTTP/3 (QUIC)**  
- **WebSocket protocol (RFC 6455)**  
- **MQTT** (IoT messaging)  
- **gRPC** over HTTP/2  
- **Custom binary/text protocols**
