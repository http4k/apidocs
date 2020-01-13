[http4k](../../index.md) / [org.http4k.filter](../index.md) / [RequestFilters](./index.md)

# RequestFilters

`object RequestFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/RequestFilters.kt#L10)

### Types

| Name | Summary |
|---|---|
| [GunZip](-gun-zip/index.md) | `object GunZip`<br>Basic UnGZipping of Request. |
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic GZipping of Request. |
| [ProxyHost](-proxy-host/index.md) | `object ProxyHost`<br>Sets the host on an outbound request from the Host header of the incoming request. This is useful for implementing proxies. Note the use of the ProxyProtocolMode to set the outbound scheme |
| [ProxyProtocolMode](-proxy-protocol-mode/index.md) | `enum class ProxyProtocolMode` |
| [Tap](-tap/index.md) | `object Tap`<br>Intercept the request before it is sent to the next service. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
