[http4k](../index.md) / [org.http4k.jsonrpc](./index.md)

## Package org.http4k.jsonrpc

### Types

| Name | Summary |
|---|---|
| [AutoMethodMappingsBuilder](-auto-method-mappings-builder/index.md) | `class AutoMethodMappingsBuilder<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ManualMethodMappingsBuilder`](-manual-method-mappings-builder/index.md)`<`[`ROOT`](-auto-method-mappings-builder/index.md#ROOT)`, `[`ROOT`](-auto-method-mappings-builder/index.md#ROOT)`>` |
| [ErrorMessage](-error-message/index.md) | `open class ErrorMessage` |
| [JsonRpcService](-json-rpc-service/index.md) | `data class JsonRpcService<ROOT : `[`NODE`](-json-rpc-service/index.md#NODE)`, NODE> : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ManualMethodMappingsBuilder](-manual-method-mappings-builder/index.md) | `open class ManualMethodMappingsBuilder<ROOT : `[`NODE`](-manual-method-mappings-builder/index.md#NODE)`, NODE> : `[`MethodMappingsBuilder`](-method-mappings-builder/index.md)`<`[`ROOT`](-manual-method-mappings-builder/index.md#ROOT)`, `[`NODE`](-manual-method-mappings-builder/index.md#NODE)`>` |
| [MethodMapping](-method-mapping/index.md) | `data class MethodMapping<IN, OUT>` |
| [MethodMappingsBuilder](-method-mappings-builder/index.md) | `interface MethodMappingsBuilder<ROOT : `[`NODE`](-method-mappings-builder/index.md#NODE)`, NODE>` |
| [NoParamsJsonRequestHandler](-no-params-json-request-handler/index.md) | `class NoParamsJsonRequestHandler<NODE, OUT> : `[`RequestHandler`](-request-handler.md)`<`[`NODE`](-no-params-json-request-handler/index.md#NODE)`, `[`NODE`](-no-params-json-request-handler/index.md#NODE)`>` |
| [ParamMappingJsonRequestHandler](-param-mapping-json-request-handler/index.md) | `class ParamMappingJsonRequestHandler<ROOT : `[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`, NODE, IN, OUT> : `[`RequestHandler`](-request-handler.md)`<`[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`, `[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`>` |
| [Params](-params/index.md) | `class Params<NODE, IN> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<`[`NODE`](-params/index.md#NODE)`, `[`IN`](-params/index.md#IN)`>` |
| [Result](-result/index.md) | `class Result<OUT, NODE> : `[`Lens`](../org.http4k.lens/-lens/index.md)`<`[`OUT`](-result/index.md#OUT)`, `[`NODE`](-result/index.md#NODE)`>` |

### Type Aliases

| Name | Summary |
|---|---|
| [ErrorHandler](-error-handler.md) | `typealias ErrorHandler = (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`ErrorMessage`](-error-message/index.md)`?` |
| [RequestHandler](-request-handler.md) | `typealias RequestHandler<IN, OUT> = (`[`IN`](-request-handler.md#IN)`) -> `[`OUT`](-request-handler.md#OUT) |

### Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> auto(json: `[`JsonLibAutoMarshallingJson`](../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`ROOT`](auto.md#ROOT)`>): `[`AutoMethodMappingsBuilder`](-auto-method-mappings-builder/index.md)`<`[`ROOT`](auto.md#ROOT)`>` |
| [jsonRpc](json-rpc.md) | `fun <ROOT : `[`NODE`](json-rpc.md#NODE)`, NODE> jsonRpc(json: `[`Json`](../org.http4k.format/-json/index.md)`<`[`ROOT`](json-rpc.md#ROOT)`, `[`NODE`](json-rpc.md#NODE)`>, errorHandler: `[`ErrorHandler`](-error-handler.md)` = defaultErrorHandler, definitions: `[`ManualMethodMappingsBuilder`](-manual-method-mappings-builder/index.md)`<`[`ROOT`](json-rpc.md#ROOT)`, `[`NODE`](json-rpc.md#NODE)`>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](-json-rpc-service/index.md)`<`[`ROOT`](json-rpc.md#ROOT)`, `[`NODE`](json-rpc.md#NODE)`>`<br>`fun <ROOT : `[`NODE`](json-rpc.md#NODE)`, NODE, M : `[`MethodMappingsBuilder`](-method-mappings-builder/index.md)`<`[`ROOT`](json-rpc.md#ROOT)`, `[`NODE`](json-rpc.md#NODE)`>> jsonRpc(methodMappingsBuilder: `[`M`](json-rpc.md#M)`, errorHandler: `[`ErrorHandler`](-error-handler.md)` = defaultErrorHandler, definitions: `[`M`](json-rpc.md#M)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`JsonRpcService`](-json-rpc-service/index.md)`<`[`ROOT`](json-rpc.md#ROOT)`, `[`NODE`](json-rpc.md#NODE)`>` |
| [manual](manual.md) | `fun <ROOT : `[`NODE`](manual.md#NODE)`, NODE> manual(json: `[`Json`](../org.http4k.format/-json/index.md)`<`[`ROOT`](manual.md#ROOT)`, `[`NODE`](manual.md#NODE)`>): `[`ManualMethodMappingsBuilder`](-manual-method-mappings-builder/index.md)`<`[`ROOT`](manual.md#ROOT)`, `[`NODE`](manual.md#NODE)`>` |
