[http4k](../index.md) / [org.http4k.core](index.md) / [HttpHandler](./-http-handler.md)

# HttpHandler

`typealias HttpHandler = (`[`Request`](-request/index.md)`) -> `[`Response`](-response/index.md)

### Inheritors

| Name | Summary |
|---|---|
| [AuthenticationComplete](../org.http4k.security.oauth.server/-authentication-complete/index.md) | `class AuthenticationComplete : `[`HttpHandler`](./-http-handler.md) |
| [ContractRoute](../org.http4k.contract/-contract-route/index.md) | `class ContractRoute : `[`HttpHandler`](./-http-handler.md) |
| [DualSyncAsyncHttpHandler](../org.http4k.client/-dual-sync-async-http-handler.md) | `interface DualSyncAsyncHttpHandler : `[`HttpHandler`](./-http-handler.md)`, `[`AsyncHttpClient`](../org.http4k.client/-async-http-client/index.md) |
| [GenerateAccessToken](../org.http4k.security.oauth.server/-generate-access-token/index.md) | `class GenerateAccessToken : `[`HttpHandler`](./-http-handler.md) |
| [JavaHttpClient](../org.http4k.client/-java-http-client/index.md) | Basic JDK-based Client.`class JavaHttpClient : `[`HttpHandler`](./-http-handler.md) |
| [JsonRpcService](../org.http4k.jsonrpc/-json-rpc-service/index.md) | `data class JsonRpcService<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`HttpHandler`](./-http-handler.md) |
| [Liveness](../org.http4k.cloudnative.health/-liveness.md) | The Liveness check is used to determine if an app is alive.`object Liveness : `[`HttpHandler`](./-http-handler.md) |
| [OAuthCallback](../org.http4k.security/-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](./-http-handler.md) |
| [Resource](../org.http4k.routing.experimental/-resource/index.md) | `interface Resource : `[`HttpHandler`](./-http-handler.md) |
| [ResourceListingHandler](../org.http4k.routing.experimental/-resource-listing-handler/index.md) | `class ResourceListingHandler : `[`HttpHandler`](./-http-handler.md) |
| [RoutingHttpHandler](../org.http4k.routing/-routing-http-handler/index.md) | Composite HttpHandler which can potentially service many different URL patterns. Should return a 404 Response if it cannot service a particular Request.`interface RoutingHttpHandler : `[`Router`](../org.http4k.routing/-router/index.md)`, `[`HttpHandler`](./-http-handler.md) |
