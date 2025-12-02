# Essential Topics to Know for WebSockets

## 1. Fundamentals
- What WebSockets are
- Difference between WebSockets and HTTP
- Full-duplex communication
- WebSocket handshake process
- WebSocket protocol (RFC 6455)

## 2. Core Concepts
- Frames (text, binary, ping/pong, close)
- Connection lifecycle (open, message, error, close)
- Subprotocols (e.g., STOMP, MQTT over WebSockets)
- Origin and security considerations

## 3. Client-Side WebSocket
- `WebSocket` API in JavaScript
- Event listeners (`onopen`, `onmessage`, `onerror`, `onclose`)
- Sending and receiving messages
- Handling reconnection logic

## 4. Server-Side WebSocket
- Implementing WebSocket servers (Node.js, Python, Go, Java, etc.)
- Broadcasting messages
- Managing multiple connections
- Heartbeats and ping/pong handling
- Authentication & authorization methods

## 5. Security
- WSS (WebSocket Secure)
- TLS considerations
- Preventing CSRF, XSS, and man-in-the-middle attacks
- Rate limiting / flood protection

## 6. Scalability
- Load balancing WebSockets
- Horizontal scaling challenges
- Using message brokers (Redis Pub/Sub, Kafka)
- Sticky sessions

## 7. Error Handling & Debugging
- Connection drops & auto-reconnect strategies
- Handling network instability
- Logging message flows

## 8. Advanced Concepts
- WebSocket compression (permessage-deflate)
- Binary data formats (protobuf, msgpack)
- Backpressure handling
- Integrating with frameworks (Socket.IO, SignalR, Phoenix Channels)

## 9. Testing & Tools
- WebSocket testing tools (wscat, websocat)
- Browser devtools WebSocket inspector
- Load testing (k6, artillery)

## 10. Use Cases
- Real-time chat
- Live dashboards
- Multiplayer games
- Collaborative editing
- IoT messaging
