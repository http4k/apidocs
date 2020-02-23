[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryBody](./index.md)

# MemoryBody

`data class MemoryBody : `[`Body`](../-body/index.md)

Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MemoryBody(payload: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`MemoryBody(payload: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)`<br>Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect.`MemoryBody(payload: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [length](length.md) | Will be `null` for bodies where it's impossible to a priori determine - e.g. StreamBody`val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [payload](payload.md) | `val payload: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html) |
| [stream](stream.md) | `val stream: `[`ByteArrayInputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/ByteArrayInputStream.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [gunzipped](../../org.http4k.filter/gunzipped.md) | `fun `[`Body`](../-body/index.md)`.gunzipped(): `[`Body`](../-body/index.md) |
| [gunzippedStream](../../org.http4k.filter/gunzipped-stream.md) | `fun `[`Body`](../-body/index.md)`.gunzippedStream(): `[`Body`](../-body/index.md) |
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](../-body/index.md)`.gzipped(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |
| [gzippedStream](../../org.http4k.filter/gzipped-stream.md) | `fun `[`Body`](../-body/index.md)`.gzippedStream(): `[`CompressionResult`](../../org.http4k.filter/-compression-result/index.md) |
