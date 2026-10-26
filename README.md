# Engineering Playground

A hands-on software engineering lab exploring backend technologies, system design, distributed systems, security, and cloud infrastructure through practical experiments and technical documentation.

> The goal is not to collect technology names. Each topic should explain a problem, show how a solution works, and include a reproducible experiment whenever practical.

## Technology catalog

| Area | Topic | Status | What to explore |
|---|---|---|---|
| Messaging | [Apache Kafka](topics/messaging/kafka/README.md) | In progress | Producers, consumers, topics, partitions, consumer groups |
| Security | [JWT](topics/security/jwt/README.md) | Planned | Claims, signing, expiration, validation, authorization |
| Networking | [Load balancing](topics/networking/load-balancing/README.md) | Planned | Algorithms, health checks, L4 vs L7 |
| Networking | [Reverse proxy](topics/networking/reverse-proxy/README.md) | Planned | Routing, TLS termination, reverse vs forward proxy |
| Cloud | [AWS Application Load Balancer](topics/cloud/aws-alb/README.md) | Planned | Listeners, rules, target groups, health checks |
| Observability | [Observability](topics/observability/README.md) | Planned | Logs, metrics, traces, useful signals |

## Repository structure

```text
engineering-playground/
├── README.md
├── CONTRIBUTING.md
├── docs/
│   └── study-template.md
└── topics/
    ├── cloud/aws-alb/
    ├── messaging/kafka/
    ├── networking/load-balancing/
    ├── networking/reverse-proxy/
    ├── observability/
    └── security/jwt/
```

## How each topic is documented

Each topic should answer:

1. **What problem does it solve?**
2. **How does it work?** Include a diagram when useful.
3. **When should it be used — and when not?**
4. **How can I reproduce the example locally?**
5. **How do I test that it works?**
6. **What trade-offs, failure modes, and security concerns matter?**
7. **What did I learn?** Record findings honestly; distinguish tested behavior from theory.

## Study status

- **Planned** — not studied yet.
- **In progress** — currently learning or experimenting.
- **Verified** — example executed and results documented.
- **Needs review** — content should be revisited or updated.

Statuses are learning notes, not claims of professional mastery.

## Suggested learning path

1. HTTP, reverse proxies, and load balancing fundamentals.
2. JWT, authentication, and authorization.
3. Kafka fundamentals and event-driven communication.
4. Docker-based local environments and integration testing.
5. Observability, resilience, and failure handling.
6. AWS ALB and deployment-oriented experiments.

## Projects vs. notes

This repository is for focused studies and small reproducible experiments. If an experiment grows into a complete application with independent architecture, tests, deployment instructions, and a clear use case, consider promoting it to its own repository and linking it here.

## Language

The repository is written in English to make it accessible to a broader technical audience. Keep explanations precise and only mark an experiment as verified after running it.

---
Built as a personal learning lab for software engineering.
