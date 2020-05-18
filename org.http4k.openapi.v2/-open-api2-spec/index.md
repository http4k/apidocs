[http4k](../../index.md) / [org.http4k.openapi.v2](../index.md) / [OpenApi2Spec](./index.md)

# OpenApi2Spec

`data class OpenApi2Spec`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi2Spec(info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md)`, paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`PathV2Spec`](../-path-v2-spec/index.md)`>>, definitions: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md)`>?)` |

### Properties

| Name | Summary |
|---|---|
| [components](components.md) | `val components: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md)`>` |
| [info](info.md) | `val info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md) |
| [paths](paths.md) | `val paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`PathV2Spec`](../-path-v2-spec/index.md)`>>` |

### Extension Functions

| Name | Summary |
|---|---|
| [flattenedPaths](../flattened-paths.md) | `fun `[`OpenApi2Spec`](./index.md)`.flattenedPaths(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PathV2`](../-path-v2/index.md)`>` |
