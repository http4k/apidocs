[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [RequestParameter](./index.md)

# RequestParameter

`sealed class RequestParameter<NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L99)

### Types

| Name | Summary |
|---|---|
| [PrimitiveParameter](-primitive-parameter/index.md) | `class PrimitiveParameter<NODE> : `[`RequestParameter`](./index.md)`<`[`NODE`](-primitive-parameter/index.md#NODE)`>` |
| [SchemaParameter](-schema-parameter/index.md) | `class SchemaParameter<NODE> : `[`RequestParameter`](./index.md)`<`[`NODE`](-schema-parameter/index.md#NODE)`>, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-schema-parameter/index.md#NODE)`>` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [in](in.md) | `val in: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [required](required.md) | `val required: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [PrimitiveParameter](-primitive-parameter/index.md) | `class PrimitiveParameter<NODE> : `[`RequestParameter`](./index.md)`<`[`NODE`](-primitive-parameter/index.md#NODE)`>` |
| [SchemaParameter](-schema-parameter/index.md) | `class SchemaParameter<NODE> : `[`RequestParameter`](./index.md)`<`[`NODE`](-schema-parameter/index.md#NODE)`>, `[`HasSchema`](../-has-schema/index.md)`<`[`NODE`](-schema-parameter/index.md#NODE)`>` |
