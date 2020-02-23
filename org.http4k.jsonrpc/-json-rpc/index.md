[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpc](./index.md)

# JsonRpc

`object JsonRpc`

### Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> auto(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<NODE>, errorHandler: `[`ErrorHandler`](../-error-handler.md)` = defaultErrorHandler, fn: Auto<NODE>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](../-json-rpc-service/index.md)`<NODE>` |
| [manual](manual.md) | `fun <NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> manual(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, errorHandler: `[`ErrorHandler`](../-error-handler.md)` = defaultErrorHandler, fn: Manual<NODE>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](../-json-rpc-service/index.md)`<NODE>` |
