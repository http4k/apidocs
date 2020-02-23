[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [ApiRenderer](./index.md)

# ApiRenderer

`interface ApiRenderer<API, NODE> : `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE>`

Renders the contract contents in OpenApi JSON format.

### Functions

| Name | Summary |
|---|---|
| [api](api.md) | `abstract fun api(api: API): NODE` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Auto](-auto.md) | ApiRenderer which uses auto-marshalling JSON to create JSON schema for message models.`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Auto(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<NODE>, schema: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE> = AutoJsonToJsonSchema(json)): `[`ApiRenderer`](./index.md)`<T, NODE>` |

### Extension Functions

| Name | Summary |
|---|---|
| [cached](../cached.md) | Cache the result of the API render, in case it is expensive to calculate.`fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](./index.md)`<API, NODE>.cached(): `[`ApiRenderer`](./index.md)`<API, NODE>` |

### Inheritors

| Name | Summary |
|---|---|
| [OpenApi3ApiRenderer](../../org.http4k.contract.openapi.v3/-open-api3-api-renderer/index.md) | Converts a API to OpenApi3 format JSON.`class OpenApi3ApiRenderer<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ApiRenderer`](./index.md)`<`[`Api`](../../org.http4k.contract.openapi.v3/-api/index.md)`<NODE>, NODE>` |
