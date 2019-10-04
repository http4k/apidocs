[http4k](../../../index.md) / [org.http4k.contract.openapi.v3](../../index.md) / [BodyContent](../index.md) / [OneOfSchemaContent](./index.md)

# OneOfSchemaContent

`class OneOfSchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](../index.md)`, `[`HasSchema`](../../-has-schema/index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L73)

### Types

| Name | Summary |
|---|---|
| [OneOf](-one-of/index.md) | `data class OneOf<NODE>` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OneOfSchemaContent(schemas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BodyContent`](../index.md)`>)` |

### Properties

| Name | Summary |
|---|---|
| [schema](schema.md) | `val schema: `[`BodyContent.OneOfSchemaContent.OneOf`](-one-of/index.md)`<`[`NODE`](index.md#NODE)`>` |

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `fun definitions(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>` |
