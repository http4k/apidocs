[http4k](../../index.md) / [org.http4k.routing](../index.md) / [Router](./index.md)

# Router

`interface Router`

Provides matching of a Request to an HttpHandler which can service it.

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | Attempt to supply an HttpHandler which can service the passed request.`abstract fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?` |

### Inheritors

| Name | Summary |
|---|---|
| [ResourceLoading](../../org.http4k.routing.experimental/-resource-loading/index.md) | A little convenience thunk to simplify implementing [Router](./index.md) for resource loaders.`interface ResourceLoading : `[`Router`](./index.md) |
| [RoutingHttpHandler](../-routing-http-handler/index.md) | Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request.`interface RoutingHttpHandler : `[`Router`](./index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
