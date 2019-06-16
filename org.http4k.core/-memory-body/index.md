[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryBody](./index.md)

# MemoryBody

`data class MemoryBody : `[`Body`](../-body/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L45)

Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MemoryBody(payload: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`MemoryBody(payload: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)``MemoryBody(payload: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html)`)`<br>Represents a body that is backed by an in-memory ByteBuffer. Closing this has no effect. |

### Properties

| Name | Summary |
|---|---|
| [length](length.md) | `val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Will be `null` for bodies where it's impossible to a priori determine - e.g. StreamBody |
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
| [gzipped](../../org.http4k.filter/gzipped.md) | `fun `[`Body`](../-body/index.md)`.gzipped(): `[`Body`](../-body/index.md) |
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |
