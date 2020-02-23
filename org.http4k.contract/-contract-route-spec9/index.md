[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec9](./index.md)

# ContractRouteSpec9

`class ContractRouteSpec9<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec`](../-contract-route-spec/index.md)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A, out B, out C, out D, out E, out F, out G, out H, out I> : ContractRequestBuilder` |

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<A>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<B>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<C>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<D>` |
| [e](e.md) | `val e: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<E>` |
| [f](f.md) | `val f: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<F>` |
| [g](g.md) | `val g: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<G>` |
| [h](h.md) | `val h: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<H>` |
| [i](i.md) | `val i: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<I>` |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): Binder<A, B, C, D, E, F, G, H, I>` |
| [div](div.md) | `infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<A, B, C, D, E, F, G, H, I, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`infix operator fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<NEXT>): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<A, B, C, D, E, F, G, H, I, NEXT>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A, B, C, D, E, F, G, H, I> `[`ContractRouteSpec9`](./index.md)`<A, B, C, D, E, F, G, H, I>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec9`](./index.md)`<A, B, C, D, E, F, G, H, I>` |
