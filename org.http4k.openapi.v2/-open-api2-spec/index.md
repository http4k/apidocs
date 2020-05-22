[http4k](../../index.md) / [org.http4k.openapi.v2](../index.md) / [OpenApi2Spec](./index.md)

# OpenApi2Spec

`data class OpenApi2Spec`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi2Spec(info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md)`, paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi2PathSpec`](../-open-api2-path-spec/index.md)`>>, definitions: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md)`> = emptyMap(), parameters: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi2ParameterSpec`](../-open-api2-parameter-spec/index.md)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `val definitions: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md)`>` |
| [info](info.md) | `val info: `[`InfoSpec`](../../org.http4k.openapi/-info-spec/index.md) |
| [parameters](parameters.md) | `val parameters: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi2ParameterSpec`](../-open-api2-parameter-spec/index.md)`>` |
| [paths](paths.md) | `val paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OpenApi2PathSpec`](../-open-api2-path-spec/index.md)`>>` |

### Extension Functions

| Name | Summary |
|---|---|
| [asV3](../as-v3.md) | `fun `[`OpenApi2Spec`](./index.md)`.asV3(): `[`OpenApi3Spec`](../../org.http4k.openapi.v3/-open-api3-spec/index.md) |
| [flatten](../flatten.md) | `fun `[`OpenApi2Spec`](./index.md)`.flatten(): `[`OpenApi2Spec`](./index.md) |
