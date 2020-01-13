[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [GZipContentTypes](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`GZipContentTypes(compressibleContentTypes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../../org.http4k.core/-content-type/index.md)`>, compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = Memory)`

Basic GZip and Gunzip support of Request/Response where the content-type is in the allowed list.
Only Gunzips requests which contain "transfer-encoding" header containing 'gzip'
Only Gzips responses when request contains "accept-encoding" header containing 'gzip' and the content-type (sans-charset) is one of the compressible types.

