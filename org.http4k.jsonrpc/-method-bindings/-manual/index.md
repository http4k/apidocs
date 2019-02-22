[http4k](../../../index.md) / [org.http4k.jsonrpc](../../index.md) / [MethodBindings](../index.md) / [Manual](./index.md)

# Manual

`class Manual<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](../index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodBindings.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Manual(json: `[`Json`](../../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsLens: `[`Mapping`](../../-mapping/index.md)`<`[`NODE`](index.md#NODE)`, `[`IN`](handler.md#IN)`>, resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <IN, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Mapping`](../../-mapping/index.md)`<`[`NODE`](index.md#NODE)`, `[`IN`](handler.md#IN)`>, resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](handler.md#OUT)`, `[`NODE`](index.md#NODE)`>, block: () -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`JsonRpcMethodBinding`](../../-json-rpc-method-binding/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>` |
| [method](method.md) | `open fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [Auto](../-auto/index.md) | `class Auto<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Manual`](./index.md)`<`[`NODE`](../-auto/index.md#NODE)`>` |
