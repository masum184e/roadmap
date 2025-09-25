# System Design Learning Roadmap

## 1. Fundamentals
- What is System Design?  
- Functional vs Non-functional requirements  
- Monolithic vs Microservices architecture
- Scalability, Reliability, Availability, Maintainability

## 2. Networking Basics
- DNS, IP, TCP/UDP, HTTP/HTTPS  
- Load Balancers (L4 vs L7)  
- Reverse Proxy vs Forward Proxy  
- CDN (Content Delivery Network)  

## 3. Storage & Databases
- SQL vs NoSQL databases
- Relational databases (MySQL, PostgreSQL)
- Document stores (MongoDB, CouchDB)
- Key-value stores (Redis, DynamoDB)
- Wide-column stores (Cassandra, HBase)  
- Time-series databases (InfluxDB, TimescaleDB)  
- Database indexing & sharding  
- Replication & Partitioning  

## 4. Caching
- Client-side caching (browser, CDN)  
- Server-side caching (Redis, Memcached)  
- Cache invalidation strategies (LRU, LFU)  
- Write-through, Write-back, Write-around  

## 5. Messaging & Communication
- Message queues (RabbitMQ, ActiveMQ)  
- Distributed log systems (Kafka, Pulsar)  
- Publish/Subscribe vs Point-to-Point  
- Event-driven architecture  

## 6. Scalability Concepts
- Horizontal vs Vertical scaling  
- Stateless vs Stateful services  
- Database scaling (sharding, replication)  
- CAP theorem & PACELC theorem  
- Consistency models (strong, eventual, causal)  

## 7. Distributed Systems
- Leader election  
- Consensus algorithms (Paxos, Raft, ZAB)  
- Clock synchronization (NTP, Lamport clocks, Vector clocks)  
- Quorum-based systems  
- Distributed transactions & 2PC/3PC  

## 8. Reliability & Fault Tolerance
- Failover & redundancy  
- Circuit breakers & retries  
- Data replication strategies  
- Backups & disaster recovery  
- Chaos engineering  

## 9. API Design
- REST APIs (resource design, versioning)  
- GraphQL basics  
- gRPC & Protocol Buffers  
- API Gateway patterns  

## 10. Observability & Monitoring
- Logging (structured logs, ELK stack)  
- Metrics & Monitoring (Prometheus, Grafana)  
- Distributed tracing (Jaeger, OpenTelemetry)  
- Alerts & incident response  

## 11. Security
- HTTPS & TLS  
- Authentication & Authorization (OAuth 2.0, JWT)  
- Rate limiting & throttling  
- OWASP top 10 vulnerabilities  
- Zero Trust architecture  

## 12. Advanced Concepts
- Microservices vs Service-Oriented Architecture (SOA)  
- Event sourcing & CQRS  
- Saga pattern for distributed transactions  
- API rate limiting with token bucket/leaky bucket  
- Blue-Green & Canary deployments  
- Feature flags & A/B testing  

## 13. Design Patterns in System Design
- Singleton, Factory, Observer (for services)  
- Database patterns (sharding, federation, materialized views)  
- Resiliency patterns (circuit breaker, bulkhead, retry)  
- Proxy & Gateway patterns  

## 14. Case Studies (Practice System Design)
- Design a URL shortener (TinyURL/Bitly)  
- Design a social media feed (Twitter, Facebook)  
- Design a chat system (WhatsApp, Slack)  
- Design a video streaming service (YouTube, Netflix)  
- Design an e-commerce platform (Amazon, Flipkart)  
- Design a ride-hailing app (Uber, Lyft)  
- Design a payment system (PayPal, Stripe)  
