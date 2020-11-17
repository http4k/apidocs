[http4k](../../index.md) / [org.http4k.lens](../index.md) / [PathLens](./index.md)

# PathLens

`open class PathLens<out FINAL> : `[`Lens`](../-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, FINAL>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PathLens(meta: `[`Meta`](../-meta/index.md)`, get: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> FINAL)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(target: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FINAL` |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |
| [bindContract](../../org.http4k.contract/bind-contract.md) | `infix fun <A> `[`PathLens`](./index.md)`<A>.bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): Binder<A>` |
| [div](../../org.http4k.contract/div.md) | `operator fun <A> `[`PathLens`](./index.md)`<A>.div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<A, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator fun <A, B> `[`PathLens`](./index.md)`<A>.div(next: `[`PathLens`](./index.md)`<B>): `[`ContractRouteSpec2`](../../org.http4k.contract/-contract-route-spec2/index.md)`<A, B>` |
| [matches](../matches.md) | Check the content of any lens on a request for routing purposes.`fun <T> `[`Lens`](../-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, T>.matches(fn: (T) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [meta](../../org.http4k.contract/meta.md) | `infix fun <A> `[`PathLens`](./index.md)`<A>.meta(new: `[`RouteMetaDsl`](../../org.http4k.contract/-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](../../org.http4k.contract/-contract-route-spec1/index.md)`<A>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiPathLens](../-bi-di-path-lens/index.md) | `class BiDiPathLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](./index.md)`<FINAL>` |
