[http4k](../../index.md) / [org.http4k.openapi.v2](../index.md) / [OpenApi2ParameterSpec](./index.md)

# OpenApi2ParameterSpec

`sealed class OpenApi2ParameterSpec`

### Types

| Name | Summary |
|---|---|
| [BodySpec](-body-spec/index.md) | `class BodySpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [CookieSpec](-cookie-spec/index.md) | `class CookieSpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [FormSpec](-form-spec/index.md) | `class FormSpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [HeaderSpec](-header-spec/index.md) | `class HeaderSpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [PathSpec](-path-spec/index.md) | `class PathSpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [QuerySpec](-query-spec/index.md) | `class QuerySpec : `[`OpenApi2ParameterSpec`](./index.md) |
| [RefSpec](-ref-spec/index.md) | `data class RefSpec : `[`OpenApi2ParameterSpec`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [items](items.md) | `val items: JsonNode` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [itemsSpec](items-spec.md) | `fun itemsSpec(): `[`SchemaSpec`](../../org.http4k.openapi/-schema-spec/index.md) |
