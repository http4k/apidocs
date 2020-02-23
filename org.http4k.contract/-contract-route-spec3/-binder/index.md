[http4k](../../../index.md) / [org.http4k.contract](../../index.md) / [ContractRouteSpec3](../index.md) / [Binder](./index.md)

# Binder

`inner class Binder<out A, out B, out C> : ContractRequestBuilder`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Binder(method: `[`Method`](../../../org.http4k.core/-method/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [to](to.md) | `infix fun to(fn: (A, B, C) -> `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`ContractRoute`](../../-contract-route/index.md) |
