[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [OpenApi3Spec](./index.md)

# OpenApi3Spec

`data class OpenApi3Spec`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi3Spec(info: `[`InfoSpec`](../-info-spec/index.md)`, paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`PathSpec`](../-path-spec/index.md)`>>, components: `[`ComponentsSpec`](../-components-spec/index.md)` = ComponentsSpec())` |

### Properties

| Name | Summary |
|---|---|
| [components](components.md) | `val components: `[`ComponentsSpec`](../-components-spec/index.md) |
| [info](info.md) | `val info: `[`InfoSpec`](../-info-spec/index.md) |
| [paths](paths.md) | `val paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`PathSpec`](../-path-spec/index.md)`>>` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildApi](../../org.http4k.openapi.v3.server/build-api.md) | `fun `[`OpenApi3Spec`](./index.md)`.buildApi(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): CodeBlock` |
| [buildEndpoint](../../org.http4k.openapi.v3.server/build-endpoint.md) | `fun `[`OpenApi3Spec`](./index.md)`.buildEndpoint(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, pathSpec: `[`PathSpec`](../-path-spec/index.md)`): FunSpec` |
| [buildEndpoints](../../org.http4k.openapi.v3.server/build-endpoints.md) | `fun `[`OpenApi3Spec`](./index.md)`.buildEndpoints(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>` |
| [buildServer](../../org.http4k.openapi.v3.server/build-server.md) | `fun `[`OpenApi3Spec`](./index.md)`.buildServer(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): TypeSpec` |
| [function](../../org.http4k.openapi.v3.client/function.md) | `fun `[`OpenApi3Spec`](./index.md)`.function(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, pathSpec: `[`PathSpec`](../-path-spec/index.md)`): FunSpec` |
| [functions](../../org.http4k.openapi.v3.client/functions.md) | `fun `[`OpenApi3Spec`](./index.md)`.functions(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>` |
| [lensDeclarations](../../org.http4k.poet/lens-declarations.md) | `fun `[`OpenApi3Spec`](./index.md)`.lensDeclarations(pathSpec: `[`PathSpec`](../-path-spec/index.md)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
