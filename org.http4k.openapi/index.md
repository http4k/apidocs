[http4k](../index.md) / [org.http4k.openapi](./index.md)

## Package org.http4k.openapi

### Types

| Name | Summary |
|---|---|
| [ApiGenerator](-api-generator.md) | `interface ApiGenerator<T> : (T, `[`GenerationOptions`](-generation-options/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FileSpec>` |
| [GenerationOptions](-generation-options/index.md) | `data class GenerationOptions` |
| [InfoSpec](-info-spec/index.md) | `data class InfoSpec` |
| [NamedSchema](-named-schema/index.md) | `sealed class NamedSchema` |
| [OpenApiJson](-open-api-json.md) | `object OpenApiJson : `[`ConfigurableJackson`](../org.http4k.format/-configurable-jackson/index.md) |
| [SchemaSpec](-schema-spec/index.md) | `sealed class SchemaSpec` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [buildModelClass](build-model-class.md) | `fun `[`SchemaSpec`](-schema-spec/index.md)`.buildModelClass(className: ClassName, allSchemas: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](-schema-spec/index.md)`>, generated: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, TypeSpec>): TypeSpec` |
| [namedSchema](named-schema.md) | `fun `[`SchemaSpec`](-schema-spec/index.md)`.namedSchema(modelName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NamedSchema`](-named-schema/index.md) |
