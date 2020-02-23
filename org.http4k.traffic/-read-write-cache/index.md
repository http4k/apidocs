[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteCache](./index.md)

# ReadWriteCache

`interface ReadWriteCache : `[`Sink`](../-sink/index.md)`, `[`Source`](../-source/index.md)

Combined Read/Write storage models, optimised for retrieval.

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | Serialise and retrieve HTTP traffic to/from the FS.`fun Disk(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteCache`](./index.md) |
| [Memory](-memory.md) | Serialise and retrieve HTTP traffic to/from Memory.`fun Memory(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`> = mutableMapOf(), shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteCache`](./index.md) |
