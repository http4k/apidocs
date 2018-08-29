[http4k](../../index.md) / [org.http4k.filter](../index.md) / [RequestFilters](./index.md)

# RequestFilters

`object RequestFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/RequestFilters.kt#L8)

### Types

| Name | Summary |
|---|---|
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic GZipping of Request. Does not currently support GZipping streams |
| [GunZip](-gun-zip/index.md) | `object GunZip`<br>Basic UnGZipping of Request. Does not currently support GZipping streams |
| [ProxyHost](-proxy-host/index.md) | `object ProxyHost`<br>Sets the host on an outbound request from the Host header of the incoming request. This is useful for implementing proxies. |
| [Tap](-tap/index.md) | `object Tap`<br>Intercept the request before it is sent to the next service. |
