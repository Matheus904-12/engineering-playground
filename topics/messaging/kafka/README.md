# Apache Kafka and event-driven Java services

**Status:** Planned

## Study goals
- Topics, partitions, offsets, producers, consumers, and consumer groups.
- Keys, ordering, delivery semantics, retries, and dead-letter topics.
- Idempotent processing, duplicate events, and schema evolution.
- Event-driven architecture vs. synchronous REST calls.

## Practice
Build a Java producer and Spring Kafka consumer, run Kafka locally with Docker Compose, and test retries and duplicate processing. Document what happens when the consumer fails after processing but before committing an offset.

## Sources
- [Apache Kafka documentation](https://kafka.apache.org/documentation/)
- [Spring for Apache Kafka](https://docs.spring.io/spring-kafka/reference/)
