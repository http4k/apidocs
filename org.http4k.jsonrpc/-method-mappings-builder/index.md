[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [MethodMappingsBuilder](./index.md)

# MethodMappingsBuilder

`interface MethodMappingsBuilder<ROOT : `[`NODE`](index.md#NODE)`, NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/MethodMappingsBuilder.kt#L5)

### Properties

| Name | Summary |
|---|---|
| [json](json.md) | `abstract val json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [mappings](mappings.md) | `abstract fun mappings(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MethodMapping`](../-method-mapping/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>` |
| [method](method.md) | `abstract fun method(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, handler: `[`RequestHandler`](../-request-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ManualMethodMappingsBuilder](../-manual-method-mappings-builder/index.md) | `open class ManualMethodMappingsBuilder<ROOT : `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`, NODE> : `[`MethodMappingsBuilder`](./index.md)`<`[`ROOT`](../-manual-method-mappings-builder/index.md#ROOT)`, `[`NODE`](../-manual-method-mappings-builder/index.md#NODE)`>` |
