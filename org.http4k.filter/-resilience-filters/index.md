[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ResilienceFilters](./index.md)

# ResilienceFilters

`object ResilienceFilters`

### Types

| Name | Summary |
|---|---|
| [Bulkheading](-bulkheading/index.md) | Provide simple Bulkhead functionality. By default, handles 25 parallel requests, with zero wait time.`object Bulkheading` |
| [CircuitBreak](-circuit-break/index.md) | Provide simple Circuit Breaker. Returns ServiceUnavailable when the circuit is open. By default, uses a % failure rate of 50% detection and an Circuit Open period of 1minute`object CircuitBreak` |
| [RateLimit](-rate-limit/index.md) | Provide simple Rate Limiter functionality. By default, handles maximum of 50 requests per 5 seconds.`object RateLimit` |
| [RetryFailures](-retry-failures/index.md) | Provide simple Retrying functionality. Returns the last response when retries expire. By default, retries 3 times with a delay of 500ms between attempts, backing off at a 1.5x multiplier.`object RetryFailures` |
