[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteStream](./index.md)

# ReadWriteStream

`interface ReadWriteStream : `[`Sink`](../-sink/index.md)`, `[`Replay`](../-replay/index.md)

Combined Read/Write storage models, optimised for replay.

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | Serialise and replay HTTP traffic to/from the FS in order.`fun Disk(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteStream`](./index.md) |
| [Memory](-memory.md) | Serialise and replay HTTP traffic to/from Memory in order.`fun Memory(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>> = mutableListOf(), shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteStream`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [replayingMatchingContent](../replaying-matching-content.md) | `fun `[`Replay`](../-replay/index.md)`.replayingMatchingContent(manipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
