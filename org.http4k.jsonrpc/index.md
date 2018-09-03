[http4k](../index.md) / [org.http4k.jsonrpc](./index.md)

## Package org.http4k.jsonrpc

### Types

| Name | Summary |
|---|---|
| [AutoMethodMappingsBuilder](-auto-method-mappings-builder/index.md) | `class AutoMethodMappingsBuilder<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ManualMethodMappingsBuilder`](-manual-method-mappings-builder/index.md)`<`[`ROOT`](-auto-method-mappings-builder/index.md#ROOT)`, `[`ROOT`](-auto-method-mappings-builder/index.md#ROOT)`>` |
| [ErrorMessage](-error-message/index.md) | `open class ErrorMessage` |
| [JsonRpc](-json-rpc/index.md) | `object JsonRpc` |
| [JsonRpcService](-json-rpc-service/index.md) | `data class JsonRpcService<ROOT : `[`NODE`](-json-rpc-service/index.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ManualMethodMappingsBuilder](-manual-method-mappings-builder/index.md) | `open class ManualMethodMappingsBuilder<ROOT : `[`NODE`](-manual-method-mappings-builder/index.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodMappingsBuilder`](-method-mappings-builder/index.md)`<`[`ROOT`](-manual-method-mappings-builder/index.md#ROOT)`, `[`NODE`](-manual-method-mappings-builder/index.md#NODE)`>` |
| [MethodMapping](-method-mapping/index.md) | `data class MethodMapping<IN, OUT>` |
| [MethodMappingsBuilder](-method-mappings-builder/index.md) | `interface MethodMappingsBuilder<ROOT : `[`NODE`](-method-mappings-builder/index.md#NODE)`, NODE>` |
| [Params](-params/index.md) | `class Params<NODE, IN> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<`[`NODE`](-params/index.md#NODE)`, `[`IN`](-params/index.md#IN)`>` |
| [Result](-result/index.md) | `class Result<OUT, NODE> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<`[`OUT`](-result/index.md#OUT)`, `[`NODE`](-result/index.md#NODE)`>` |

### Type Aliases

| Name | Summary |
|---|---|
| [ErrorHandler](-error-handler.md) | `typealias ErrorHandler = (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`ErrorMessage`](-error-message/index.md)`?` |
| [JsonRpcHandler](-json-rpc-handler.md) | `typealias JsonRpcHandler<IN, OUT> = (`[`IN`](-json-rpc-handler.md#IN)`) -> `[`OUT`](-json-rpc-handler.md#OUT) |
