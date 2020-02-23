[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ErrorResponseRenderer](./index.md)

# ErrorResponseRenderer

`interface ErrorResponseRenderer`

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `open fun badRequest(lensFailure: `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `open fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ContractRenderer](../-contract-renderer/index.md) | `interface ContractRenderer : `[`ErrorResponseRenderer`](./index.md) |
| [JsonErrorResponseRenderer](../-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<NODE> : `[`ErrorResponseRenderer`](./index.md) |
| [OpenApi2](../../org.http4k.contract.openapi.v2/-open-api2/index.md) | Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees.`open class OpenApi2<out NODE> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md) |
| [OpenApi3](../../org.http4k.contract.openapi.v3/-open-api3/index.md) | Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed.`class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md) |
| [SimpleJson](../../org.http4k.contract.simple/-simple-json/index.md) | `class SimpleJson<out NODE> : `[`ContractRenderer`](../-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](./index.md) |
