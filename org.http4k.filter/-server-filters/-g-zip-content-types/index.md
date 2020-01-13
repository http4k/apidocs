[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [GZipContentTypes](./index.md)

# GZipContentTypes

`class GZipContentTypes : `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L256)

Basic GZip and Gunzip support of Request/Response where the content-type is in the allowed list.
Only Gunzips requests which contain "transfer-encoding" header containing 'gzip'
Only Gzips responses when request contains "accept-encoding" header containing 'gzip' and the content-type (sans-charset) is one of the compressible types.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GZipContentTypes(compressibleContentTypes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../../org.http4k.core/-content-type/index.md)`>, compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = NON_STREAMING)`<br>Basic GZip and Gunzip support of Request/Response where the content-type is in the allowed list. Only Gunzips requests which contain "transfer-encoding" header containing 'gzip' Only Gzips responses when request contains "accept-encoding" header containing 'gzip' and the content-type (sans-charset) is one of the compressible types. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
