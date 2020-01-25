[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Sink](./index.md)

# Sink

`interface Sink` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/traffic/Sink.kt#L13)

Consumes HTTP traffic for storage.

### Functions

| Name | Summary |
|---|---|
| [set](set.md) | `abstract operator fun set(request: `[`Request`](../../org.http4k.core/-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskStream](-disk-stream.md) | `fun DiskStream(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }, id: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { System.nanoTime().toString() + UUID.randomUUID().toString() }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to the FS in order. |
| [DiskTree](-disk-tree.md) | `fun DiskTree(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to the FS, optimised for retrieval. |
| [MemoryMap](-memory-map.md) | `fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic in Memory, optimised for retrieval. |
| [MemoryStream](-memory-stream.md) | `fun MemoryStream(stream: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>>, shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`Sink`](./index.md)<br>Serialises HTTP traffic to Memory in order. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [Servirtium](../-servirtium.md) | `fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = { it }): `[`Sink`](./index.md)<br>Write HTTP traffic to disk in Servirtium markdown format. |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteCache](../-read-write-cache/index.md) | `interface ReadWriteCache : `[`Sink`](./index.md)`, `[`Source`](../-source/index.md)<br>Combined Read/Write storage models, optimised for retrieval. |
| [ReadWriteStream](../-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](./index.md)`, `[`Replay`](../-replay/index.md)<br>Combined Read/Write storage models, optimised for replay. |
