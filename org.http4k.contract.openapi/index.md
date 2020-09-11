[http4k](../index.md) / [org.http4k.contract.openapi](./index.md)

## Package org.http4k.contract.openapi

Rendering for OpenAPI specifications

### Types

| Name | Summary |
|---|---|
| [ApiInfo](-api-info/index.md) | `data class ApiInfo` |
| [ApiRenderer](-api-renderer/index.md) | Renders the contract contents in OpenApi JSON format.`interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>` |
| [OpenApiExtension](-open-api-extension/index.md) | Provides a way to apply extensions to the OpenAPI JSON document.`interface OpenApiExtension` |
| [Render](-render.md) | `typealias Render<NODE> = `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.() -> NODE` |
| [RenderModes](-render-modes/index.md) | `interface RenderModes` |
| [SecurityRenderer](-security-renderer/index.md) | Provides rendering of Security models in to OpenApi specs.`interface SecurityRenderer` |

### Functions

| Name | Summary |
|---|---|
| [cached](cached.md) | Cache the result of the API render, in case it is expensive to calculate.`fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](-api-renderer/index.md)`<API, NODE>.cached(): `[`ApiRenderer`](-api-renderer/index.md)`<API, NODE>` |
| [operationId](operation-id.md) | `fun `[`ContractRoute`](../org.http4k.contract/-contract-route/index.md)`.operationId(contractRoot: `[`PathSegments`](../org.http4k.contract/-path-segments/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rendererFor](renderer-for.md) | `fun <T : `[`Security`](../org.http4k.contract.security/-security/index.md)`> rendererFor(fn: (T) -> `[`RenderModes`](-render-modes/index.md)`): `[`SecurityRenderer`](-security-renderer/index.md) |
