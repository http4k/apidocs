[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLens](./index.md)

# BiDiPathLens

`class BiDiPathLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](../-path-lens/index.md)`<FINAL>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiPathLens(meta: `[`Meta`](../-meta/index.md)`, get: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> FINAL, set: (FINAL, `[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to set the value into the target`operator fun <R : `[`Request`](../../org.http4k.core/-request/index.md)`> invoke(value: FINAL, target: R): R` |

### Extension Functions

| Name | Summary |
|---|---|
| [bindContract](../../org.http4k.contract/bind-contract.md) | `infix fun <A> `[`PathLens`](../-path-lens/index.md)`<A>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): Binder<A>` |
| [div](../../org.http4k.contract/div.md) | `operator fun <A> `[`PathLens`](../-path-lens/index.md)`<A>.div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<A, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator fun <A, B> `[`PathLens`](../-path-lens/index.md)`<A>.div(next: `[`PathLens`](../-path-lens/index.md)`<B>): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<A, B>` |
| [meta](../../org.http4k.contract/meta.md) | `infix fun <A> `[`PathLens`](../-path-lens/index.md)`<A>.meta(new: `[`RouteMetaDsl`](../../org.http4k.contract/-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](../../org.http4k.contract/-contract-route-spec1/index.md)`<A>` |
