[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [MethodBindings](./index.md)

# MethodBindings

`interface MethodBindings<ROOT : `[`NODE`](index.md#NODE)`, NODE> : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`JsonRpcMethodBinding`](../-json-rpc-method-binding/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodBindings.kt#L6)

### Types

| Name | Summary |
|---|---|
| [Auto](-auto/index.md) | `class Auto<ROOT : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Manual`](-manual/index.md)`<`[`ROOT`](-auto/index.md#ROOT)`, `[`ROOT`](-auto/index.md#ROOT)`>` |
| [Manual](-manual/index.md) | `class Manual<ROOT : `[`NODE`](-manual/index.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](./index.md)`<`[`ROOT`](-manual/index.md#ROOT)`, `[`NODE`](-manual/index.md#NODE)`>` |

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `abstract val json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [method](method.md) | `abstract fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`JsonRpcHandler`](../-json-rpc-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [Manual](-manual/index.md) | `class Manual<ROOT : `[`NODE`](-manual/index.md#NODE)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`MethodBindings`](./index.md)`<`[`ROOT`](-manual/index.md#ROOT)`, `[`NODE`](-manual/index.md#NODE)`>` |
