[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [Resource](./index.md)

# Resource

`interface Resource : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `open val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [etag](etag.md) | `open val etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`?` |
| [headers](headers.md) | `open val headers: `[`Headers`](../../org.http4k.core/-headers.md) |
| [lastModified](last-modified.md) | `open val lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`?` |
| [length](length.md) | `open val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`MemoryResponse`](../../org.http4k.core/-memory-response/index.md) |
| [isModifiedSince](is-modified-since.md) | `open fun isModifiedSince(instant: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [openStream](open-stream.md) | `abstract fun openStream(): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |

### Inheritors

| Name | Summary |
|---|---|
| [InMemoryResource](../-in-memory-resource/index.md) | `class InMemoryResource : `[`Resource`](./index.md) |
| [URLResource](../-u-r-l-resource/index.md) | `data class URLResource : `[`Resource`](./index.md) |
