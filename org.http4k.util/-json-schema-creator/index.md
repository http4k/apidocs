[http4k](../../index.md) / [org.http4k.util](../index.md) / [JsonSchemaCreator](./index.md)

# JsonSchemaCreator

`interface JsonSchemaCreator<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/util/JsonSchemaCreator.kt#L3)

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `abstract fun toSchema(obj: `[`IN`](index.md#IN)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`JsonSchema`](../-json-schema/index.md)`<`[`OUT`](index.md#OUT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ApiRenderer](../../org.http4k.contract.openapi/-api-renderer/index.md) | `interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](./index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](../../org.http4k.contract.openapi/-api-renderer/index.md#NODE)`>`<br>Renders the contract contents in OpenApi JSON format. |
| [JacksonJsonSchemaCreator](../-jackson-json-schema-creator/index.md) | `class JacksonJsonSchemaCreator : `[`JsonSchemaCreator`](./index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, JsonNode>` |
| [JsonToJsonSchema](../-json-to-json-schema/index.md) | `class JsonToJsonSchema<NODE> : `[`JsonSchemaCreator`](./index.md)`<`[`NODE`](../-json-to-json-schema/index.md#NODE)`, `[`NODE`](../-json-to-json-schema/index.md#NODE)`>` |
