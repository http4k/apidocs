[http4k](../index.md) / [org.http4k.contract.openapi](./index.md)

## Package org.http4k.contract.openapi

### Types

| Name | Summary |
|---|---|
| [ApiInfo](-api-info/index.md) | `data class ApiInfo` |
| [ApiRenderer](-api-renderer/index.md) | `interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](-api-renderer/index.md#NODE)`>`<br>Renders the contract contents in OpenApi JSON format. |
| [RenderModes](-render-modes/index.md) | `interface RenderModes` |
| [SecurityRenderer](-security-renderer/index.md) | `interface SecurityRenderer`<br>Provides rendering of Security models in to OpenApi specs. |

### Type Aliases

| Name | Summary |
|---|---|
| [Render](-render.md) | `typealias Render<NODE> = `[`Json`](../org.http4k.format/-json/index.md)`<`[`NODE`](-render.md#NODE)`>.() -> `[`NODE`](-render.md#NODE) |

### Functions

| Name | Summary |
|---|---|
| [cached](cached.md) | `fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](-api-renderer/index.md)`<`[`API`](cached.md#API)`, `[`NODE`](cached.md#NODE)`>.cached(): `[`ApiRenderer`](-api-renderer/index.md)`<`[`API`](cached.md#API)`, `[`NODE`](cached.md#NODE)`>`<br>Cache the result of the API render, in case it is expensive to calculate. |
| [operationId](operation-id.md) | `fun `[`ContractRoute`](../org.http4k.contract/-contract-route/index.md)`.operationId(contractRoot: `[`PathSegments`](../org.http4k.contract/-path-segments/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rendererFor](renderer-for.md) | `fun <T : `[`Security`](../org.http4k.contract.security/-security/index.md)`> rendererFor(fn: (`[`T`](renderer-for.md#T)`) -> `[`RenderModes`](-render-modes/index.md)`): `[`SecurityRenderer`](-security-renderer/index.md) |
