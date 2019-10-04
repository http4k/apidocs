[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [OpenApi3ApiRenderer](./index.md)

# OpenApi3ApiRenderer

`class OpenApi3ApiRenderer<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](../-api/index.md)`<`[`NODE`](index.md#NODE)`>, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/OpenApi3ApiRenderer.kt#L18)

Converts a API to OpenApi3 format JSON.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi3ApiRenderer(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>)`<br>Converts a API to OpenApi3 format JSON. |

### Functions

| Name | Summary |
|---|---|
| [api](api.md) | `fun api(api: `[`Api`](../-api/index.md)`<`[`NODE`](index.md#NODE)`>): `[`NODE`](index.md#NODE) |
| [toSchema](to-schema.md) | `fun toSchema(obj: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, overrideDefinitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`JsonSchema`](../../org.http4k.util/-json-schema/index.md)`<`[`NODE`](index.md#NODE)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [cached](../../org.http4k.contract.openapi/cached.md) | `fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`API`](../../org.http4k.contract.openapi/cached.md#API)`, `[`NODE`](../../org.http4k.contract.openapi/cached.md#NODE)`>.cached(): `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`API`](../../org.http4k.contract.openapi/cached.md#API)`, `[`NODE`](../../org.http4k.contract.openapi/cached.md#NODE)`>`<br>Cache the result of the API render, in case it is expensive to calculate. |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
