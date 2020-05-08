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
| [OpenApi3Spec](-open-api3-spec/index.md) | `data class OpenApi3Spec` |
| [OpenApiJson](-open-api-json.md) | `object OpenApiJson : `[`ConfigurableJackson`](../org.http4k.format/-configurable-jackson/index.md) |
| [ParameterSpec](-parameter-spec/index.md) | `sealed class ParameterSpec` |
| [PathSpec](-path-spec/index.md) | `data class PathSpec` |
| [RequestBodySpec](-request-body-spec/index.md) | `data class RequestBodySpec` |
| [SchemaSpec](-schema-spec/index.md) | `sealed class SchemaSpec` |

### Properties

| Name | Summary |
|---|---|
| [httpHandler](http-handler.md) | `val httpHandler: `[`Property`](../org.http4k.poet/-property/index.md) |

### Functions

| Name | Summary |
|---|---|
| [main](main.md) | `fun main(args: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
