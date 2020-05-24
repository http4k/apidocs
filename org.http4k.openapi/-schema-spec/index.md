[http4k](../../index.md) / [org.http4k.openapi](../index.md) / [SchemaSpec](./index.md)

# SchemaSpec

`sealed class SchemaSpec`

### Types

| Name | Summary |
|---|---|
| [ArraySpec](-array-spec/index.md) | `data class ArraySpec : `[`SchemaSpec`](./index.md) |
| [BooleanSpec](-boolean-spec/index.md) | `data class BooleanSpec : `[`SchemaSpec`](./index.md) |
| [IntegerSpec](-integer-spec/index.md) | `data class IntegerSpec : `[`SchemaSpec`](./index.md) |
| [NumberSpec](-number-spec/index.md) | `data class NumberSpec : `[`SchemaSpec`](./index.md) |
| [ObjectSpec](-object-spec/index.md) | `data class ObjectSpec : `[`SchemaSpec`](./index.md) |
| [RefSpec](-ref-spec/index.md) | `data class RefSpec : `[`SchemaSpec`](./index.md) |
| [StringSpec](-string-spec/index.md) | `data class StringSpec : `[`SchemaSpec`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [clazz](clazz.md) | `open val clazz: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<*>?` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildModelClass](../build-model-class.md) | `fun `[`SchemaSpec`](./index.md)`.buildModelClass(className: ClassName, allSchemas: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SchemaSpec`](./index.md)`>, generated: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`GeneratedType`](../-generated-type/index.md)`>): `[`GeneratedType`](../-generated-type/index.md) |
| [namedSchema](../named-schema.md) | `fun `[`SchemaSpec`](./index.md)`.namedSchema(modelName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NamedSchema`](../-named-schema/index.md) |
