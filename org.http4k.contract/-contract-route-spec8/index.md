[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec8](./index.md)

# ContractRouteSpec8

`class ContractRouteSpec8<out A, out B, out C, out D, out E, out F, out G, out H> : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L140)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder<out A, out B, out C, out D, out E, out F, out G, out H> : `[`ContractRequestBuilder`](../-contract-route-spec/-contract-request-builder/index.md) |

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

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`Binder`](-binder/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`>` |
| [div](div.md) | `operator infix fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec9`](../-contract-route-spec9/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator infix fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec9`](../-contract-route-spec9/index.md)`<`[`A`](-binder/index.md#A)`, `[`B`](-binder/index.md#B)`, `[`C`](-binder/index.md#C)`, `[`D`](-binder/index.md#D)`, `[`E`](-binder/index.md#E)`, `[`F`](-binder/index.md#F)`, `[`G`](-binder/index.md#G)`, `[`H`](-binder/index.md#H)`, `[`NEXT`](div.md#NEXT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun <A, B, C, D, E, F, G, H> `[`ContractRouteSpec8`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`>.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec8`](./index.md)`<`[`A`](../meta.md#A)`, `[`B`](../meta.md#B)`, `[`C`](../meta.md#C)`, `[`D`](../meta.md#D)`, `[`E`](../meta.md#E)`, `[`F`](../meta.md#F)`, `[`G`](../meta.md#G)`, `[`H`](../meta.md#H)`>` |
