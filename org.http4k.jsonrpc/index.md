[http4k](../index.md) / [org.http4k.jsonrpc](./index.md)

## Package org.http4k.jsonrpc

### Types

| Name | Summary |
|---|---|
| [ErrorHandler](-error-handler.md) | `typealias ErrorHandler = (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`ErrorMessage`](-error-message/index.md)`?` |
| [ErrorMessage](-error-message/index.md) | `open class ErrorMessage` |
| [JsonRpc](-json-rpc/index.md) | `object JsonRpc` |
| [JsonRpcHandler](-json-rpc-handler.md) | `typealias JsonRpcHandler<IN, OUT> = (IN) -> OUT` |
| [JsonRpcMethodBinding](-json-rpc-method-binding/index.md) | `data class JsonRpcMethodBinding<IN, OUT>` |
| [JsonRpcService](-json-rpc-service/index.md) | `data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [Mapping](-mapping/index.md) | `class Mapping<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<IN, OUT>` |
| [MethodBindings](-method-bindings/index.md) | `interface MethodBindings<NODE> : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`JsonRpcMethodBinding`](-json-rpc-method-binding/index.md)`<NODE, NODE>>` |
