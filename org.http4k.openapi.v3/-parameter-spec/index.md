[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [ParameterSpec](./index.md)

# ParameterSpec

`sealed class ParameterSpec`

### Types

| Name | Summary |
|---|---|
| [CookieSpec](-cookie-spec/index.md) | `class CookieSpec : `[`ParameterSpec`](./index.md) |
| [HeaderSpec](-header-spec/index.md) | `class HeaderSpec : `[`ParameterSpec`](./index.md) |
| [PathSpec](-path-spec/index.md) | `class PathSpec : `[`ParameterSpec`](./index.md) |
| [QuerySpec](-query-spec/index.md) | `class QuerySpec : `[`ParameterSpec`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [schema](schema.md) | `val schema: `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md) |

### Extension Properties

| Name | Summary |
|---|---|
| [lensSpecClazz](../../org.http4k.poet/lens-spec-clazz.md) | `val `[`ParameterSpec`](./index.md)`.lensSpecClazz: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<out `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [asTypeName](../../org.http4k.poet/as-type-name.md) | `fun `[`ParameterSpec`](./index.md)`.asTypeName(): TypeName?` |
| [lensConstruct](../../org.http4k.poet/lens-construct.md) | `fun `[`ParameterSpec`](./index.md)`.lensConstruct(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [quotedName](../../org.http4k.poet/quoted-name.md) | `fun `[`ParameterSpec`](./index.md)`.quotedName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
