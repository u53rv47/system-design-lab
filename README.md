# System Design Lab 🧪

Welcome to the **System Design Lab** — a hands-on project for mastering system design by learning theory, building systems, and documenting insights.

Here's a comprehensive list of core and advanced topics in system design, grouped by category with recommended resources.

---

## 📚 Foundational Concepts

- **CAP Theorem**
  - [CAP Theorem - Martin Kleppmann](https://martin.kleppmann.com/papers/2015-cacm-cap.pdf)
  - [System Design Primer](https://github.com/donnemartin/system-design-primer#cap-theorem)
- **Consistency Models**
  - Strong, Eventual, Causal, Read-your-writes
- **Latency vs Throughput**
- **Scalability (Vertical vs Horizontal)**

---

## ⚙️ Core System Components

### Load Balancing
- [Gaurav Sen - Load Balancer](https://www.youtube.com/watch?v=KxZ7jHkzHJ8)
- Round-robin, Least-connections, IP-hash
- Health checks and failover
- Global load balancing (GeoDNS, Anycast)

### Caching
- [System Design Primer - Caching](https://github.com/donnemartin/system-design-primer#cache)
- TTL, Eviction Policies (LRU, LFU)
- CDN integration
- Write-through vs Write-around

### Database Design
- SQL vs NoSQL
- Data modeling
- Schema design
- [MongoDB Design Patterns](https://www.mongodb.com/blog/post/6-rules-of-thumb-for-mongodb-schema-design-part-1)

### Message Queues
- [Kafka Design](https://kafka.apache.org/documentation/)
- RabbitMQ, ActiveMQ, Redis Streams
- Pub/Sub vs Point-to-point
- Backpressure & Retry strategies

---

## 🌍 Distributed Systems

- **Replication**
  - Synchronous vs Asynchronous
  - Leader-Follower, Multi-leader, CRDTs
- **Sharding / Partitioning**
  - Static vs Dynamic
  - Consistent Hashing
- **Distributed Consensus**
  - Raft, Paxos, ZAB
  - [MIT 6.824: Raft](https://raft.github.io/)
- **Clock Synchronization**
  - Lamport Timestamps
  - Vector Clocks

---

## 🧰 Infrastructure & Deployment

- **Containers & Orchestration**
  - Docker, Kubernetes
  - Service discovery
- **Monitoring & Observability**
  - Prometheus, Grafana, Jaeger, ELK
- **Disaster Recovery**
  - Backup strategies
  - Geo-redundancy

---

## 🔧 Real-World Systems

- **Content Delivery Network (CDN)**
  - Caching, edge servers, invalidation
- **URL Shortener**
  - Base62, hash collisions
- **Rate Limiter**
  - Token Bucket, Leaky Bucket
- **Analytics Pipeline**
  - Log aggregation, ETL, real-time vs batch

---

## 🛡️ Reliability & Performance

- **Retry Logic, Circuit Breakers**
- **Timeouts and Rate Limiting**
- **Redundancy & Failover**
- **SLAs, SLOs, SLIs**

---

## 🧑‍🏫 Learning Resources

- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Designing Data-Intensive Applications](https://dataintensive.net/)
- [ByteByteGo](https://bytebytego.com/)
- [MIT 6.824 (Distributed Systems)](https://pdos.csail.mit.edu/6.824/)
- [High Scalability Blog](http://highscalability.com/)

---
