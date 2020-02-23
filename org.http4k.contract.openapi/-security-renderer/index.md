[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [SecurityRenderer](./index.md)

# SecurityRenderer

`interface SecurityRenderer`

Provides rendering of Security models in to OpenApi specs.

### Functions

| Name | Summary |
|---|---|
| [full](full.md) | `abstract fun <NODE> full(security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`): `[`Render`](../-render.md)`<NODE>?` |
| [ref](ref.md) | `abstract fun <NODE> ref(security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`): `[`Render`](../-render.md)`<NODE>?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(vararg renderers: `[`SecurityRenderer`](./index.md)`): `[`SecurityRenderer`](./index.md) |
