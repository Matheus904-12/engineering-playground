# Authentication and JWT

**Status:** Planned

## Study goals
- Authentication vs. authorization; sessions vs. tokens.
- JWT structure, signing, expiration, issuer, audience, and validation.
- Password hashing, secret management, refresh-token trade-offs, and revocation.
- Spring Security filter chain, roles, authorities, and method security.
- Common risks: trusting decoded-but-unverified claims, leaking tokens, and weak secrets.

## Practice
Secure a Java Spring Boot API with Spring Security. Add tests for anonymous access, valid tokens, expired tokens, and insufficient permissions. Never commit real secrets.

## Sources
- [Spring Security](https://docs.spring.io/spring-security/reference/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
