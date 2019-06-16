[http4k](../../index.md) / [org.http4k.servlet](../index.md) / [HttpHandlerServlet](./index.md)

# HttpHandlerServlet

`class HttpHandlerServlet : `[`HttpServlet`](https://javaee.github.io/javaee-spec/javadocs/javax/servlet/http/HttpServlet.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/servlet/servlet.kt#L18)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpHandlerServlet(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [service](service.md) | `fun service(req: `[`HttpServletRequest`](https://javaee.github.io/javaee-spec/javadocs/javax/servlet/http/HttpServletRequest.html)`, resp: `[`HttpServletResponse`](https://javaee.github.io/javaee-spec/javadocs/javax/servlet/http/HttpServletResponse.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
