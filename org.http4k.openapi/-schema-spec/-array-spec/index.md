[http4k](../../../index.md) / [org.http4k.openapi](../../index.md) / [SchemaSpec](../index.md) / [ArraySpec](./index.md)

# ArraySpec

`data class ArraySpec : `[`SchemaSpec`](../index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ArraySpec(items: JsonNode, minItems: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`? = null, maxItems: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`? = null, uniqueItems: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, nullable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [maxItems](max-items.md) | `val maxItems: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [minItems](min-items.md) | `val minItems: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [nullable](nullable.md) | `val nullable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [uniqueItems](unique-items.md) | `val uniqueItems: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [itemsSpec](items-spec.md) | `fun itemsSpec(): `[`SchemaSpec`](../index.md) |
