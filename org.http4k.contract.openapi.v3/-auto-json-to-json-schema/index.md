[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [AutoJsonToJsonSchema](./index.md)

# AutoJsonToJsonSchema

`class AutoJsonToJsonSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/AutoJsonToJsonSchema.kt#L16)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoJsonToJsonSchema(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>, refPrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "components/schemas", fieldRetrieval: `[`FieldRetrieval`](../-field-retrieval/index.md)` = FieldRetrieval.compose(SimpleLookup))` |

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<`[`NODE`](index.md#NODE)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
