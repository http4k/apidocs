[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [URLResource](./index.md)

# URLResource

`data class URLResource : `[`Resource`](../-resource/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `URLResource(url: `[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [lastModified](last-modified.md) | `val lastModified: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`?` |
| [url](url.md) | `val url: `[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html) |

### Functions

| Name | Summary |
|---|---|
| [openStream](open-stream.md) | `fun openStream(): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |
