[http4k](../../index.md) / [org.http4k.server](../index.md) / [HttpUndertowHandler](./index.md)

# HttpUndertowHandler

`class HttpUndertowHandler : `[`HttpHandler`](http://undertow.io/javadoc/2.0.x/io/undertow/server/HttpHandler.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-undertow/src/main/kotlin/org/http4k/server/Undertow.kt#L22)

Exposed to allow for insertion into a customised Undertow server instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpUndertowHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>Exposed to allow for insertion into a customised Undertow server instance |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `fun handleRequest(exchange: `[`HttpServerExchange`](http://undertow.io/javadoc/2.0.x/io/undertow/server/HttpServerExchange.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
