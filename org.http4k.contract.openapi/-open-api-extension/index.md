[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [OpenApiExtension](./index.md)

# OpenApiExtension

`interface OpenApiExtension` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/OpenApiExtension.kt#L6)

Provides a way to apply extensions to the OpenAPI JSON document.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun <NODE> invoke(node: `[`NODE`](invoke.md#NODE)`): `[`Render`](../-render.md)`<`[`NODE`](invoke.md#NODE)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
