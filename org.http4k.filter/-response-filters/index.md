[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ResponseFilters](./index.md)

# ResponseFilters

`object ResponseFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ResponseFilters.kt#L9)

### Types

| Name | Summary |
|---|---|
| [GunZip](-gun-zip/index.md) | `object GunZip`<br>Basic UnGZipping of Response. |
| [GZip](-g-zip/index.md) | `object GZip`<br>Basic GZipping of Response. |
| [GZipContentTypes](-g-zip-content-types/index.md) | `class GZipContentTypes : `[`Filter`](../../org.http4k.core/-filter/index.md)<br>GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types. |
| [ReportHttpTransaction](-report-http-transaction/index.md) | `object ReportHttpTransaction`<br>General reporting Filter for an ReportHttpTransaction. Pass an optional HttpTransactionLabeller to create custom labels. This is useful for logging metrics. Note that the passed function blocks the response from completing. |
| [ReportRouteLatency](-report-route-latency/index.md) | `object ReportRouteLatency`<br>Report the latency on a particular route to a callback function. This is useful for logging metrics. Note that the passed function blocks the response from completing. |
| [Tap](-tap/index.md) | `object Tap`<br>Intercept the response after it is sent to the next service. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
