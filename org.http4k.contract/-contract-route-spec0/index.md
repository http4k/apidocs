[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRouteSpec0](./index.md)

# ContractRouteSpec0

`class ContractRouteSpec0 : `[`ContractRouteSpec`](../-contract-route-spec/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeSpec.kt#L24)

### Types

| Name | Summary |
|---|---|
| [Binder](-binder/index.md) | `inner class Binder : `[`ContractRequestBuilder`](../-contract-route-spec/-contract-request-builder/index.md) |

### Inherited Properties

| Name | Summary |
|---|---|
| [pathFn](../-contract-route-spec/path-fn.md) | `val pathFn: (`[`PathSegments`](../-path-segments/index.md)`) -> `[`PathSegments`](../-path-segments/index.md) |
| [pathLenses](../-contract-route-spec/path-lenses.md) | `vararg val pathLenses: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<*>>` |
| [routeMeta](../-contract-route-spec/route-meta.md) | `val routeMeta: `[`RouteMeta`](../-route-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun bindContract(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`Binder`](-binder/index.md) |
| [div](div.md) | `operator infix fun div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec0`](./index.md)<br>`operator infix fun <NEXT> div(next: `[`PathLens`](../../org.http4k.lens/-path-lens/index.md)`<`[`NEXT`](div.md#NEXT)`>): `[`ContractRouteSpec1`](../-contract-route-spec1/index.md)`<`[`NEXT`](div.md#NEXT)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [meta](../meta.md) | `infix fun `[`ContractRouteSpec0`](./index.md)`.meta(new: `[`RouteMetaDsl`](../-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec0`](./index.md) |
