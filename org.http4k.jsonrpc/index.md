[http4k](../index.md) / [org.http4k.jsonrpc](./index.md)

## Package org.http4k.jsonrpc

### Types

| Name | Summary |
|---|---|
| [ErrorMessage](-error-message/index.md) | `open class ErrorMessage` |
| [JsonRpc](-json-rpc/index.md) | `object JsonRpc` |
| [JsonRpcMethodBinding](-json-rpc-method-binding/index.md) | `data class JsonRpcMethodBinding<IN, OUT>` |
| [JsonRpcService](-json-rpc-service/index.md) | `data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [Mapping](-mapping/index.md) | `class Mapping<IN, OUT> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<`[`IN`](-mapping/index.md#IN)`, `[`OUT`](-mapping/index.md#OUT)`>` |
| [MethodBindings](-method-bindings/index.md) | `interface MethodBindings<NODE> : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`JsonRpcMethodBinding`](-json-rpc-method-binding/index.md)`<`[`NODE`](-method-bindings/index.md#NODE)`, `[`NODE`](-method-bindings/index.md#NODE)`>>` |

### Type Aliases

| Name | Summary |
|---|---|
| [ErrorHandler](-error-handler.md) | `typealias ErrorHandler = (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`ErrorMessage`](-error-message/index.md)`?` |
| [JsonRpcHandler](-json-rpc-handler.md) | `typealias JsonRpcHandler<IN, OUT> = (`[`IN`](-json-rpc-handler.md#IN)`) -> `[`OUT`](-json-rpc-handler.md#OUT) |
