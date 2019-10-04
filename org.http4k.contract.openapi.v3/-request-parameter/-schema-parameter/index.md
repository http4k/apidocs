[http4k](../../../index.md) / [org.http4k.contract.openapi.v3](../../index.md) / [RequestParameter](../index.md) / [SchemaParameter](./index.md)

# SchemaParameter

`class SchemaParameter<NODE> : `[`RequestParameter`](../index.md)`<`[`NODE`](index.md#NODE)`>, `[`HasSchema`](../../-has-schema/index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L111)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SchemaParameter(meta: `[`Meta`](../../../org.http4k.lens/-meta/index.md)`, jsonSchema: `[`JsonSchema`](../../../org.http4k.util/-json-schema/index.md)`<`[`NODE`](index.md#NODE)`>?)` |

### Properties

| Name | Summary |
|---|---|
| [schema](schema.md) | `val schema: `[`NODE`](index.md#NODE)`?` |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [in](../in.md) | `val in: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [name](../name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](../required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `fun definitions(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](index.md#NODE)`>>` |
