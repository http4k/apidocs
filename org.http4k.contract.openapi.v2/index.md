[http4k](../index.md) / [org.http4k.contract.openapi.v2](./index.md)

## Package org.http4k.contract.openapi.v2

### Types

| Name | Summary |
|---|---|
| [JsonToJsonSchema](-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<NODE, NODE>` |
| [OpenApi2](-open-api2/index.md) | Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees.`open class OpenApi2<out NODE> : `[`ContractRenderer`](../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../org.http4k.contract/-error-response-renderer/index.md) |

### Properties

| Name | Summary |
|---|---|
| [OpenApi2SecurityRenderer](-open-api2-security-renderer.md) | Compose the supported Security models`val OpenApi2SecurityRenderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
| [value](value.md) | `val `[`ParamMeta`](../org.http4k.lens/-param-meta/index.md)`.value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [OpenApi2](-open-api2.md) | Defaults for configuring OpenApi2 with Jackson`fun OpenApi2(apiInfo: `[`ApiInfo`](../org.http4k.contract.openapi/-api-info/index.md)`, baseUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, json: `[`Jackson`](../org.http4k.format/-jackson.md)`, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList()): `[`OpenApi2`](-open-api2/index.md)`<JsonNode>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [renderer](renderer.md) | `val ApiKeySecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val BasicAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val ImplicitOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
