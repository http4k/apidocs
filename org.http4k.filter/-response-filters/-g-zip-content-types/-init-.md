[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [GZipContentTypes](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`GZipContentTypes(compressibleContentTypes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../../org.http4k.core/-content-type/index.md)`>, compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = NON_STREAMING)`

GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types.

