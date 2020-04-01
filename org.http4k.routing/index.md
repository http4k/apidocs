[http4k](../index.md) / [org.http4k.routing](./index.md)

## Package org.http4k.routing

Code for routing HTTP messages inside server implementations.

### Types

| Name | Summary |
|---|---|
| [PathMethod](-path-method/index.md) | `data class PathMethod` |
| [ResourceLoader](-resource-loader/index.md) | Looks up contents of a resource path.`interface ResourceLoader` |
| [RoutedRequest](-routed-request/index.md) | `data class RoutedRequest : `[`Request`](../org.http4k.core/-request/index.md) |
| [RoutedResponse](-routed-response/index.md) | `class RoutedResponse : `[`Response`](../org.http4k.core/-response/index.md) |
| [Router](-router/index.md) | Provides matching of a Request to an HttpHandler which can service it.`interface Router` |
| [RouterMatch](-router-match/index.md) | `sealed class RouterMatch : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`RouterMatch`](-router-match/index.md)`>` |
| [RoutingHttpHandler](-routing-http-handler/index.md) | Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request.`interface RoutingHttpHandler : `[`Router`](-router/index.md)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [RoutingWsHandler](-routing-ws-handler/index.md) | `interface RoutingWsHandler : `[`WsHandler`](../org.http4k.websocket/-ws-handler.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [path](path.md) | `fun `[`Request`](../org.http4k.core/-request/index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [routes](routes.md) | `fun routes(vararg list: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Method`](../org.http4k.core/-method/index.md)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md)<br>`fun routes(vararg list: `[`RoutingHttpHandler`](-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [singlePageApp](single-page-app.md) | For SPAs we serve static content as usual, or fall back to the index page. The resource loader is configured to look at /public package (on the Classpath).`fun singlePageApp(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = ResourceLoader.Classpath("/public"), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [static](static.md) | Serve static content using the passed ResourceLoader. Note that for security, by default ONLY mime-types registered in mime.types (resource file) will be served. All other types are registered as application/octet-stream and are not served.`fun static(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = ResourceLoader.Classpath(), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [websockets](websockets.md) | `fun websockets(ws: `[`WsConsumer`](../org.http4k.websocket/-ws-consumer.md)`): `[`WsHandler`](../org.http4k.websocket/-ws-handler.md)<br>`fun websockets(vararg list: `[`RoutingWsHandler`](-routing-ws-handler/index.md)`): `[`RoutingWsHandler`](-routing-ws-handler/index.md) |
