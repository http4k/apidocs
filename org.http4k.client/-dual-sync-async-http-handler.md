[http4k](../index.md) / [org.http4k.client](index.md) / [DualSyncAsyncHttpHandler](./-dual-sync-async-http-handler.md)

# DualSyncAsyncHttpHandler

`interface DualSyncAsyncHttpHandler : `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](-async-http-client/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/client/ext.kt#L13)

### Inherited Functions

| Name | Summary |
|---|---|
| [close](-async-http-client/close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invoke](-async-http-client/invoke.md) | `abstract operator fun invoke(request: `[`Request`](../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asK8sServer](../org.http4k.cloudnative/kotlin.-function1/as-k8s-server.md) | `fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../org.http4k.server/-server-config/index.md)`, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, healthApp: `[`HttpHandler`](../org.http4k.core/-http-handler.md)` = Health(), healthPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8001): `[`Http4kK8sServer`](../org.http4k.cloudnative/-http4k-k8s-server/index.md)<br>`fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../org.http4k.server/-server-config/index.md)`, env: `[`Environment`](../org.http4k.cloudnative.env/-environment/index.md)` = ENV, healthApp: `[`HttpHandler`](../org.http4k.core/-http-handler.md)` = Health()): `[`Http4kK8sServer`](../org.http4k.cloudnative/-http4k-k8s-server/index.md) |
| [asServer](../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosControls](../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`Stage`](../org.http4k.chaos/-stage.md)` = Wait, security: `[`Security`](../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |