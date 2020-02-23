[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [JsonToJsonSchema](./index.md)

# JsonToJsonSchema

`class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<NODE, NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonToJsonSchema(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, refPrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "components/schemas")` |

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `fun toSchema(obj: NODE, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<NODE>` |
