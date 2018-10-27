[http4k](../../../index.md) / [org.http4k.jsonrpc](../../index.md) / [MethodBindings](../index.md) / [Auto](./index.md)

# Auto

`class Auto<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Manual`](../-manual/index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodBindings.kt#L36)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Auto(json: `[`JsonLibAutoMarshallingJson`](../../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>)` |

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `val json: `[`JsonLibAutoMarshallingJson`](../../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, fn: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(block: (`[`IN`](handler.md#IN)`) -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>`<br>`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(block: () -> `[`OUT`](handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [handler](../-manual/handler.md) | `fun <IN, OUT> handler(paramsLens: `[`Mapping`](../../-mapping/index.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`IN`](../-manual/handler.md#IN)`>, resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](../-manual/handler.md#OUT)`, `[`NODE`](../-manual/index.md#NODE)`>, fn: (`[`IN`](../-manual/handler.md#IN)`) -> `[`OUT`](../-manual/handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`NODE`](../-manual/index.md#NODE)`>`<br>`fun <IN, OUT> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Mapping`](../../-mapping/index.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`IN`](../-manual/handler.md#IN)`>, resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](../-manual/handler.md#OUT)`, `[`NODE`](../-manual/index.md#NODE)`>, fn: (`[`IN`](../-manual/handler.md#IN)`) -> `[`OUT`](../-manual/handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`NODE`](../-manual/index.md#NODE)`>`<br>`fun <OUT> handler(resultLens: `[`Mapping`](../../-mapping/index.md)`<`[`OUT`](../-manual/handler.md#OUT)`, `[`NODE`](../-manual/index.md#NODE)`>, block: () -> `[`OUT`](../-manual/handler.md#OUT)`): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`NODE`](../-manual/index.md#NODE)`>` |
| [iterator](../-manual/iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`JsonRpcMethodBinding`](../../-json-rpc-method-binding/index.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`NODE`](../-manual/index.md#NODE)`>>` |
| [method](../-manual/method.md) | `open fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<`[`NODE`](../-manual/index.md#NODE)`, `[`NODE`](../-manual/index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
