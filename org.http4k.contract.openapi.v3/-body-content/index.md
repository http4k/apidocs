[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [BodyContent](./index.md)

# BodyContent

`sealed class BodyContent` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L67)

### Types

| Name | Summary |
|---|---|
| [FormContent](-form-content/index.md) | `class FormContent : `[`BodyContent`](./index.md) |
| [NoSchema](-no-schema/index.md) | `data class NoSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md) |
| [OneOfSchemaContent](-one-of-schema-content/index.md) | `class OneOfSchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-one-of-schema-content/index.md#NODE)`>` |
| [SchemaContent](-schema-content/index.md) | `class SchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-schema-content/index.md#NODE)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [FormContent](-form-content/index.md) | `class FormContent : `[`BodyContent`](./index.md) |
| [NoSchema](-no-schema/index.md) | `data class NoSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md) |
| [OneOfSchemaContent](-one-of-schema-content/index.md) | `class OneOfSchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-one-of-schema-content/index.md#NODE)`>` |
| [SchemaContent](-schema-content/index.md) | `class SchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-schema-content/index.md#NODE)`>` |
