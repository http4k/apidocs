[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [OpenApi3](./index.md)

# OpenApi3

`class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/OpenApi3.kt#L46)

Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of
object models will default to either reflective or hashcode based depending on if a Auto Json
is passed.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenApi3(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList())``OpenApi3(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList(), apiRenderer: `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](../-api/index.md)`<`[`NODE`](index.md#NODE)`>, `[`NODE`](index.md#NODE)`> = OpenApi3ApiRenderer(json), securityRenderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md)` = OpenApi3SecurityRenderer, errorResponseRenderer: `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)` = JsonErrorResponseRenderer(json))`<br>Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed. |

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `fun description(contractRoot: `[`PathSegments`](../../org.http4k.contract/-path-segments/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../../org.http4k.contract/-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
