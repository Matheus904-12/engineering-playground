# Observability for Java services

**Status:** Planned

## Study goals
- Structured logs, metrics, traces, correlation IDs, and useful dashboards.
- Golden signals: latency, traffic, errors, and saturation.
- Spring Boot Actuator and Micrometer.
- Alert quality, cardinality, sensitive data, and sampling.

## Practice
Add Actuator and Micrometer to a Java service, expose health/metrics appropriately, and trace a request through a failure scenario. Never expose management endpoints publicly without deliberate security controls.

## Sources
- [Spring Boot Actuator](https://docs.spring.io/spring-boot/reference/actuator/)
- [OpenTelemetry](https://opentelemetry.io/docs/)
