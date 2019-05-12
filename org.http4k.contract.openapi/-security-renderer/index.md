[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [SecurityRenderer](./index.md)

# SecurityRenderer

`interface SecurityRenderer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/SecurityRenderer.kt#L11)

Provides rendering of Security models in to OpenApi specs.

### Functions

| Name | Summary |
|---|---|
| [full](full.md) | `abstract fun <NODE> full(security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`): `[`Render`](../-render.md)`<`[`NODE`](full.md#NODE)`>?` |
| [ref](ref.md) | `abstract fun <NODE> ref(security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`): `[`Render`](../-render.md)`<`[`NODE`](ref.md#NODE)`>?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(vararg renderers: `[`SecurityRenderer`](./index.md)`): `[`SecurityRenderer`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [OpenApi2SecurityRenderer](../../org.http4k.contract.openapi.v2/-open-api2-security-renderer/index.md) | `object OpenApi2SecurityRenderer : `[`SecurityRenderer`](./index.md) |
| [OpenApi3SecurityRenderer](../../org.http4k.contract.openapi.v3/-open-api3-security-renderer/index.md) | `object OpenApi3SecurityRenderer : `[`SecurityRenderer`](./index.md) |
