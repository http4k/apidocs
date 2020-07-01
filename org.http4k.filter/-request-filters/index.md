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

### Functions

| Name | Summary |
|---|---|
| [Base64DecodeBody](-base64-decode-body.md) | Some platforms deliver bodies as Base64 encoded strings.`fun Base64DecodeBody(): `[`Filter`](../../org.http4k.core/-filter/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [Assert](../-assert.md) | Perform an assertThat on the incoming Request as a Filter operation`fun `[`RequestFilters`](./index.md)`.Assert(matcher: Matcher<`[`Request`](../../org.http4k.core/-request/index.md)`>): `[`Filter`](../../org.http4k.core/-filter/index.md) |
