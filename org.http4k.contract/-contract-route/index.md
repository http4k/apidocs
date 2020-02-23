[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoute](./index.md)

# ContractRoute

`class ContractRoute : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `val meta: `[`RouteMeta`](../-route-meta/index.md) |
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [nonBodyParams](non-body-params.md) | `val nonBodyParams: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../../org.http4k.lens/-meta/index.md)`>` |
| [spec](spec.md) | `val spec: `[`ContractRouteSpec`](../-contract-route-spec/index.md) |
| [tags](tags.md) | `val tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Tag`](../-tag/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [describeFor](describe-for.md) | `fun describeFor(contractRoot: `[`PathSegments`](../-path-segments/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [invoke](invoke.md) | ContractRoutes are chiefly designed to operate within a contract {} block and not directly as an HttpHandler, but this function exists to enable the testing of the ContractRoute logic outside of a wider contract context. This means that certain behaviour is defaulted - chiefly the generation of NOT_FOUND and BAD_REQUEST responses.`fun invoke(p1: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [newRequest](new-request.md) | `fun newRequest(baseUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [operationId](../../org.http4k.contract.openapi/operation-id.md) | `fun `[`ContractRoute`](./index.md)`.operationId(contractRoot: `[`PathSegments`](../-path-segments/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
