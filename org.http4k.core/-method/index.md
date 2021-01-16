[http4k](../../index.md) / [org.http4k.core](../index.md) / [Method](./index.md)

# Method

`enum class Method`

### Enum Values

| Name | Summary |
|---|---|
| [GET](-g-e-t.md) |  |
| [POST](-p-o-s-t.md) |  |
| [PUT](-p-u-t.md) |  |
| [DELETE](-d-e-l-e-t-e.md) |  |
| [OPTIONS](-o-p-t-i-o-n-s.md) |  |
| [TRACE](-t-r-a-c-e.md) |  |
| [PATCH](-p-a-t-c-h.md) |  |
| [PURGE](-p-u-r-g-e.md) |  |
| [HEAD](-h-e-a-d.md) |  |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.routing/and.md) | `fun `[`Method`](./index.md)`.and(that: `[`Router`](../../org.http4k.routing/-router/index.md)`): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [asRouter](../../org.http4k.routing/as-router.md) | `fun `[`Method`](./index.md)`.asRouter(): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [bind](../../org.http4k.routing/bind.md) | `infix fun `[`Method`](./index.md)`.bind(routingHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>`infix fun `[`Method`](./index.md)`.bind(httpHandler: `[`HttpHandler`](../-http-handler.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
