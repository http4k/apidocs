[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [GZipContentTypes](./index.md)

# GZipContentTypes

`class GZipContentTypes : `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ResponseFilters.kt#L62)

GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GZipContentTypes(compressibleContentTypes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../../org.http4k.core/-content-type/index.md)`>)`<br>GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
