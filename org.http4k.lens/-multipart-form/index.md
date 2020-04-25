[http4k](../../index.md) / [org.http4k.lens](../index.md) / [MultipartForm](./index.md)

# MultipartForm

`data class MultipartForm : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MultipartForm(fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormField`](../-multipart-form-field/index.md)`>> = emptyMap(), files: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormFile`](../-multipart-form-file/index.md)`>> = emptyMap(), errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`> = emptyList())` |

### Properties

| Name | Summary |
|---|---|
| [errors](errors.md) | `val errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`>` |
| [fields](fields.md) | `val fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormField`](../-multipart-form-field/index.md)`>>` |
| [files](files.md) | `val files: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MultipartFormFile`](../-multipart-form-file/index.md)`>>` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [minusField](minus-field.md) | `fun minusField(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MultipartForm`](./index.md) |
| [minusFile](minus-file.md) | `fun minusFile(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MultipartForm`](./index.md) |
| [plus](plus.md) | `operator fun plus(kv: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`MultipartForm`](./index.md)<br>`operator fun plus(kv: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MultipartFormField`](../-multipart-form-field/index.md)`>): `[`MultipartForm`](./index.md)<br>`operator fun plus(kv: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MultipartFormFile`](../-multipart-form-file/index.md)`>): `[`MultipartForm`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun `[`MultipartForm`](./index.md)`.with(vararg modifiers: (`[`MultipartForm`](./index.md)`) -> `[`MultipartForm`](./index.md)`): `[`MultipartForm`](./index.md) |
