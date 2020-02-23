[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [OpenApi3ApiRenderer](./index.md)

# OpenApi3ApiRenderer

`class OpenApi3ApiRenderer<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](../-api/index.md)`<NODE>, NODE>`

Converts a API to OpenApi3 format JSON.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Converts a API to OpenApi3 format JSON.`OpenApi3ApiRenderer(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>)` |

### Functions

| Name | Summary |
|---|---|
| [api](api.md) | `fun api(api: `[`Api`](../-api/index.md)`<NODE>): NODE` |
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<NODE>` |

### Extension Functions

| Name | Summary |
|---|---|
| [cached](../../org.http4k.contract.openapi/cached.md) | Cache the result of the API render, in case it is expensive to calculate.`fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<API, NODE>.cached(): `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<API, NODE>` |
