[http4k](../index.md) / [org.http4k.openapi.server](./index.md)

## Package org.http4k.openapi.server

### Types

| Name | Summary |
|---|---|
| [ServerApiGenerator](-server-api-generator/index.md) | `object ServerApiGenerator : `[`ApiGenerator`](../org.http4k.openapi/-api-generator.md) |

### Functions

| Name | Summary |
|---|---|
| [buildApi](build-api.md) | `fun `[`OpenApi3Spec`](../org.http4k.openapi/-open-api3-spec/index.md)`.buildApi(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): CodeBlock` |
| [buildEndpoint](build-endpoint.md) | `fun `[`OpenApi3Spec`](../org.http4k.openapi/-open-api3-spec/index.md)`.buildEndpoint(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../org.http4k.core/-method/index.md)`, pathSpec: `[`PathSpec`](../org.http4k.openapi/-path-spec/index.md)`): FunSpec` |
| [buildEndpoints](build-endpoints.md) | `fun `[`OpenApi3Spec`](../org.http4k.openapi/-open-api3-spec/index.md)`.buildEndpoints(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>` |
| [buildServer](build-server.md) | `fun `[`OpenApi3Spec`](../org.http4k.openapi/-open-api3-spec/index.md)`.buildServer(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): TypeSpec` |
