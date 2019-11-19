[http4k](../../index.md) / [org.http4k.core](../index.md) / [ContentType](./index.md)

# ContentType

`data class ContentType` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/ContentType.kt#L5)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ContentType(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, directives: `[`Parameters`](../-parameters.md)` = emptyList())` |

### Properties

| Name | Summary |
|---|---|
| [directives](directives.md) | `val directives: `[`Parameters`](../-parameters.md) |
| [value](value.md) | `val value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [equalsIgnoringDirectives](equals-ignoring-directives.md) | `fun equalsIgnoringDirectives(that: `[`ContentType`](./index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toHeaderValue](to-header-value.md) | `fun toHeaderValue(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [withNoDirectives](with-no-directives.md) | `fun withNoDirectives(): `[`ContentType`](./index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [APPLICATION_FORM_URLENCODED](-a-p-p-l-i-c-a-t-i-o-n_-f-o-r-m_-u-r-l-e-n-c-o-d-e-d.md) | `val APPLICATION_FORM_URLENCODED: `[`ContentType`](./index.md) |
| [APPLICATION_JSON](-a-p-p-l-i-c-a-t-i-o-n_-j-s-o-n.md) | `val APPLICATION_JSON: `[`ContentType`](./index.md) |
| [APPLICATION_PDF](-a-p-p-l-i-c-a-t-i-o-n_-p-d-f.md) | `val APPLICATION_PDF: `[`ContentType`](./index.md) |
| [APPLICATION_XML](-a-p-p-l-i-c-a-t-i-o-n_-x-m-l.md) | `val APPLICATION_XML: `[`ContentType`](./index.md) |
| [MULTIPART_FORM_DATA](-m-u-l-t-i-p-a-r-t_-f-o-r-m_-d-a-t-a.md) | `val MULTIPART_FORM_DATA: `[`ContentType`](./index.md) |
| [OCTET_STREAM](-o-c-t-e-t_-s-t-r-e-a-m.md) | `val OCTET_STREAM: `[`ContentType`](./index.md) |
| [TEXT_HTML](-t-e-x-t_-h-t-m-l.md) | `val TEXT_HTML: `[`ContentType`](./index.md) |
| [TEXT_PLAIN](-t-e-x-t_-p-l-a-i-n.md) | `val TEXT_PLAIN: `[`ContentType`](./index.md) |
| [TEXT_XML](-t-e-x-t_-x-m-l.md) | `val TEXT_XML: `[`ContentType`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [MultipartFormWithBoundary](-multipart-form-with-boundary.md) | `fun MultipartFormWithBoundary(boundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContentType`](./index.md) |
| [MultipartMixedWithBoundary](-multipart-mixed-with-boundary.md) | `fun MultipartMixedWithBoundary(boundary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContentType`](./index.md) |
| [Text](-text.md) | `fun Text(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, charset: `[`Charset`](https://docs.oracle.com/javase/9/docs/api/java/nio/charset/Charset.html)`? = Charsets.UTF_8): `[`ContentType`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |
