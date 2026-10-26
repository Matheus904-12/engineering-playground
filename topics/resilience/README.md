# Resilience and failure handling

**Status:** Planned

## Study goals
- Timeouts, bounded retries, exponential backoff, and jitter.
- Circuit breakers, bulkheads, rate limits, and graceful degradation.
- Idempotency and safe handling of repeated requests.
- Why a fallback can hide failures if observability is poor.

## Practice
Use a Java Spring Boot service to simulate a slow or unavailable dependency. Compare behavior with timeouts and bounded retries, and document the results.

## Sources
- [Resilience4j](https://resilience4j.readme.io/)
- [Google SRE books](https://sre.google/books/)
