[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [AutoJsonToJsonSchema](./index.md)

# AutoJsonToJsonSchema

`class AutoJsonToJsonSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoJsonToJsonSchema(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<NODE>, fieldRetrieval: `[`FieldRetrieval`](../-field-retrieval/index.md)` = FieldRetrieval.compose(SimpleLookup), modelNamer: `[`SchemaModelNamer`](../-schema-model-namer/index.md)` = SchemaModelNamer.Simple, refPrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "components/schemas")` |

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<NODE>` |
