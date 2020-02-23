[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Replay](./index.md)

# Replay

`interface Replay`

Provides a stream of traffic for replaying purposes.

### Functions

| Name | Summary |
|---|---|
| [requests](requests.md) | `abstract fun requests(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [responses](responses.md) | `abstract fun responses(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | Provides a stream of pre-stored HTTP traffic from the FS.`fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`Replay`](./index.md) |
| [MemoryStream](-memory-stream.md) | Provides a stream of pre-stored HTTP traffic from Memory.`fun MemoryStream(stream: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>): `[`Replay`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [replayingMatchingContent](../replaying-matching-content.md) | `fun `[`Replay`](./index.md)`.replayingMatchingContent(manipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [Servirtium](../-servirtium.md) | Read HTTP traffic from disk in Servirtium markdown format.`fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, options: `[`InteractionOptions`](../../org.http4k.servirtium/-interaction-options/index.md)` = Defaults): `[`Replay`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteStream](../-read-write-stream/index.md) | Combined Read/Write storage models, optimised for replay.`interface ReadWriteStream : `[`Sink`](../-sink/index.md)`, `[`Replay`](./index.md) |
