[http4k](../index.md) / [org.http4k.core](index.md) / [HttpHandler](./-http-handler.md)

# HttpHandler

`typealias HttpHandler = (`[`Request`](-request/index.md)`) -> `[`Response`](-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Http4k.kt#L5)

### Inheritors

| Name | Summary |
|---|---|
| [ApacheClient](../org.http4k.client/-apache-client/index.md) | `class ApacheClient : `[`HttpHandler`](./-http-handler.md) |
| [JavaHttpClient](../org.http4k.client/-java-http-client/index.md) | `class JavaHttpClient : `[`HttpHandler`](./-http-handler.md) |
| [JettyClient](../org.http4k.client/-jetty-client/index.md) | `class JettyClient : `[`HttpHandler`](./-http-handler.md)`, `[`AsyncHttpClient`](../org.http4k.client/-async-http-client/index.md) |
| [JsonRpcService](../org.http4k.jsonrpc/-json-rpc-service/index.md) | `data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](./-http-handler.md) |
| [Liveness](../org.http4k.cloudnative.health/-liveness.md) | `object Liveness : `[`HttpHandler`](./-http-handler.md)<br>The Liveness check is used to determine if an app is alive. |
| [OAuthCallback](../org.http4k.security/-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](./-http-handler.md) |
| [OkHttp](../org.http4k.client/-ok-http/index.md) | `class OkHttp : `[`HttpHandler`](./-http-handler.md)`, `[`AsyncHttpClient`](../org.http4k.client/-async-http-client/index.md) |
| [Resource](../org.http4k.routing.experimental/-resource/index.md) | `interface Resource : `[`HttpHandler`](./-http-handler.md) |
| [ResourceListingHandler](../org.http4k.routing.experimental/-resource-listing-handler/index.md) | `class ResourceListingHandler : `[`HttpHandler`](./-http-handler.md) |
| [RoutingHttpHandler](../org.http4k.routing/-routing-http-handler/index.md) | `interface RoutingHttpHandler : `[`Router`](../org.http4k.routing/-router/index.md)`, `[`HttpHandler`](./-http-handler.md)<br>Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request. |
