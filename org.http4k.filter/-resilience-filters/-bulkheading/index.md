[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResilienceFilters](../index.md) / [Bulkheading](./index.md)

# Bulkheading

`object Bulkheading`

Provide simple Bulkhead functionality.
By default, handles 25 parallel requests, with zero wait time.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(bulkhead: Bulkhead = Bulkhead.ofDefaults("Bulkhead"), onError: () -> `[`Response`](../../../org.http4k.core/-response/index.md)` = { Response(TOO_MANY_REQUESTS.description("Bulkhead limit exceeded")) }): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
