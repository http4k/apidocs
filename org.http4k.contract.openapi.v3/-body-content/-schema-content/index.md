[http4k](../../../index.md) / [org.http4k.contract.openapi.v3](../../index.md) / [BodyContent](../index.md) / [SchemaContent](./index.md)

# SchemaContent

`class SchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](../index.md)`, `[`HasSchema`](../../-has-schema/index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L71)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SchemaContent(jsonSchema: `[`JsonSchema`](../../../org.http4k.util/-json-schema/index.md)`<`[`NODE`](index.md#NODE)`>?, example: `[`NODE`](index.md#NODE)`?)` |

### Properties

| Name | Summary |
|---|---|
| [example](example.md) | `val example: `[`NODE`](index.md#NODE)`?` |
| [schema](schema.md) | `val schema: `[`NODE`](index.md#NODE)`?` |

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `fun definitions(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>` |
