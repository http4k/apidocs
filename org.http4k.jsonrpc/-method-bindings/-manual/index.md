[http4k](../../../index.md) / [org.http4k.jsonrpc](../../index.md) / [MethodBindings](../index.md) / [Manual](./index.md)

# Manual

`class Manual<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](../index.md)`<NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Manual(json: `[`Json`](../../../org.http4k.format/-json/index.md)`<NODE>)` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsLens: `[`Mapping`](../../-mapping/index.md)`<NODE, IN>, resultLens: `[`Mapping`](../../-mapping/index.md)`<OUT, NODE>, fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`<br>`fun <IN, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Mapping`](../../-mapping/index.md)`<NODE, IN>, resultLens: `[`Mapping`](../../-mapping/index.md)`<OUT, NODE>, fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`<br>`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(resultLens: `[`Mapping`](../../-mapping/index.md)`<OUT, NODE>, block: () -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>` |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`JsonRpcMethodBinding`](../../-json-rpc-method-binding/index.md)`<NODE, NODE>>` |
| [method](method.md) | `open fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
