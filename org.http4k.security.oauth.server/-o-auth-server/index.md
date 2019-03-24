[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [OAuthServer](./index.md)

# OAuthServer

`class OAuthServer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/OAuthServer.kt#L19)

Provide help creating OAuth Authorization Server with Authorization Code Flow

References:

* Authorization Code Grant flow spec: https://tools.ietf.org/html/rfc6749#page-23
* OAuth 2 Security Best Current Practices: https://tools.ietf.org/html/draft-ietf-oauth-security-topics-11

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthServer(tokenPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authRequestPersistence: `[`AuthRequestPersistence`](../-auth-request-persistence/index.md)`, clientValidator: `[`ClientValidator`](../-client-validator/index.md)`, authorizationCodes: `[`AuthorizationCodes`](../-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../-access-tokens/index.md)`, clock: Clock)`<br>Provide help creating OAuth Authorization Server with Authorization Code Flow |

### Properties

| Name | Summary |
|---|---|
| [authenticationComplete](authentication-complete.md) | `val authenticationComplete: `[`AuthenticationCompleteFilter`](../-authentication-complete-filter/index.md) |
| [authenticationStart](authentication-start.md) | `val authenticationStart: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [tokenRoute](token-route.md) | `val tokenRoute: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [clientId](client-id.md) | `val clientId: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ClientId`](../-client-id/index.md)`>` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [scopes](scopes.md) | `val scopes: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?>` |
| [state](state.md) | `val state: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |