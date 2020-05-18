[http4k](../../index.md) / [org.http4k.openapi.v2](../index.md) / [PathV2](./index.md)

# PathV2

`data class PathV2`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathV2(urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, pathV2Spec: `[`PathV2Spec`](../-path-v2-spec/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [pathV2Spec](path-v2-spec.md) | `val pathV2Spec: `[`PathV2Spec`](../-path-v2-spec/index.md) |
| [urlPathPattern](url-path-pattern.md) | `val urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [allSchemas](all-schemas.md) | `fun allSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
| [requestSchemas](request-schemas.md) | `fun requestSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
| [responseSchemas](response-schemas.md) | `fun responseSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
