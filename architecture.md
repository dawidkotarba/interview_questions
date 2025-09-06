# Architecture & Distributed Systems

## Deployment Strategies
- What is the difference between big bang, canary, and blue/green deployment? Advantages and disadvantages of each.
- What is rolling deployment? Pros and cons.
- What is a feature toggle (feature flag) and how can it help in deployment?
- What is immutable deployment? Advantages.
- How do you handle rollback strategies in production?

## System Design & High-Level Architecture
- Describe the high-level architecture of your latest project. Include diagram of interactions.
- How do you handle scaling in your architecture? (vertical vs horizontal scaling)
- How do you design for high availability and fault tolerance?
- How do you approach low-latency requirements in your systems?
- How do you design systems for high throughput?
- How do you handle asynchronous communication? (message queues, events, pub/sub)
- How do you manage shared state in distributed systems?
- How do you ensure consistency in distributed systems? (CAP theorem)
- How do you handle eventual consistency?
- How do you manage distributed transactions? (2PC, Saga pattern)
- How do you deal with distributed locks?
- How do you handle backpressure in distributed pipelines?

## Architectural Challenges
- What was the most challenging task from an architectural point of view you have implemented?
- Describe a situation when you had to refactor or redesign a system for scalability or performance.
- How do you balance trade-offs between security, performance, and maintainability?
- How do you handle backward compatibility in system design?
- How do you approach API versioning in your architecture?
- How do you detect and mitigate single points of failure?
- How do you design for disaster recovery?

## Performance & Scalability
- How do you design systems for horizontal and vertical scalability?
- How do you scale databases? (sharding, replication, partitioning)
- How do you handle cache in a distributed system? (local vs distributed caches)
- How do you reduce latency in distributed services?
- How do you perform capacity planning for your systems?
- How do you handle high request loads? (load balancing strategies, CDN, throttling)
- How do you design for multi-region availability?

## Networking & Communication
- How do you handle network failures in distributed systems?
- How do you design APIs for reliability and efficiency? (REST vs gRPC vs GraphQL)
- How do you handle service discovery in microservices architecture?
- How do you implement rate limiting and throttling?
- How do you ensure secure communication between services? (TLS, mutual TLS, OAuth, JWT)

## Data Storage & Management
- How do you choose between SQL and NoSQL databases for your architecture?
- How do you handle data consistency and integrity in distributed databases?
- How do you design event sourcing and CQRS patterns?
- How do you implement a data warehouse or analytics pipeline?
- How do you handle replication lag in distributed databases?
- How do you design for multi-tenant systems?

## Observability & Monitoring
- How do you monitor distributed systems? (metrics, logging, tracing)
- What metrics are most important for system health?
- How do you implement distributed tracing?
- How do you set up alerts for production systems?
- How do you debug performance issues in distributed systems?

## Design Patterns & Principles
- Which architectural patterns do you apply? (microservices, monolith, event-driven, serverless)
- What are common anti-patterns in distributed systems?
- How do you apply SOLID, DRY, KISS, YAGNI principles in architecture?
- What design patterns have you applied? (e.g., singleton, factory, observer, strategy, decorator)
- How do you handle modularity and separation of concerns?
- How do you design for extensibility and maintainability?

## Cloud & Modern Infrastructure
- How do you design cloud-native systems? (AWS, Azure, GCP)
- How do you manage containerized applications? (Docker, Kubernetes)
- How do you implement auto-scaling in cloud environments?
- How do you design for hybrid and multi-cloud architectures?
- How do you handle secrets management in distributed systems?

## Reliability & Fault Tolerance
- How do you implement retries and circuit breakers?
- How do you handle failover between services and databases?
- How do you design for zero-downtime deployments?
- How do you ensure idempotency in distributed systems?
- How do you detect and recover from partial failures?

## Security
- How do you design for secure distributed systems?
- How do you handle authentication and authorization in microservices?
- How do you secure API gateways and service-to-service communication?
- How do you implement data encryption at rest and in transit?
- How do you prevent common web attacks in distributed architectures? (SQL injection, XSS, CSRF)

## Testing & QA for Architecture
- How do you perform load testing and stress testing?
- How do you simulate failures in distributed systems? (Chaos engineering)
- How do you ensure data consistency under concurrent loads?
- How do you perform integration testing for microservices?

## Miscellaneous / Best Practices
- How do you choose between synchronous vs asynchronous communication?
- How do you handle versioning of services in distributed environments?
- How do you document architecture for developers and stakeholders?
- How do you handle technical debt in complex systems?
- How do you conduct architectural reviews and audits?
- How do you make trade-offs between performance, reliability, and cost?
