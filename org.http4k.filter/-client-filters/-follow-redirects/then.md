[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [FollowRedirects](index.md) / [then](./then.md)

# then

`fun then(router: `[`RoutingHttpHandler`](../../../org.http4k.routing/-routing-http-handler/index.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)

This filter requires special treatment for routing handlers.

In general, Filters are applied *after* routing (i.e. routing information is available to filters).
This filter, however, needs to behave like a browser, and for that we apply the filter *before* the routing.

