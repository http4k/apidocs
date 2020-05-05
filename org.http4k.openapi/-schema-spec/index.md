[http4k](../../index.md) / [org.http4k.openapi](../index.md) / [SchemaSpec](./index.md)

# SchemaSpec

`sealed class SchemaSpec`

### Types

| Name | Summary |
|---|---|
| [ArraySpec](-array-spec/index.md) | `data class ArraySpec : `[`SchemaSpec`](./index.md) |
| [BooleanSpec](-boolean-spec.md) | `object BooleanSpec : `[`SchemaSpec`](./index.md) |
| [IntegerSpec](-integer-spec.md) | `object IntegerSpec : `[`SchemaSpec`](./index.md) |
| [NumberSpec](-number-spec.md) | `object NumberSpec : `[`SchemaSpec`](./index.md) |
| [ObjectSpec](-object-spec/index.md) | `data class ObjectSpec : `[`SchemaSpec`](./index.md) |
| [RefSpec](-ref-spec/index.md) | `data class RefSpec : `[`SchemaSpec`](./index.md) |
| [StringSpec](-string-spec.md) | `object StringSpec : `[`SchemaSpec`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [clazz](clazz.md) | `open val clazz: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<*>?` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildModelClass](../../org.http4k.openapi.models/build-model-class.md) | `fun `[`SchemaSpec`](./index.md)`.buildModelClass(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, allSchemas: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](./index.md)`>, generated: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, TypeSpec>): TypeSpec` |
