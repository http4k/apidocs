[http4k](../index.md) / [org.http4k.core](index.md) / [HttpHandler](./-http-handler.md)

# HttpHandler

`typealias HttpHandler = (`[`Request`](-request/index.md)`) -> `[`Response`](-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Http4k.kt#L5)

### Inheritors

| Name | Summary |
|---|---|
| [AuthenticationComplete](../org.http4k.security.oauth.server/-authentication-complete/index.md) | `class AuthenticationComplete : `[`HttpHandler`](./-http-handler.md) |
| [DualSyncAsyncHttpHandler](../org.http4k.client/-dual-sync-async-http-handler.md) | `interface DualSyncAsyncHttpHandler : `[`HttpHandler`](./-http-handler.md)`, `[`AsyncHttpClient`](../org.http4k.client/-async-http-client/index.md) |
| [GenerateAccessToken](../org.http4k.security.oauth.server/-generate-access-token/index.md) | `class GenerateAccessToken : `[`HttpHandler`](./-http-handler.md) |
| [JsonRpcService](../org.http4k.jsonrpc/-json-rpc-service/index.md) | `data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](./-http-handler.md) |
| [Liveness](../org.http4k.cloudnative.health/-liveness.md) | `object Liveness : `[`HttpHandler`](./-http-handler.md)<br>The Liveness check is used to determine if an app is alive. |
| [OAuthCallback](../org.http4k.security/-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](./-http-handler.md) |
| [Resource](../org.http4k.routing.experimental/-resource/index.md) | `interface Resource : `[`HttpHandler`](./-http-handler.md) |
| [ResourceListingHandler](../org.http4k.routing.experimental/-resource-listing-handler/index.md) | `class ResourceListingHandler : `[`HttpHandler`](./-http-handler.md) |
| [RoutingHttpHandler](../org.http4k.routing/-routing-http-handler/index.md) | `interface RoutingHttpHandler : `[`Router`](../org.http4k.routing/-router/index.md)`, `[`HttpHandler`](./-http-handler.md)<br>Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request. |
