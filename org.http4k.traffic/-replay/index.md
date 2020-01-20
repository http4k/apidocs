[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Replay](./index.md)

# Replay

`interface Replay` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Replay.kt#L12)

Provides a stream of traffic for replaying purposes.

### Functions

| Name | Summary |
|---|---|
| [requests](requests.md) | `abstract fun requests(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [responses](responses.md) | `abstract fun responses(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | `fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`Replay`](./index.md)<br>Provides a stream of pre-stored HTTP traffic from the FS. |
| [MemoryStream](-memory-stream.md) | `fun MemoryStream(stream: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>): `[`Replay`](./index.md)<br>Provides a stream of pre-stored HTTP traffic from Memory. |

### Extension Functions

| Name | Summary |
|---|---|
| [replayingMatchingContent](../../org.http4k.testing/replaying-matching-content.md) | `fun `[`Replay`](./index.md)`.replayingMatchingContent(): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [Servirtium](../-servirtium.md) | `fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>): `[`Replay`](./index.md)<br>Read HTTP traffic from disk in Servirtium markdown format |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteStream](../-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](../-sink/index.md)`, `[`Replay`](./index.md)<br>Combined Read/Write storage models, optimised for replay. |
