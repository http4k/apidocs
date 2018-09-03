[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [AutoMethodMappingsBuilder](./index.md)

# AutoMethodMappingsBuilder

`class AutoMethodMappingsBuilder<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`ManualMethodMappingsBuilder`](../-manual-method-mappings-builder/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`ROOT`](index.md#ROOT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodMappingsBuilder.kt#L37)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoMethodMappingsBuilder(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`ROOT`](index.md#ROOT)`>)` |

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `val json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`ROOT`](index.md#ROOT)`>` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`ROOT`](index.md#ROOT)`, `[`ROOT`](index.md#ROOT)`>`<br>`fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(block: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`ROOT`](index.md#ROOT)`, `[`ROOT`](index.md#ROOT)`>`<br>`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(block: () -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`ROOT`](index.md#ROOT)`, `[`ROOT`](index.md#ROOT)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [handler](../-manual-method-mappings-builder/handler.md) | `fun <IN, OUT> handler(paramsLens: `[`Params`](../-params/index.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`IN`](../-manual-method-mappings-builder/handler.md#IN)`>, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>, fn: (`[`IN`](../-manual-method-mappings-builder/handler.md#IN)`) -> `[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>`<br>`fun <IN, OUT> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Params`](../-params/index.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`IN`](../-manual-method-mappings-builder/handler.md#IN)`>, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>, fn: (`[`IN`](../-manual-method-mappings-builder/handler.md#IN)`) -> `[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>`<br>`fun <OUT> handler(resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>, block: () -> `[`OUT`](../-manual-method-mappings-builder/handler.md#OUT)`): `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>` |
| [mappings](../-manual-method-mappings-builder/mappings.md) | `fun mappings(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MethodMapping`](../-method-mapping/index.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>>` |
| [method](../-manual-method-mappings-builder/method.md) | `fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
