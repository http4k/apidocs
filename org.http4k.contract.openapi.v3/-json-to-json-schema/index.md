[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [JsonToJsonSchema](./index.md)

# JsonToJsonSchema

`class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/JsonToJsonSchema.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonToJsonSchema(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>, refPrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "components/schemas")` |

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`NODE`](index.md#NODE)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<`[`NODE`](index.md#NODE)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
