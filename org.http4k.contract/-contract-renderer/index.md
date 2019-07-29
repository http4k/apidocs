[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRenderer](./index.md)

# ContractRenderer

`interface ContractRenderer : `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRenderer.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `abstract fun description(contractRoot: `[`PathSegments`](../-path-segments/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [badRequest](../-error-response-renderer/bad-request.md) | `open fun badRequest(lensFailure: `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](../-error-response-renderer/not-found.md) | `open fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [NoRenderer](../-no-renderer/index.md) | `object NoRenderer : `[`ContractRenderer`](./index.md) |
| [OpenApi2](../../org.http4k.contract.openapi.v2/-open-api2/index.md) | `open class OpenApi2<out NODE> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md)<br>Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees. |
| [OpenApi3](../../org.http4k.contract.openapi.v3/-open-api3/index.md) | `class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md)<br>Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed. |
| [SimpleJson](../../org.http4k.contract.simple/-simple-json/index.md) | `class SimpleJson<out NODE> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) |
