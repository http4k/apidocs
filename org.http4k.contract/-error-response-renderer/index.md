[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ErrorResponseRenderer](./index.md)

# ErrorResponseRenderer

`interface ErrorResponseRenderer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/contract/ErrorResponseRenderer.kt#L12)

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `open fun badRequest(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../../org.http4k.lens/-failure/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `open fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ContractRenderer](../-contract-renderer/index.md) | `interface ContractRenderer : `[`ErrorResponseRenderer`](./index.md) |
| [JsonErrorResponseRenderer](../-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<NODE> : `[`ErrorResponseRenderer`](./index.md) |
| [OpenApi2](../../org.http4k.contract.openapi.v2/-open-api2/index.md) | `open class OpenApi2<out NODE> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md)<br>Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees. |
| [OpenApi3](../../org.http4k.contract.openapi.v3/-open-api3/index.md) | `class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md)<br>Contract renderer for OpenApi3 format JSON. By default, for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees. |
| [SimpleJson](../../org.http4k.contract.simple/-simple-json/index.md) | `class SimpleJson<out NODE> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md) |
