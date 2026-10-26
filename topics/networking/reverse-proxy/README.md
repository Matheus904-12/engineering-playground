# Reverse proxy and HTTP routing

**Status:** Planned

## Study goals
- Reverse proxy vs. forward proxy; L4 vs. L7 routing.
- TLS termination, headers, timeouts, and request size limits.
- Forwarded headers and secure client IP handling.
- How Java applications behave behind a proxy.

## Practice
Run a Java Spring Boot service behind Nginx, configure routing and timeouts, then document request flow and failure behavior.

## Sources
- [NGINX documentation](https://nginx.org/en/docs/)
- [Spring Boot proxy configuration](https://docs.spring.io/spring-boot/reference/)
