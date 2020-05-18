[http4k](../index.md) / [org.http4k.openapi.v3.server](./index.md)

## Package org.http4k.openapi.v3.server

### Types

| Name | Summary |
|---|---|
| [ServerApiGenerator](-server-api-generator/index.md) | `object ServerApiGenerator : `[`ApiGenerator`](../org.http4k.openapi/-api-generator.md)`<`[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [buildApi](build-api.md) | `fun buildApi(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): CodeBlock` |
| [buildEndpoint](build-endpoint.md) | `fun `[`PathV3`](../org.http4k.openapi.v3/-path-v3/index.md)`.buildEndpoint(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FunSpec` |
| [buildServer](build-server.md) | `fun `[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md)`.buildServer(endpoints: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FunSpec>): TypeSpec` |
