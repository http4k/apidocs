[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionStorage](./index.md)

# InteractionStorage

`interface InteractionStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionStorage.kt#L13)

Provides storage for the recorded Servirtium interaction data.

### Functions

| Name | Summary |
|---|---|
| [clean](clean.md) | `abstract fun clean(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`StorageProvider`](../-storage-provider.md) |
| [InMemory](-in-memory.md) | `fun InMemory(): `[`StorageProvider`](../-storage-provider.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [Github](../-github.md) | `fun InteractionStorage.Companion.Github(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, basePath: `[`Path`](https://docs.oracle.com/javase/9/docs/api/java/nio/file/Path.html)` = Path.of(""), reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = SetBaseUriFrom(Uri.of("https://api.github.com")).then(JavaHttpClient())): `[`StorageProvider`](../-storage-provider.md)<br>Read a file from a repository using the GitHub API. |
