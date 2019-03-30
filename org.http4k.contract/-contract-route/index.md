[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoute](./index.md)

# ContractRoute

`class ContractRoute` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/ContractRoute.kt#L17)

### Properties

| Name | Summary |
|---|---|
| [jsonRequest](json-request.md) | `val jsonRequest: `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>?` |
| [meta](meta.md) | `val meta: `[`RouteMeta`](../-route-meta/index.md) |
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [nonBodyParams](non-body-params.md) | `val nonBodyParams: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../../org.http4k.lens/-meta/index.md)`>` |
| [spec](spec.md) | `val spec: `[`ContractRouteSpec`](../-contract-route-spec/index.md) |
| [tags](tags.md) | `val tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Tag`](../-tag/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [describeFor](describe-for.md) | `fun describeFor(contractRoot: `[`PathSegments`](../-path-segments/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [newRequest](new-request.md) | `fun newRequest(baseUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
