[http4k](../index.md) / [org.http4k.openapi.v3](./index.md)

## Package org.http4k.openapi.v3

### Types

| Name | Summary |
|---|---|
| [ApiGenerator](-api-generator.md) | `interface ApiGenerator : (`[`OpenApi3Spec`](-open-api3-spec/index.md)`, `[`GenerationOptions`](-generation-options/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FileSpec>` |
| [ComponentsSpec](-components-spec/index.md) | `data class ComponentsSpec` |
| [GenerationOptions](-generation-options/index.md) | `data class GenerationOptions` |
| [InfoSpec](-info-spec/index.md) | `data class InfoSpec` |
| [MessageBodySpec](-message-body-spec/index.md) | `data class MessageBodySpec` |
| [NamedSchema](-named-schema/index.md) | `sealed class NamedSchema` |
| [OpenApi3Spec](-open-api3-spec/index.md) | `data class OpenApi3Spec` |
| [OpenApiJson](-open-api-json.md) | `object OpenApiJson : `[`ConfigurableJackson`](../org.http4k.format/-configurable-jackson/index.md) |
| [ParameterSpec](-parameter-spec/index.md) | `sealed class ParameterSpec` |
| [Path](-path/index.md) | Convenience type for working with generated code`data class Path` |
| [PathSpec](-path-spec/index.md) | `data class PathSpec` |
| [RequestBodySpec](-request-body-spec/index.md) | `data class RequestBodySpec` |
| [ResponseSpec](-response-spec/index.md) | `data class ResponseSpec` |
| [SchemaSpec](-schema-spec/index.md) | `sealed class SchemaSpec` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [apiName](api-name.md) | `fun `[`OpenApi3Spec`](-open-api3-spec/index.md)`.apiName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [flattenedPaths](flattened-paths.md) | `fun `[`OpenApi3Spec`](-open-api3-spec/index.md)`.flattenedPaths(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Path`](-path/index.md)`>` |
