[http4k](../../../index.md) / [org.http4k.jsonrpc](../../index.md) / [MethodBindings](../index.md) / [Auto](index.md) / [handler](./handler.md)

# handler

`inline fun <reified IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(paramsFieldNames: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, noinline fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`
`inline fun <reified IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(noinline fn: (IN) -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`
`fun <OUT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> handler(fn: () -> OUT): `[`JsonRpcHandler`](../../-json-rpc-handler.md)`<NODE, NODE>`