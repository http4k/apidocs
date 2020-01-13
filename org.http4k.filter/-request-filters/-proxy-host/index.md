[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [RequestFilters](../index.md) / [ProxyHost](./index.md)

# ProxyHost

`object ProxyHost` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/RequestFilters.kt#L62)

Sets the host on an outbound request from the Host header of the incoming request. This is useful for implementing proxies.
Note the use of the ProxyProtocolMode to set the outbound scheme

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(mode: `[`RequestFilters.ProxyProtocolMode`](../-proxy-protocol-mode/index.md)` = ProxyProtocolMode.Http): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
