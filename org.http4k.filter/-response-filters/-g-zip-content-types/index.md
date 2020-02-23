[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [GZipContentTypes](./index.md)

# GZipContentTypes

`class GZipContentTypes : `[`Filter`](../../../org.http4k.core/-filter/index.md)

GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types.`GZipContentTypes(compressibleContentTypes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../../org.http4k.core/-content-type/index.md)`>, compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = Memory)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
