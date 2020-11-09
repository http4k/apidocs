[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ResponseFilters](./index.md)

# ResponseFilters

`object ResponseFilters`

### Types

| Name | Summary |
|---|---|
| [GunZip](-gun-zip/index.md) | Basic UnGZipping of Response.`object GunZip` |
| [GZip](-g-zip/index.md) | Basic GZipping of Response.`object GZip` |
| [GZipContentTypes](-g-zip-content-types/index.md) | GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types.`class GZipContentTypes : `[`Filter`](../../org.http4k.core/-filter.md) |
| [ReportHttpTransaction](-report-http-transaction/index.md) | General reporting Filter for an ReportHttpTransaction. Pass an optional HttpTransactionLabeler to create custom labels. This is useful for logging metrics. Note that the passed function blocks the response from completing.`object ReportHttpTransaction` |
| [ReportRouteLatency](-report-route-latency/index.md) | Report the latency on a particular route to a callback function. This is useful for logging metrics. Note that the passed function blocks the response from completing.`object ReportRouteLatency` |
| [Tap](-tap/index.md) | Intercept the response after it is sent to the next service.`object Tap` |

### Functions

| Name | Summary |
|---|---|
| [Base64EncodeBody](-base64-encode-body.md) | Some platforms deliver bodies as Base64 encoded strings.`fun Base64EncodeBody(): <ERROR CLASS>` |

### Extension Functions

| Name | Summary |
|---|---|
| [Assert](../-assert.md) | Perform an assertThat on the outgoing Response as a Filter operation`fun `[`ResponseFilters`](./index.md)`.Assert(matcher: Matcher<`[`Response`](../../org.http4k.core/-response/index.md)`>): <ERROR CLASS>`<br>Perform an assertion on the outgoing Response as a Filter operation`fun `[`ResponseFilters`](./index.md)`.Assert(match: Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>): <ERROR CLASS>` |
