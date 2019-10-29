[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec4](./index.md)

# ContractRouteSpec4

`class ContractRouteSpec4<out A, out B, out C, out D> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L81)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A, out B, out C, out D> : `[`ContractRouteSpec.ContractRequestBuilder`](../-contract-route-spec/-contract-request-builder/index.md) |

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`A`](-binder/index.md#A)`>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`B`](-binder/index.md#B)`>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`C`](-binder/index.md#C)`>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`D`](-binder/index.md#D)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`ContractRouteSpec4.Binder`](-binder/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`>` |
| [div](div.md) | `infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec5`](../-contract-route-spec5/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`infix operator fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec5`](../-contract-route-spec5/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`NEXT`](div.md#NEXT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A, B, C, D> `[`ContractRouteSpec4`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec4`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`>` |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
