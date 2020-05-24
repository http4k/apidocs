[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [OpenApi3ParameterSpec](./index.md)

# OpenApi3ParameterSpec

`sealed class OpenApi3ParameterSpec`

### Types

| Name | Summary |
|---|---|
| [CookieSpec](-cookie-spec/index.md) | `class CookieSpec : `[`OpenApi3ParameterSpec`](./index.md) |
| [FormFieldSpec](-form-field-spec/index.md) | `class FormFieldSpec : `[`OpenApi3ParameterSpec`](./index.md) |
| [HeaderSpec](-header-spec/index.md) | `class HeaderSpec : `[`OpenApi3ParameterSpec`](./index.md) |
| [PathSpec](-path-spec/index.md) | `class PathSpec : `[`OpenApi3ParameterSpec`](./index.md) |
| [QuerySpec](-query-spec/index.md) | `class QuerySpec : `[`OpenApi3ParameterSpec`](./index.md) |
| [RefOrNoSchemaSpec](-ref-or-no-schema-spec/index.md) | `class RefOrNoSchemaSpec : `[`OpenApi3ParameterSpec`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [schema](schema.md) | `val schema: `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md) |

### Extension Properties

| Name | Summary |
|---|---|
| [lensSpecClazz](../../org.http4k.poet/lens-spec-clazz.md) | `val `[`OpenApi3ParameterSpec`](./index.md)`.lensSpecClazz: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<out `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [asTypeName](../../org.http4k.poet/as-type-name.md) | `fun `[`OpenApi3ParameterSpec`](./index.md)`.asTypeName(): TypeName` |
| [lensConstruct](../../org.http4k.poet/lens-construct.md) | `fun `[`OpenApi3ParameterSpec`](./index.md)`.lensConstruct(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [quotedName](../../org.http4k.poet/quoted-name.md) | `fun `[`OpenApi3ParameterSpec`](./index.md)`.quotedName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
