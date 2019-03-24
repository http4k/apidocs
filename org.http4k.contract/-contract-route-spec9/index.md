[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec9](./index.md)

# ContractRouteSpec9

`class ContractRouteSpec9<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L156)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec.ContractRequestBuilder`](../-contract-route-spec/-contract-request-builder/index.md) |

### Properties

| Name | Summary |
|---|---|
| [a](a.md) | `val a: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`A`](-binder/index.md#A)`>` |
| [b](b.md) | `val b: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`B`](-binder/index.md#B)`>` |
| [c](c.md) | `val c: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`C`](-binder/index.md#C)`>` |
| [d](d.md) | `val d: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`D`](-binder/index.md#D)`>` |
| [e](e.md) | `val e: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`E`](-binder/index.md#E)`>` |
| [f](f.md) | `val f: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`F`](-binder/index.md#F)`>` |
| [g](g.md) | `val g: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`G`](-binder/index.md#G)`>` |
| [h](h.md) | `val h: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`H`](-binder/index.md#H)`>` |
| [i](i.md) | `val i: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`I`](-binder/index.md#I)`>` |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`ContractRouteSpec9.Binder`](-binder/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`, `[`I`](-binder/index.md#I)`>` |
| [div](div.md) | `infix operator fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`, `[`I`](-binder/index.md#I)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`infix operator fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec10`](../-contract-route-spec10/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`, `[`I`](-binder/index.md#I)`, `[`NEXT`](div.md#NEXT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A, B, C, D, E, F, G, H, I> `[`ContractRouteSpec9`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`, `[`I`](../meta.md#I)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec9`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`, `[`I`](../meta.md#I)`>` |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
