# Caching with Redis in Java services

**Status:** Planned

## Study goals
- Cache-aside, TTL, invalidation, and cache stampede.
- What should and should not be cached.
- Cache consistency, serialization, and failure behavior.
- Spring Cache abstraction vs. direct Redis operations.

## Practice
Add a Redis cache to a Spring Boot endpoint, measure response behavior, test expiration, and describe what happens when Redis is unavailable.

## Sources
- [Redis documentation](https://redis.io/docs/latest/)
- [Spring Data Redis](https://docs.spring.io/spring-data/redis/reference/)
