[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [MethodBindings](./index.md)

# MethodBindings

`interface MethodBindings<NODE> : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`JsonRpcMethodBinding`](../-json-rpc-method-binding/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodBindings.kt#L6)

### Types

| Name | Summary |
|---|---|
| [Auto](-auto/index.md) | `class Auto<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Manual`](-manual/index.md)`<`[`NODE`](-auto/index.md#NODE)`>` |
| [Manual](-manual/index.md) | `class Manual<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](./index.md)`<`[`NODE`](-manual/index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [method](method.md) | `abstract fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [Manual](-manual/index.md) | `class Manual<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](./index.md)`<`[`NODE`](-manual/index.md#NODE)`>` |
