[http4k](../index.md) / [org.http4k.contract.openapi.v2](./index.md)

## Package org.http4k.contract.openapi.v2

### Types

| Name | Summary |
|---|---|
| [JsonToJsonSchema](-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`NODE`](-json-to-json-schema/index.md#NODE)`, `[`NODE`](-json-to-json-schema/index.md#NODE)`>` |
| [OpenApi2](-open-api2/index.md) | `open class OpenApi2<out NODE> : `[`ContractRenderer`](../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../org.http4k.contract/-error-response-renderer/index.md)<br>Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees. |

### Properties

| Name | Summary |
|---|---|
| [OpenApi2SecurityRenderer](-open-api2-security-renderer.md) | `val OpenApi2SecurityRenderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>Compose the supported Security models |

### Companion Object Properties

| Name | Summary |
|---|---|
| [renderer](renderer.md) | `val ApiKeySecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val BasicAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
