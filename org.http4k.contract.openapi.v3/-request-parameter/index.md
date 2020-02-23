[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [RequestParameter](./index.md)

# RequestParameter

`sealed class RequestParameter<NODE>`

### Types

| Name | Summary |
|---|---|
| [PrimitiveParameter](-primitive-parameter/index.md) | `class PrimitiveParameter<NODE> : `[`RequestParameter`](./index.md)`<NODE>` |
| [SchemaParameter](-schema-parameter/index.md) | `class SchemaParameter<NODE> : `[`RequestParameter`](./index.md)`<NODE>, `[`HasSchema`](../-has-schema/index.md)`<NODE>` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [in](in.md) | `val in: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
