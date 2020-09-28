[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [RateLimit](./index.md)

# RateLimit

`object RateLimit`

Provide simple Rate Limiter functionality.
By default, handles maximum of 50 requests per 5 seconds.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(rateLimit: RateLimiter = RateLimiter.ofDefaults("RateLimit"), onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(TOO_MANY_REQUESTS.description("Rate limit exceeded")) }): <ERROR CLASS>` |
