[http4k](../index.md) / [org.http4k.routing](./index.md)

## Package org.http4k.routing

Code for routing HTTP messages inside server implementations.

### Types

| Name | Summary |
|---|---|
| [PathMethod](-path-method/index.md) | `class PathMethod` |
| [ResourceLoader](-resource-loader/index.md) | `interface ResourceLoader` |
| [RoutedRequest](-routed-request/index.md) | `data class RoutedRequest : `[`Request`](../org.http4k.core/-request/index.md) |
| [RoutedResponse](-routed-response/index.md) | `class RoutedResponse : `[`Response`](../org.http4k.core/-response/index.md) |
| [Router](-router/index.md) | `interface Router` |
| [RouterMatch](-router-match/index.md) | The result of a matching operation. May or may not contain a matched HttpHandler.`sealed class RouterMatch : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`RouterMatch`](-router-match/index.md)`>` |
| [RoutingHttpHandler](-routing-http-handler/index.md) | Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request.`interface RoutingHttpHandler : `[`Router`](-router/index.md)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [RoutingWsHandler](-routing-ws-handler/index.md) | `interface RoutingWsHandler : `[`WsHandler`](../org.http4k.websocket/-ws-handler.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [&lt;no name provided&gt;](-no name provided-.md) | Looks up contents of a resource path.`fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [and](and.md) | `fun `[`Method`](../org.http4k.core/-method/index.md)`.and(that: `[`Router`](-router/index.md)`): <ERROR CLASS>`<br>`infix fun `[`Router`](-router/index.md)`.and(that: `[`Router`](-router/index.md)`): `[`Router`](-router/index.md) |
| [asRouter](as-router.md) | `fun `[`Method`](../org.http4k.core/-method/index.md)`.asRouter(): <ERROR CLASS>` |
| [bind](bind.md) | `infix fun `[`Router`](-router/index.md)`.bind(handler: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](-routing-http-handler/index.md)<br>`infix fun `[`Router`](-router/index.md)`.bind(handler: `[`RoutingHttpHandler`](-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [body](body.md) | Ensure body matches predicate`fun body(predicate: (`[`Body`](../org.http4k.core/-body/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](-router/index.md)<br>Ensure body string matches predicate`fun body(predicate: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](-router/index.md) |
| [graphQL](graph-q-l.md) | Routing plugin for GraphQL handling.`fun graphQL(handler: `[`GraphQLHandler`](../org.http4k.graphql/-graph-q-l-handler.md)`, badRequestFn: (`[`LensFailure`](../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { Response(BAD_REQUEST) }): `[`RoutingHttpHandler`](-routing-http-handler/index.md)<br>Routing plugin for GraphQL handling with contextual data.`fun <T> graphQL(handler: `[`GraphQLWithContextHandler`](../org.http4k.graphql/-graph-q-l-with-context-handler.md)`<T>, getContext: (`[`Request`](../org.http4k.core/-request/index.md)`) -> T, badRequestFn: (`[`LensFailure`](../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { Response(BAD_REQUEST) }): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [header](header.md) | Apply routing predicate to a header`fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, predicate: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](-router/index.md)<br>`fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Router`](-router/index.md) |
| [headers](headers.md) | Ensure all headers are present`fun headers(vararg names: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Router`](-router/index.md) |
| [hostDemux](host-demux.md) | Matches the Host header to a matching Handler.`fun hostDemux(vararg hosts: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [path](path.md) | `fun `[`Request`](../org.http4k.core/-request/index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [queries](queries.md) | Ensure all queries are present`fun queries(vararg names: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Router`](-router/index.md) |
| [query](query.md) | Apply routing predicate to a query`fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, predicate: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](-router/index.md)<br>`fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Router`](-router/index.md) |
| [routes](routes.md) | `fun routes(vararg list: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Method`](../org.http4k.core/-method/index.md)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md)<br>`fun routes(vararg list: `[`RoutingHttpHandler`](-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [singlePageApp](single-page-app.md) | For SPAs we serve static content as usual, or fall back to the index page. The resource loader is configured to look at /public package (on the Classpath).`fun singlePageApp(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = ResourceLoader.Classpath("/public"), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [static](static.md) | Serve static content using the passed ResourceLoader. Note that for security, by default ONLY mime-types registered in mime.types (resource file) will be served. All other types are registered as application/octet-stream and are not served.`fun static(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = Classpath(), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) |
| [websockets](websockets.md) | `fun websockets(ws: `[`WsConsumer`](../org.http4k.websocket/-ws-consumer.md)`): `[`WsHandler`](../org.http4k.websocket/-ws-handler.md)<br>`fun websockets(vararg list: `[`RoutingWsHandler`](-routing-ws-handler/index.md)`): `[`RoutingWsHandler`](-routing-ws-handler/index.md) |
