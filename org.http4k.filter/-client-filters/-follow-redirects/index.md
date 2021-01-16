[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [FollowRedirects](./index.md)

# FollowRedirects

`class FollowRedirects : `[`Filter`](../../../org.http4k.core/-filter.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FollowRedirects()` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
| [then](then.md) | This filter requires special treatment for routing handlers.`fun then(router: `[`RoutingHttpHandler`](../../../org.http4k.routing/-routing-http-handler/index.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
