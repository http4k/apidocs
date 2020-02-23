[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRenderer](./index.md)

# ContractRenderer

`interface ContractRenderer : `[`ErrorResponseRenderer`](../-error-response-renderer/index.md)

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `abstract fun description(contractRoot: `[`PathSegments`](../-path-segments/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [NoRenderer](../-no-renderer/index.md) | `object NoRenderer : `[`ContractRenderer`](./index.md) |
| [OpenApi2](../../org.http4k.contract.openapi.v2/-open-api2/index.md) | Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of object models is used as the input relies on JSON objects and not JVM classees.`open class OpenApi2<out NODE> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) |
| [OpenApi3](../../org.http4k.contract.openapi.v3/-open-api3/index.md) | Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of object models will default to either reflective or hashcode based depending on if a Auto Json is passed.`class OpenApi3<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) |
| [SimpleJson](../../org.http4k.contract.simple/-simple-json/index.md) | `class SimpleJson<out NODE> : `[`ContractRenderer`](./index.md)`, `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) |
