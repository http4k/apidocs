[http4k](../../index.md) / [org.http4k.core](../index.md) / [MultipartEntity](./index.md)

# MultipartEntity

`sealed class MultipartEntity : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-multipart/src/main/kotlin/org/http4k/core/MultipartFormBody.kt#L18)

### Types

| Name | Summary |
|---|---|
| [Field](-field/index.md) | `data class Field : `[`MultipartEntity`](./index.md) |
| [File](-file/index.md) | `data class File : `[`MultipartEntity`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [Field](-field/index.md) | `data class Field : `[`MultipartEntity`](./index.md) |
| [File](-file/index.md) | `data class File : `[`MultipartEntity`](./index.md) |
