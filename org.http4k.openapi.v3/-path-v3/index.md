[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [PathV3](./index.md)

# PathV3

`data class PathV3`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathV3(urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, pathV3Spec: `[`PathV3Spec`](../-path-v3-spec/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [pathV3Spec](path-v3-spec.md) | `val pathV3Spec: `[`PathV3Spec`](../-path-v3-spec/index.md) |
| [uniqueName](unique-name.md) | `val uniqueName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [urlPathPattern](url-path-pattern.md) | `val urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [allSchemas](all-schemas.md) | `fun allSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
| [requestSchemas](request-schemas.md) | `fun requestSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
| [responseSchemas](response-schemas.md) | `fun responseSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildEndpoint](../../org.http4k.openapi.v3.server/build-endpoint.md) | `fun `[`PathV3`](./index.md)`.buildEndpoint(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FunSpec` |
| [function](../../org.http4k.openapi.v3.client/function.md) | `fun `[`PathV3`](./index.md)`.function(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FunSpec` |
| [lensDeclarations](../../org.http4k.poet/lens-declarations.md) | `fun `[`PathV3`](./index.md)`.lensDeclarations(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
