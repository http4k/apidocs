[http4k](../../index.md) / [org.http4k.util](../index.md) / [JsonSchemaCreator](./index.md)

# JsonSchemaCreator

`interface JsonSchemaCreator<IN, OUT>`

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `abstract fun toSchema(obj: IN, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`JsonSchema`](../-json-schema/index.md)`<OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [ApiRenderer](../../org.http4k.contract.openapi/-api-renderer/index.md) | Renders the contract contents in OpenApi JSON format.`interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](./index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>` |
| [AutoJsonToJsonSchema](../../org.http4k.contract.openapi.v3/-auto-json-to-json-schema/index.md) | `class AutoJsonToJsonSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`JsonSchemaCreator`](./index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>` |
| [JsonToJsonSchema](../../org.http4k.contract.openapi.v2/-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](./index.md)`<NODE, NODE>` |
| [JsonToJsonSchema](../../org.http4k.contract.openapi.v3/-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](./index.md)`<NODE, NODE>` |
