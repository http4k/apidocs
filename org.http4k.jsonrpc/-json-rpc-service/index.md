[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpcService](./index.md)

# JsonRpcService

`data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonRpcService(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, errorHandler: `[`ErrorHandler`](../-error-handler.md)`, bindings: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`JsonRpcMethodBinding`](../-json-rpc-method-binding/index.md)`<NODE, NODE>>)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
