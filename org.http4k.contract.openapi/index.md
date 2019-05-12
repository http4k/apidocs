[http4k](../index.md) / [org.http4k.contract.openapi](./index.md)

## Package org.http4k.contract.openapi

### Types

| Name | Summary |
|---|---|
| [ApiInfo](-api-info/index.md) | `data class ApiInfo` |
| [ApiRenderer](-api-renderer/index.md) | `interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](-api-renderer/index.md#NODE)`>`<br>Renders the contract contents in OpenApi JSON format. |
| [SecurityRenderer](-security-renderer/index.md) | `interface SecurityRenderer`<br>Provides rendering of Security models in to OpenApi specs. |

### Type Aliases

| Name | Summary |
|---|---|
| [Render](-render.md) | `typealias Render<NODE> = `[`Json`](../org.http4k.format/-json/index.md)`<`[`NODE`](-render.md#NODE)`>.() -> `[`NODE`](-render.md#NODE) |
