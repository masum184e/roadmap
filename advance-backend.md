# Advance Backend

## 1. Core Programming Languages

- **TypeScript:** Full-stack capability with Node.js; real-time apps (chat, games)
- **gRPC:** Fast binary protocol for microservices and internal APIs
- **OpenAPI/Swagger:** Auto-generated documentation and client/server SDKs
- **Rate Limiting, Throttling:** Protect API from abuse and ensure fair usage
- **Postman:** Test APIs easily
- **Prisma:** Type-safe and auto-generated SQL queries for PostgreSQL, MySQL, etc.
## 2. Databases

- **PostgreSQL:** Advanced RDBMS; used for structured data, complex queries
- **MySQL / MariaDB:** Popular, simple relational DB for small to large apps
- **MongoDB:** NoSQL, document-based; great for dynamic schemas (e.g., user profiles, blogs)
- **Redis:** In-memory cache; also supports pub-sub and streams

Concepts like indexing, normalization, and ACID compliance ensure data consistency, performance, and scalability.

## 3. Security

| Technology / Concept      | Use                                       |
| ------------------------- | ----------------------------------------- |
| **JWT, OAuth2, Sessions** | Authenticate and authorize users securely |
| **CORS, CSRF, XSS, SQLi** | Prevent common web attacks                |
| **HTTPS, TLS, HSTS**      | Secure data in transit                    |
| **bcrypt, Argon2**        | Secure password hashing                   |
| **Security Headers**      | Prevent browser-based exploits            |

## 4. Architecture

- **Event-Driven Architecture:** React to real-time changes (e.g., user signups, payments)

## 5. Message Brokers

- **RabbitMQ:** Queues and workers; decoupling and async processing
- **Kafka:** Distributed logs for large-scale event pipelines (e.g., logging, analytics)

Use queues when you want to decouple, retry, or parallelize tasks (e.g., sending emails, generating reports).

## 6. Testing

- **Unit Testing:** Test small isolated functions (e.g., math, validation)
- **Integration Testing:** Test full flow (e.g., API + DB)

## 7. CI/CD & DevOps

| Tool                                     | Use                                                  |
| ---------------------------------------- | ---------------------------------------------------- |
| **GitHub Actions / Jenkins / GitLab CI** | Automate build, test, and deployment pipelines       |
| **Docker**                               | Package apps with their dependencies                 |
| **Kubernetes**                           | Deploy and manage containers at scale                |
| **Terraform**                            | Infrastructure as Code for reproducible environments |
| **Prometheus + Grafana**                 | Monitor services (CPU, memory, errors)               |
| **ELK / Loki**                           | Logs aggregation and searching                       |

## 8. Cloud Platforms

| Provider  | Use                                                                         |
| --------- | --------------------------------------------------------------------------- |
| **AWS**   | EC2, Lambda, RDS, S3, SQS – everything from hosting to serverless to queues |
| **Azure** | Especially for enterprise or .NET-heavy environments                        |
