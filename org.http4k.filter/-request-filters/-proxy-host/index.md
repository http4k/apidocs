[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [RequestFilters](../index.md) / [ProxyHost](./index.md)

# ProxyHost

`object ProxyHost`

Sets the host on an outbound request from the Host header of the incoming request. This is useful for implementing proxies.
Note the use of the ProxyProtocolMode to set the outbound scheme

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(mode: ProxyProtocolMode = ProxyProtocolMode.Http): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
