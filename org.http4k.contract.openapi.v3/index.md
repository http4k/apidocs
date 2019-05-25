[http4k](../index.md) / [org.http4k.contract.openapi.v3](./index.md)

## Package org.http4k.contract.openapi.v3

### Types

| Name | Summary |
|---|---|
| [Api](-api/index.md) | `data class Api<NODE>` |
| [ApiPath](-api-path/index.md) | `sealed class ApiPath<NODE>` |
| [AutoJsonToJsonSchema](-auto-json-to-json-schema/index.md) | `class AutoJsonToJsonSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](-auto-json-to-json-schema/index.md#NODE)`>` |
| [BodyContent](-body-content/index.md) | `sealed class BodyContent` |
| [Components](-components/index.md) | `data class Components<NODE>` |
| [HasSchema](-has-schema/index.md) | `interface HasSchema<NODE>` |
| [JsonToJsonSchema](-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`NODE`](-json-to-json-schema/index.md#NODE)`, `[`NODE`](-json-to-json-schema/index.md#NODE)`>` |
| [OpenApi3](-open-api3/index.md) | `class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../org.http4k.contract/-error-response-renderer/index.md)<br>Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed. |
| [OpenApi3ApiRenderer](-open-api3-api-renderer/index.md) | `class OpenApi3ApiRenderer<NODE> : `[`ApiRenderer`](../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](-api/index.md)`<`[`NODE`](-open-api3-api-renderer/index.md#NODE)`>, `[`NODE`](-open-api3-api-renderer/index.md#NODE)`>`<br>Converts a API to OpenApi3 format JSON. |
| [OpenApi3SecurityRenderer](-open-api3-security-renderer/index.md) | `object OpenApi3SecurityRenderer : `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
| [RequestContents](-request-contents/index.md) | `class RequestContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<`[`NODE`](-request-contents/index.md#NODE)`>` |
| [RequestParameter](-request-parameter/index.md) | `sealed class RequestParameter<NODE>` |
| [ResponseContents](-response-contents/index.md) | `class ResponseContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<`[`NODE`](-response-contents/index.md#NODE)`>` |
