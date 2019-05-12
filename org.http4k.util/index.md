[http4k](../index.md) / [org.http4k.util](./index.md)

## Package org.http4k.util

Presumed homeless code used across the rest of the library.

### Types

| Name | Summary |
|---|---|
| [Appendable](-appendable/index.md) | `class Appendable<T>` |
| [JacksonJsonSchemaCreator](-jackson-json-schema-creator/index.md) | `class JacksonJsonSchemaCreator : `[`JsonSchemaCreator`](-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, JsonNode>` |
| [JsonSchema](-json-schema/index.md) | `data class JsonSchema<out NODE>` |
| [JsonSchemaCreator](-json-schema-creator/index.md) | `interface JsonSchemaCreator<IN, OUT>` |
| [JsonToJsonSchema](-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](-json-schema-creator/index.md)`<`[`NODE`](-json-to-json-schema/index.md#NODE)`, `[`NODE`](-json-to-json-schema/index.md#NODE)`>` |

### Exceptions

| Name | Summary |
|---|---|
| [IllegalSchemaException](-illegal-schema-exception/index.md) | `class IllegalSchemaException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
