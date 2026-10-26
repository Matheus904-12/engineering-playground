# Engineering Playground

A Java-first software engineering lab focused on backend development, system design, distributed systems, security, cloud infrastructure, and production engineering.

**Main stack:** Java · Spring Boot · JUnit · SQL · Docker  
**Learning style:** concept → small experiment → automated test → documented trade-offs.

> This is a learning portfolio, not a list of technologies claimed as mastered. Topics move to **Verified** only after examples have actually been run and checked.

## Study roadmap

| Area | Topic | What to practice |
|---|---|---|
| Java | [Java fundamentals](topics/java/core/README.md) | OOP, collections, generics, streams, exceptions, JVM |
| Backend | [REST APIs with Spring Boot](topics/java/spring-boot-rest/README.md) | Layering, DTOs, validation, HTTP, error handling |
| Quality | [Testing Java applications](topics/java/testing/README.md) | JUnit 5, Mockito, integration tests, Testcontainers |
| Data | [SQL, transactions, and JPA](topics/database/sql-jpa/README.md) | SQL, indexes, transactions, JDBC, Hibernate, migrations |
| Security | [Authentication and JWT](topics/security/jwt/README.md) | Spring Security, tokens, authorization, secure defaults |
| Messaging | [Apache Kafka](topics/messaging/kafka/README.md) | Events, partitions, consumer groups, retries, idempotency |
| Caching | [Redis](topics/cache/redis/README.md) | Cache-aside, TTL, invalidation, failure behavior |
| Architecture | [System design](topics/architecture/system-design/README.md) | Requirements, capacity, trade-offs, failure domains |
| Networking | [HTTP, DNS, and TLS](topics/networking/http-dns-tls/README.md) | Request lifecycle, status codes, certificates |
| Networking | [Reverse proxy](topics/networking/reverse-proxy/README.md) | Routing, TLS termination, timeouts |
| Networking | [Load balancing](topics/networking/load-balancing/README.md) | Algorithms, health checks, L4 vs. L7 |
| Cloud | [AWS Application Load Balancer](topics/cloud/aws-alb/README.md) | Listeners, target groups, routing, health checks |
| Containers | [Docker](topics/containers/docker/README.md) | Images, Compose, multi-stage builds, local dependencies |
| Reliability | [Resilience patterns](topics/resilience/README.md) | Timeouts, retries, circuit breakers, bulkheads |
| Observability | [Observability](topics/observability/README.md) | Logs, metrics, traces, Actuator, Micrometer |
| Delivery | [CI/CD with GitHub Actions](topics/ci-cd/github-actions/README.md) | Build, tests, pull-request checks, artifacts |
| Performance | [JVM performance](topics/performance/jvm-performance/README.md) | Profiling, garbage collection, latency, throughput |

## Repository structure

```text
engineering-playground/
├── README.md
├── CONTRIBUTING.md
├── docs/
│   └── study-template.md
└── topics/
    ├── architecture/system-design/
    ├── cache/redis/
    ├── ci-cd/github-actions/
    ├── cloud/aws-alb/
    ├── containers/docker/
    ├── database/sql-jpa/
    ├── java/
    │   ├── core/
    │   ├── spring-boot-rest/
    │   └── testing/
    ├── messaging/kafka/
    ├── networking/
    ├── observability/
    ├── performance/jvm-performance/
    ├── resilience/
    └── security/jwt/
```

## How to study each topic

Every topic should answer:

1. **Problem:** What problem does this solve, and what alternatives exist?
2. **Concepts:** How does it work? Use diagrams when they clarify the flow.
3. **Java implementation:** Build a small, understandable example; use Spring Boot when it fits.
4. **Tests:** Cover expected behavior, edge cases, and failures.
5. **Reproducibility:** Include prerequisites, commands, and expected output.
6. **Trade-offs:** Explain complexity, security, cost, and operational failure modes.
7. **Reflection:** Record what was learned and what remains uncertain.

## Status legend

- **Planned** — not studied yet.
- **In progress** — currently learning or experimenting.
- **Verified** — example executed and results documented.
- **Needs review** — revisit the content or example.

## Suggested learning order

1. Java fundamentals, HTTP, and SQL.
2. Spring Boot REST APIs, validation, and automated tests.
3. PostgreSQL, JPA, transactions, and Docker.
4. Authentication, authorization, and security testing.
5. Networking, reverse proxies, and load balancing.
6. Caching, Kafka, idempotency, and resilience.
7. Observability, CI/CD, JVM performance, and cloud deployment.
8. System design: combine the concepts in realistic architecture exercises.

## Portfolio principles

- Java is the default language for runnable code in this repository.
- Prefer official documentation and explain concepts in your own words.
- Do not commit credentials, tokens, private data, or real secrets.
- Avoid adding tools just to inflate the technology list; explain why each is useful.
- When a study becomes a complete application, consider giving it a separate repository and linking it here.

## Primary references

- [Dev.java](https://dev.java/learn/)
- [Spring Boot](https://docs.spring.io/spring-boot/index.html)
- [Spring Security](https://docs.spring.io/spring-security/reference/)
- [JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Apache Kafka](https://kafka.apache.org/documentation/)
- [Docker](https://docs.docker.com/)
- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)

---
Built as a personal Java-first engineering learning lab.
