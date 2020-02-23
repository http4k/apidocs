[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [InMemoryResource](./index.md)

# InMemoryResource

`class InMemoryResource : `[`Resource`](../-resource/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InMemoryResource(content: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`? = null, etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`? = null)`<br>`InMemoryResource(content: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`? = null, etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [etag](etag.md) | `val etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`?` |
| [lastModified](last-modified.md) | `val lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`?` |
| [length](length.md) | `val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [openStream](open-stream.md) | `fun openStream(): `[`ByteArrayInputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/ByteArrayInputStream.html) |
