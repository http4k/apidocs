[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [Source](./index.md)

# Source

`interface Source`

Tries to retrieve a stored response for a given request.

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `abstract operator fun get(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)`?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [DiskTree](-disk-tree.md) | Looks up traffic from the FS, based on tree storage format.`fun DiskTree(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`Source`](./index.md) |
| [MemoryMap](-memory-map.md) | Looks up traffic from Memory, based on map storage format.`fun MemoryMap(cache: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Source`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ReadWriteCache](../-read-write-cache/index.md) | Combined Read/Write storage models, optimised for retrieval.`interface ReadWriteCache : `[`Sink`](../-sink/index.md)`, `[`Source`](./index.md) |
