[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec1](./index.md)

# ContractRouteSpec1

`class ContractRouteSpec1<out A> : `[`ContractRouteSpec`](../-contract-route-spec/index.md)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A> : ContractRequestBuilder` |

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<A>` |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): Binder<A>` |
| [div](div.md) | `infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec2`](../-contract-route-spec2/index.md)`<A, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`infix operator fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<NEXT>): `[`ContractRouteSpec2`](../-contract-route-spec2/index.md)`<A, NEXT>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A> `[`ContractRouteSpec1`](./index.md)`<A>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](./index.md)`<A>` |
