[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [BodyContent](./index.md)

# BodyContent

`sealed class BodyContent`

### Types

| Name | Summary |
|---|---|
| [FormContent](-form-content/index.md) | `class FormContent : `[`BodyContent`](./index.md) |
| [NoSchema](-no-schema/index.md) | `data class NoSchema<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md) |
| [OneOfSchemaContent](-one-of-schema-content/index.md) | `class OneOfSchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<NODE>` |
| [SchemaContent](-schema-content/index.md) | `class SchemaContent<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`BodyContent`](./index.md)`, `[`HasSchema`](../-has-schema/index.md)`<NODE>` |
