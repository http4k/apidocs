[http4k](../../index.md) / [org.http4k.core.etag](../index.md) / [ETagValidationRequestParser](./index.md)

# ETagValidationRequestParser

`class ETagValidationRequestParser` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/etag/ETagValidationRequestParser.kt#L21)

Implemented according to https://www.w3.org/Protocols/rfc2616/rfc2616-sec3.html#sec3.11

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ETagValidationRequestParser()`<br>Implemented according to https://www.w3.org/Protocols/rfc2616/rfc2616-sec3.html#sec3.11 |

### Companion Object Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | `fun parse(headerValue: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FieldValue`](../-field-value/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
