[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kRequestHandler](./index.md)

# Http4kRequestHandler

`class Http4kRequestHandler : HttpRequestHandler`

Exposed to allow for insertion into a customised Apache WebServer instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Exposed to allow for insertion into a customised Apache WebServer instance`Http4kRequestHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: ClassicHttpRequest, response: ClassicHttpResponse, context: HttpContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
