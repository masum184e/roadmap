# RabbitMQ Learning Roadmap

## [1. Introduction](#)
- [What is RabbitMQ?](#)
- [Message Brokers vs Queues](#)
- [AMQP protocol basics](#)
- [When & Why to use RabbitMQ](#)

## [2. Core Concepts](#)
- [Producer, Consumer](#)
- [Queue](#)
- [Exchange](#)
  - [Direct](#)
  - [Fanout](#)
  - [Topic](#)
  - [Headers](#)
- [Binding & Routing Keys](#)
- [Message Acknowledgements (Ack, Nack, Reject)](#)

## 3. Setup & Basics
- [Installing RabbitMQ (Docker / Local / Cloud)](#)
- [RabbitMQ Management UI](#)
- Declaring Queues & Exchanges
- Publishing & Consuming Messages
- Auto-delete & Durable Queues
- Persistent Messages

## 4. Message Patterns
- Work Queues (Task Queue)
- Publish / Subscribe
- Routing
- Topics
- RPC (Request-Reply pattern)
- Dead Letter Queue (DLQ)

## 5. Reliability & Durability
- Durable vs Transient Queues
- Message Durability
- Manual vs Auto Acknowledgement
- Prefetch Count (Fair Dispatch)
- Dead Letter Exchanges (DLX)
- Retry Mechanisms

## 6. Advanced Concepts
- Priority Queues
- Delayed Messages
- Message TTL (Time to Live)
- Expired Messages & Dead Lettering
- Alternate Exchanges
- Quorum Queues vs Classic Queues
- Streams (New in RabbitMQ)

## 7. Security
- Users, Virtual Hosts, Permissions
- Authentication & Authorization
- TLS/SSL with RabbitMQ
- Firewalls & Network Security

## 8. Monitoring & Management
- RabbitMQ Management Plugin
- Monitoring Queues, Exchanges, Connections
- Metrics & Health Checks
- Prometheus + Grafana Integration

## 9. Scaling & High Availability
- Clustering in RabbitMQ
- Federation & Shovel
- Mirrored Queues
- Quorum Queues (for HA)
- Load Balancing Producers & Consumers

## 10. Integrations
- RabbitMQ with Node.js
- RabbitMQ with Python
- RabbitMQ with Java (Spring Boot)
- RabbitMQ with .NET
- RabbitMQ in Microservices Architecture
- RabbitMQ with Docker & Kubernetes

## 11. Troubleshooting & Best Practices
- Handling Duplicate Messages (Idempotency)
- Poison Message Handling
- Backpressure & Flow Control
- Common Errors & Fixes
- Performance Tuning

---
✅ Suggested Path:
- **Beginner:** Introduction → Core Concepts → Setup & Basics → Message Patterns  
- **Intermediate:** Reliability & Durability → Advanced Concepts → Security  
- **Advanced:** Scaling & HA → Integrations → Monitoring → Best Practices
