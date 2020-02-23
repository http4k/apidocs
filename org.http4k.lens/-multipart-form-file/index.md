[http4k](../../index.md) / [org.http4k.lens](../index.md) / [MultipartFormFile](./index.md)

# MultipartFormFile

`data class MultipartFormFile : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

### Types

| Name | Summary |
|---|---|
| [Companion](-companion.md) | `companion object Companion : `[`BiDiLensSpec`](../-bi-di-lens-spec/index.md)`<`[`MultipartForm`](../-multipart-form/index.md)`, `[`MultipartFormFile`](./index.md)`>` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MultipartFormFile(filename: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, content: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [content](content.md) | `val content: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [filename](filename.md) | `val filename: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
