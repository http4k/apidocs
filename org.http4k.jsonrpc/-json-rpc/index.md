[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpc](./index.md)

# JsonRpc

`object JsonRpc` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/jsonRpc.kt#L8)

### Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <ROOT : `[`NODE`](auto.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> auto(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`ROOT`](auto.md#ROOT)`>, errorHandler: `[`ErrorHandler`](../-error-handler.md)` = defaultErrorHandler, fn: `[`Auto`](../-method-bindings/-auto/index.md)`<`[`ROOT`](auto.md#ROOT)`>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](../-json-rpc-service/index.md)`<`[`ROOT`](auto.md#ROOT)`, `[`ROOT`](auto.md#ROOT)`>` |
| [manual](manual.md) | `fun <ROOT : `[`NODE`](manual.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> manual(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](manual.md#ROOT)`, `[`NODE`](manual.md#NODE)`>, errorHandler: `[`ErrorHandler`](../-error-handler.md)` = defaultErrorHandler, fn: `[`Manual`](../-method-bindings/-manual/index.md)`<`[`ROOT`](manual.md#ROOT)`, `[`NODE`](manual.md#NODE)`>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](../-json-rpc-service/index.md)`<`[`ROOT`](manual.md#ROOT)`, `[`NODE`](manual.md#NODE)`>` |
