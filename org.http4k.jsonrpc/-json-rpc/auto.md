[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpc](index.md) / [auto](./auto.md)

# auto

`fun <NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> auto(json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`<NODE>, errorHandler: `[`ErrorHandler`](../-error-handler.md)` = defaultErrorHandler, fn: Auto<NODE>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](../-json-rpc-service/index.md)`<NODE>`