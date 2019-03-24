[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpcMethodBinding](./index.md)

# JsonRpcMethodBinding

`data class JsonRpcMethodBinding<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/JsonRpcService.kt#L109)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonRpcMethodBinding(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>)` |

### Properties

| Name | Summary |
|---|---|
| [handler](handler.md) | `val handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
