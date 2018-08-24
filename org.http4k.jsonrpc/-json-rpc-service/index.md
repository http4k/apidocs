[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonRpcService](./index.md)

# JsonRpcService

`data class JsonRpcService<ROOT : `[`NODE`](index.md#NODE)`, NODE> : `[`HttpHandler`](../../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/JsonRpcService.kt#L24)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonRpcService(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>, errorHandler: `[`ErrorHandler`](../-error-handler.md)`, methodMappings: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MethodMapping`](../-method-mapping/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>>)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosControls](../../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |
