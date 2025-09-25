# gRPC Topics to Learn

## 1. Basics
- What is gRPC (and why use it)
- gRPC vs REST vs GraphQL
- Protocol Buffers (protobuf) basics
  - Defining `.proto` files
  - Messages & fields
  - Services & RPC methods
- Installing and setting up gRPC in a project

## 2. Core Concepts
- Unary RPC
- Server Streaming RPC
- Client Streaming RPC
- Bidirectional Streaming RPC
- Code generation (stubs & clients)

## 3. Protocol Buffers (Advanced)
- Scalar types (int32, string, bool, etc.)
- Enums
- Nested messages
- Repeated fields (lists/arrays)
- Maps
- Oneof
- Reserved fields
- Importing `.proto` files
- Packages & namespaces
- Options (e.g., `deprecated`, custom options)

## 4. gRPC Server & Client
- Creating a gRPC server
- Creating a gRPC client
- Handling requests & responses
- Error handling
- Deadlines & timeouts
- Cancellation

## 5. Authentication & Security
- Transport security (TLS/SSL)
- Authentication mechanisms
  - Token-based auth
  - OAuth2/JWT with gRPC
- Metadata (headers)
- Interceptors for auth

## 6. Middleware / Interceptors
- Unary interceptors
- Streaming interceptors
- Logging, tracing, and monitoring
- Error handling with interceptors

## 7. Advanced Features
- gRPC reflection
- gRPC health checks
- gRPC server load balancing
- gRPC retries
- gRPC deadlines
- Compression

## 8. gRPC in Practice
- gRPC with different languages (Node.js, Go, Python, Java, etc.)
- gRPC-Web (browser support)
- gRPC-Gateway (REST ↔ gRPC bridge)
- Versioning APIs in gRPC
- Backward & forward compatibility with protobuf

## 9. Testing & Debugging
- Using `grpcurl`
- Unit testing gRPC services
- Mocking gRPC clients
- Debugging protobuf messages

## 10. Deployment & Performance
- Streaming for real-time applications
- Connection pooling
- Load balancing strategies
- Observability (metrics, tracing, logging)
- Best practices for schema & service design
