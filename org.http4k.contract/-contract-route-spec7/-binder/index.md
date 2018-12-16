[http4k](../../../index.md) / [org.http4k.contract](../../index.md) / [ContractRouteSpec7](../index.md) / [Binder](./index.md)

# Binder

`inner class Binder<out A, out B, out C, out D, out E, out F, out G>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L170)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Binder(method: `[`Method`](../../../org.http4k.core/-method/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [newRequest](new-request.md) | `fun newRequest(baseUri: `[`Uri`](../../../org.http4k.core/-uri/index.md)`): `[`Request`](../../../org.http4k.core/-request/index.md) |
| [to](to.md) | `infix fun to(fn: (`[`A`](index.md#A)`, `[`B`](index.md#B)`, `[`C`](index.md#C)`, `[`D`](index.md#D)`, `[`E`](index.md#E)`, `[`F`](index.md#F)`, `[`G`](index.md#G)`) -> `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`ContractRoute`](../../-contract-route/index.md) |
