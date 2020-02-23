[http4k](../../../index.md) / [org.http4k.jsonrpc](../../index.md) / [MethodBindings](../index.md) / [Auto](./index.md)

# Auto

`class Auto<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : Manual<NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Auto(json: `[`JsonLibAutoMarshallingJson`](../../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<NODE>)` |

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `val json: `[`JsonLibAutoMarshallingJson`](../../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<NODE>` |

### Functions

| Name | Summary |
|---|---|
| [handler](handler.md) | `fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`<br>`fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`<br>`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(fn: () -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>` |
