[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [RateLimit](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(rateLimit: RateLimiter = RateLimiter.ofDefaults("RateLimit"), onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(TOO_MANY_REQUESTS.description("Rate limit exceeded")) }): <ERROR CLASS>`