[http4k](../index.md) / [org.http4k.contract.openapi.v3](./index.md)

## Package org.http4k.contract.openapi.v3

### Types

| Name | Summary |
|---|---|
| [Api](-api/index.md) | `data class Api<NODE>` |
| [ApiPath](-api-path/index.md) | `data class ApiPath<NODE>` |
| [BodyContent](-body-content/index.md) | `sealed class BodyContent` |
| [Components](-components/index.md) | `data class Components<NODE>` |
| [HasSchema](-has-schema/index.md) | `interface HasSchema<NODE>` |
| [OpenApi3](-open-api3/index.md) | `class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../org.http4k.contract/-error-response-renderer/index.md)<br>Contract renderer for OpenApi3 format JSON. By default, for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees. |
| [OpenApi3ApiRenderer](-open-api3-api-renderer/index.md) | `class OpenApi3ApiRenderer<NODE> : `[`ApiRenderer`](../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](-api/index.md)`<`[`NODE`](-open-api3-api-renderer/index.md#NODE)`>, `[`NODE`](-open-api3-api-renderer/index.md#NODE)`>`<br>Converts a API to OpenApi3 format JSON. |
| [OpenApi3SecurityRenderer](-open-api3-security-renderer/index.md) | `object OpenApi3SecurityRenderer : `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
| [RequestContents](-request-contents/index.md) | `class RequestContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<`[`NODE`](-request-contents/index.md#NODE)`>` |
| [RequestParameter](-request-parameter/index.md) | `sealed class RequestParameter<NODE>` |
| [ResponseContents](-response-contents/index.md) | `class ResponseContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<`[`NODE`](-response-contents/index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [OpenApi3](-open-api3.md) | `fun OpenApi3(apiInfo: `[`ApiInfo`](../org.http4k.contract.openapi/-api-info/index.md)`, jackson: `[`ConfigurableJackson`](../org.http4k.format/-configurable-jackson/index.md)` = Jackson): `[`OpenApi3`](-open-api3/index.md)`<JsonNode>` |
