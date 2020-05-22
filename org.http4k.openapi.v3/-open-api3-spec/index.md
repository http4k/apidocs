[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [OpenApi3Spec](./index.md)

# OpenApi3Spec

`data class OpenApi3Spec`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi3Spec(info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md)`, paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi3PathSpec`](../-open-api3-path-spec/index.md)`>>, components: `[`OpenApi3ComponentsSpec`](../-open-api3-components-spec/index.md)` = OpenApi3ComponentsSpec())` |

### Properties

| Name | Summary |
|---|---|
| [components](components.md) | `val components: `[`OpenApi3ComponentsSpec`](../-open-api3-components-spec/index.md) |
| [info](info.md) | `val info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md) |
| [paths](paths.md) | `val paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi3PathSpec`](../-open-api3-path-spec/index.md)`>>` |

### Extension Functions

| Name | Summary |
|---|---|
| [apiName](../api-name.md) | `fun `[`OpenApi3Spec`](./index.md)`.apiName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [buildServer](../../org.http4k.openapi.v3.server/build-server.md) | `fun `[`OpenApi3Spec`](./index.md)`.buildServer(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): TypeSpec` |
| [flatten](../flatten.md) | `fun `[`OpenApi3Spec`](./index.md)`.flatten(): `[`OpenApi3Spec`](./index.md) |
| [flattenedPaths](../flattened-paths.md) | `fun `[`OpenApi3Spec`](./index.md)`.flattenedPaths(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Path`](../-path/index.md)`>` |
