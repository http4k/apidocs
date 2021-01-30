[http4k](../../index.md) / [org.http4k.core](../index.md) / [Accept](./index.md)

# Accept

`data class Accept`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Accept(contentTypes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContentType`](../-content-type/index.md)`>, directives: `[`Parameters`](../-parameters.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [contentTypes](content-types.md) | `val contentTypes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContentType`](../-content-type/index.md)`>` |
| [directives](directives.md) | `val directives: `[`Parameters`](../-parameters.md) |

### Functions

| Name | Summary |
|---|---|
| [accepts](accepts.md) | Note that the Accept header ignores CharSet because that is in a separate Accept-CharSet header..`fun accepts(contentType: `[`ContentType`](../-content-type/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
