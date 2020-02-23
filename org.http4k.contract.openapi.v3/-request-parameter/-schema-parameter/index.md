[http4k](../../../index.md) / [org.http4k.contract.openapi.v3](../../index.md) / [RequestParameter](../index.md) / [SchemaParameter](./index.md)

# SchemaParameter

`class SchemaParameter<NODE> : `[`RequestParameter`](../index.md)`<NODE>, `[`HasSchema`](../../-has-schema/index.md)`<NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SchemaParameter(meta: `[`Meta`](../../../org.http4k.lens/-meta/index.md)`, jsonSchema: `[`JsonSchema`](../../../org.http4k.util/-json-schema/index.md)`<NODE>?)` |

### Properties

| Name | Summary |
|---|---|
| [schema](schema.md) | `val schema: NODE?` |

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `fun definitions(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, NODE>>` |
