[http4k](../index.md) / [org.http4k.contract.openapi.v3](./index.md)

## Package org.http4k.contract.openapi.v3

### Types

| Name | Summary |
|---|---|
| [Api](-api/index.md) | `data class Api<NODE>` |
| [ApiPath](-api-path/index.md) | `sealed class ApiPath<NODE>` |
| [AutoJsonToJsonSchema](-auto-json-to-json-schema/index.md) | `class AutoJsonToJsonSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>` |
| [BodyContent](-body-content/index.md) | `sealed class BodyContent` |
| [Components](-components/index.md) | `data class Components<NODE>` |
| [Field](-field/index.md) | `data class Field` |
| [FieldMetadata](-field-metadata/index.md) | `data class FieldMetadata` |
| [FieldMetadataRetrievalStrategy](-field-metadata-retrieval-strategy.md) | `interface FieldMetadataRetrievalStrategy : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`FieldMetadata`](-field-metadata/index.md) |
| [FieldRetrieval](-field-retrieval/index.md) | `interface FieldRetrieval : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Field`](-field/index.md) |
| [HasSchema](-has-schema/index.md) | `interface HasSchema<NODE>` |
| [JacksonFieldMetadataRetrievalStrategy](-jackson-field-metadata-retrieval-strategy/index.md) | `object JacksonFieldMetadataRetrievalStrategy : `[`FieldMetadataRetrievalStrategy`](-field-metadata-retrieval-strategy.md) |
| [JacksonJsonNamingAnnotated](-jackson-json-naming-annotated/index.md) | `class JacksonJsonNamingAnnotated : `[`FieldRetrieval`](-field-retrieval/index.md) |
| [JacksonJsonPropertyAnnotated](-jackson-json-property-annotated/index.md) | `object JacksonJsonPropertyAnnotated : `[`FieldRetrieval`](-field-retrieval/index.md) |
| [JsonToJsonSchema](-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../org.http4k.util/-json-schema-creator/index.md)`<NODE, NODE>` |
| [NoOpFieldMetadataRetrievalStrategy](-no-op-field-metadata-retrieval-strategy/index.md) | `class NoOpFieldMetadataRetrievalStrategy : `[`FieldMetadataRetrievalStrategy`](-field-metadata-retrieval-strategy.md) |
| [OpenApi3](-open-api3/index.md) | Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed.`class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../org.http4k.contract/-error-response-renderer/index.md) |
| [OpenApi3ApiRenderer](-open-api3-api-renderer/index.md) | Converts a API to OpenApi3 format JSON.`class OpenApi3ApiRenderer<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ApiRenderer`](../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](-api/index.md)`<NODE>, NODE>` |
| [RequestContents](-request-contents/index.md) | `class RequestContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<NODE>` |
| [RequestParameter](-request-parameter/index.md) | `sealed class RequestParameter<NODE>` |
| [ResponseContents](-response-contents/index.md) | `class ResponseContents<NODE> : `[`HasSchema`](-has-schema/index.md)`<NODE>` |
| [SchemaModelNamer](-schema-model-namer/index.md) | `interface SchemaModelNamer : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [SimpleLookup](-simple-lookup/index.md) | `class SimpleLookup : `[`FieldRetrieval`](-field-retrieval/index.md) |

### Exceptions

| Name | Summary |
|---|---|
| [NoFieldFound](-no-field-found/index.md) | `class NoFieldFound : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |

### Properties

| Name | Summary |
|---|---|
| [OpenApi3SecurityRenderer](-open-api3-security-renderer.md) | Compose the supported Security models`val OpenApi3SecurityRenderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
| [value](value.md) | `val `[`ParamMeta`](../org.http4k.lens/-param-meta/index.md)`.value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [&lt;no name provided&gt;](-no name provided-.md) | `fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [AutoJsonToJsonSchema](-auto-json-to-json-schema.md) | `fun AutoJsonToJsonSchema(json: `[`Jackson`](../org.http4k.format/-jackson.md)`): `[`AutoJsonToJsonSchema`](-auto-json-to-json-schema/index.md)`<JsonNode>` |
| [OpenApi3](-open-api3.md) | Defaults for configuring OpenApi3 with Jackson`fun OpenApi3(apiInfo: `[`ApiInfo`](../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Jackson`](../org.http4k.format/-jackson.md)` = Jackson, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList()): `[`OpenApi3`](-open-api3/index.md)`<JsonNode>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [renderer](renderer.md) | `val ApiKeySecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val AuthCodeOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val BasicAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val BearerAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md)<br>`val ImplicitOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../org.http4k.contract.openapi/-security-renderer/index.md) |
