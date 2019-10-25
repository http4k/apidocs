[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [HasSchema](./index.md)

# HasSchema

`interface HasSchema<NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L63)

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `abstract fun definitions(): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [OneOfSchemaContent](../-body-content/-one-of-schema-content/index.md) | `class OneOfSchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](../-body-content/index.md)`, `[`HasSchema`](./index.md)`<`[`NODE`](../-body-content/-one-of-schema-content/index.md#NODE)`>` |
| [RequestContents](../-request-contents/index.md) | `class RequestContents<NODE> : `[`HasSchema`](./index.md)`<`[`NODE`](../-request-contents/index.md#NODE)`>` |
| [ResponseContents](../-response-contents/index.md) | `class ResponseContents<NODE> : `[`HasSchema`](./index.md)`<`[`NODE`](../-response-contents/index.md#NODE)`>` |
| [SchemaContent](../-body-content/-schema-content/index.md) | `class SchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](../-body-content/index.md)`, `[`HasSchema`](./index.md)`<`[`NODE`](../-body-content/-schema-content/index.md#NODE)`>` |
| [SchemaParameter](../-request-parameter/-schema-parameter/index.md) | `class SchemaParameter<NODE> : `[`RequestParameter`](../-request-parameter/index.md)`<`[`NODE`](../-request-parameter/-schema-parameter/index.md#NODE)`>, `[`HasSchema`](./index.md)`<`[`NODE`](../-request-parameter/-schema-parameter/index.md#NODE)`>` |
