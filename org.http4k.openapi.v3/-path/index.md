[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [Path](./index.md)

# Path

`data class Path`

Convenience type for working with generated code

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Convenience type for working with generated code`Path(urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, pathSpec: `[`PathSpec`](../-path-spec/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [pathSpec](path-spec.md) | `val pathSpec: `[`PathSpec`](../-path-spec/index.md) |
| [uniqueName](unique-name.md) | `val uniqueName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [urlPathPattern](url-path-pattern.md) | `val urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [allSchemas](all-schemas.md) | `fun allSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../-named-schema/index.md)`>` |
| [requestSchemas](request-schemas.md) | `fun requestSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../-named-schema/index.md)`>` |
| [responseSchemas](response-schemas.md) | `fun responseSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../-named-schema/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildEndpoint](../../org.http4k.openapi.v3.server/build-endpoint.md) | `fun `[`Path`](./index.md)`.buildEndpoint(): FunSpec` |
| [function](../../org.http4k.openapi.v3.client/function.md) | `fun `[`Path`](./index.md)`.function(): FunSpec` |
| [lensDeclarations](../../org.http4k.poet/lens-declarations.md) | `fun `[`Path`](./index.md)`.lensDeclarations(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
