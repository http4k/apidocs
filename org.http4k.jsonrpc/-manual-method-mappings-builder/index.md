[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [ManualMethodMappingsBuilder](./index.md)

# ManualMethodMappingsBuilder

`open class ManualMethodMappingsBuilder<ROOT : `[`NODE`](index.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodMappingsBuilder`](../-method-mappings-builder/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodMappingsBuilder.kt#L12)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ManualMethodMappingsBuilder(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>)` |

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `open val json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN, OUT> handler(paramsLens: `[`Params`](../-params/index.md)`<`[`NODE`](index.md#NODE)`, `[`IN`](handler.md#IN)`>, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <IN, OUT> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Params`](../-params/index.md)`<`[`NODE`](index.md#NODE)`, `[`IN`](handler.md#IN)`>, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <OUT> handler(resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, block: () -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` |
| [mappings](mappings.md) | `fun mappings(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MethodMapping`](../-method-mapping/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>` |
| [method](method.md) | `fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AutoMethodMappingsBuilder](../-auto-method-mappings-builder/index.md) | `class AutoMethodMappingsBuilder<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ManualMethodMappingsBuilder`](./index.md)`<`[`ROOT`](../-auto-method-mappings-builder/index.md#ROOT)`, `[`ROOT`](../-auto-method-mappings-builder/index.md#ROOT)`>` |
