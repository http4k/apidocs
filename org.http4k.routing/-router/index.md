[http4k](../../index.md) / [org.http4k.routing](../index.md) / [Router](./index.md)

# Router

`interface Router`

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | Attempt to supply an HttpHandler which can service the passed request.`abstract fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`RouterMatch`](../-router-match/index.md) |
| [withBasePath](with-base-path.md) | Returns a Router which prepends the passed base path to the logic determining the match().`open fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Router`](./index.md) |
| [withFilter](with-filter.md) | Returns a Router which applies the passed Filter to all received requests before servicing them.`open fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`Router`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `infix fun `[`Router`](./index.md)`.and(that: `[`Router`](./index.md)`): `[`Router`](./index.md) |
| [bind](../bind.md) | `infix fun `[`Router`](./index.md)`.bind(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](../-routing-http-handler/index.md)<br>`infix fun `[`Router`](./index.md)`.bind(handler: `[`RoutingHttpHandler`](../-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../-routing-http-handler/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ResourceLoading](../../org.http4k.routing.experimental/-resource-loading/index.md) | A little convenience thunk to simplify implementing [Router](./index.md) for resource loaders.`interface ResourceLoading : `[`Router`](./index.md) |
| [RoutingHttpHandler](../-routing-http-handler/index.md) | Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request.`interface RoutingHttpHandler : `[`Router`](./index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
