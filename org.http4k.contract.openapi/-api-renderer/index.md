[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [ApiRenderer](./index.md)

# ApiRenderer

`interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/ApiRenderer.kt#L10)

Renders the contract contents in OpenApi JSON format.

### Functions

| Name | Summary |
|---|---|
| [api](api.md) | `abstract fun api(api: `[`API`](index.md#API)`): `[`NODE`](index.md#NODE) |

### Inherited Functions

| Name | Summary |
|---|---|
| [toSchema](../../org.http4k.util/-json-schema-creator/to-schema.md) | `abstract fun toSchema(obj: `[`IN`](../../org.http4k.util/-json-schema-creator/index.md#IN)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<`[`OUT`](../../org.http4k.util/-json-schema-creator/index.md#OUT)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Auto](-auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Auto(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](-auto.md#NODE)`>, schema: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](-auto.md#NODE)`>): `[`ApiRenderer`](./index.md)`<`[`T`](-auto.md#T)`, `[`NODE`](-auto.md#NODE)`>`<br>ApiRenderer which uses auto-marshalling JSON to create JSON schema for message models. |

### Extension Functions

| Name | Summary |
|---|---|
| [cached](../cached.md) | `fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](./index.md)`<`[`API`](../cached.md#API)`, `[`NODE`](../cached.md#NODE)`>.cached(): `[`ApiRenderer`](./index.md)`<`[`API`](../cached.md#API)`, `[`NODE`](../cached.md#NODE)`>`<br>Cache the result of the API render, in case it is expensive to calculate. |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [OpenApi3ApiRenderer](../../org.http4k.contract.openapi.v3/-open-api3-api-renderer/index.md) | `class OpenApi3ApiRenderer<NODE> : `[`ApiRenderer`](./index.md)`<`[`Api`](../../org.http4k.contract.openapi.v3/-api/index.md)`<`[`NODE`](../../org.http4k.contract.openapi.v3/-open-api3-api-renderer/index.md#NODE)`>, `[`NODE`](../../org.http4k.contract.openapi.v3/-open-api3-api-renderer/index.md#NODE)`>`<br>Converts a API to OpenApi3 format JSON. |
