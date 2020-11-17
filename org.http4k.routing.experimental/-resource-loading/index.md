[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoading](./index.md)

# ResourceLoading

`interface ResourceLoading : `[`Router`](../../org.http4k.routing/-router/index.md)

A little convenience thunk to simplify implementing [Router](../../org.http4k.routing/-router/index.md) for resource loaders.

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | `abstract fun match(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request.`open fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`RouterMatch`](../../org.http4k.routing/-router-match/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.routing/and.md) | `infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.and(that: `[`Router`](../../org.http4k.routing/-router/index.md)`): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [bind](../../org.http4k.routing/bind.md) | `infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.bind(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>`infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.bind(handler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
