[http4k](../../index.md) / [org.http4k.filter](../index.md) / [RequestFilters](./index.md)

# RequestFilters

`object RequestFilters`

### Types

| Name | Summary |
|---|---|
| [GunZip](-gun-zip/index.md) | Basic UnGZipping of Request.`object GunZip` |
| [GZip](-g-zip/index.md) | Basic GZipping of Request.`object GZip` |
| [ProxyHost](-proxy-host/index.md) | Sets the host on an outbound request from the Host header of the incoming request. This is useful for implementing proxies. Note the use of the ProxyProtocolMode to set the outbound scheme`object ProxyHost` |
| [ProxyProtocolMode](-proxy-protocol-mode/index.md) | `enum class ProxyProtocolMode` |
| [Tap](-tap/index.md) | Intercept the request before it is sent to the next service.`object Tap` |
