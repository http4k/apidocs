[http4k](../../index.md) / [org.http4k.util](../index.md) / [JacksonJsonSchemaCreator](./index.md)

# JacksonJsonSchemaCreator

`class JacksonJsonSchemaCreator : `[`JsonSchemaCreator`](../-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, JsonNode>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/util/JacksonJsonSchemaCreator.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JacksonJsonSchemaCreator(json: `[`ConfigurableJackson`](../../org.http4k.format/-configurable-jackson/index.md)` = Jackson, refPrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "components/schemas")` |

### Functions

| Name | Summary |
|---|---|
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../-json-schema/index.md)`<JsonNode>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
