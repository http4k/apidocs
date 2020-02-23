[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Sink](./index.md)

# Sink

`interface Sink`

Consumes HTTP traffic for storage.

### Functions

| Name | Summary |
|---|---|
| [set](set.md) | `abstract operator fun set(request: `[`Request`](../../org.http4k.core/-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | Serialises HTTP traffic to the FS in order.`fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }, id: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { System.nanoTime().toString() + UUID.randomUUID().toString() }): `[`Sink`](./index.md) |
| [DiskTree](-disk-tree.md) | Serialises HTTP traffic to the FS, optimised for retrieval.`fun DiskTree(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md) |
| [MemoryMap](-memory-map.md) | Serialises HTTP traffic in Memory, optimised for retrieval.`fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md) |
| [MemoryStream](-memory-stream.md) | Serialises HTTP traffic to Memory in order.`fun MemoryStream(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [Servirtium](../-servirtium.md) | Write HTTP traffic to disk in Servirtium markdown format.`fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, options: `[`InteractionOptions`](../../org.http4k.servirtium/-interaction-options/index.md)`): `[`Sink`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteCache](../-read-write-cache/index.md) | Combined Read/Write storage models, optimised for retrieval.`interface ReadWriteCache : `[`Sink`](./index.md)`, `[`Source`](../-source/index.md) |
| [ReadWriteStream](../-read-write-stream/index.md) | Combined Read/Write storage models, optimised for replay.`interface ReadWriteStream : `[`Sink`](./index.md)`, `[`Replay`](../-replay/index.md) |
