[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionStorageLookup](./index.md)

# InteractionStorageLookup

`interface InteractionStorageLookup : (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`InteractionStorage`](../-interaction-storage.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionStorage.kt#L13)

Provides a way of providing a storage layer for

### Functions

| Name | Summary |
|---|---|
| [clean](clean.md) | `abstract fun clean(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File(".")): `[`InteractionStorageLookup`](./index.md) |
| [InMemory](-in-memory.md) | `fun InMemory(): `[`InteractionStorageLookup`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
