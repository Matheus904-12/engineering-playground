# Load balancing

**Status:** Planned

## Study goals
- Round robin, least connections, weighted routing, and health checks.
- L4 vs. L7 load balancing, sticky sessions, and stateless services.
- Readiness vs. liveness, draining, and graceful shutdown.
- Retries, timeouts, and why retries can amplify overload.

## Practice
Run two instances of a small Java API behind a load balancer, observe request distribution, stop one instance, and record the results.

## Sources
- [NGINX documentation](https://nginx.org/en/docs/)
- [AWS Elastic Load Balancing](https://docs.aws.amazon.com/elasticloadbalancing/)
