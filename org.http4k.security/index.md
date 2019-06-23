[http4k](../index.md) / [org.http4k.security](./index.md)

## Package org.http4k.security

Code relevant to interfacing with security mechanisms such as OAuth servers.

### Types

| Name | Summary |
|---|---|
| [AccessToken](-access-token/index.md) | `data class AccessToken` |
| [AccessTokenDetails](-access-token-details/index.md) | `data class AccessTokenDetails` |
| [AccessTokenFetcher](-access-token-fetcher/index.md) | `class AccessTokenFetcher` |
| [AccessTokenResponse](-access-token-response/index.md) | `data class AccessTokenResponse` |
| [CrossSiteRequestForgeryToken](-cross-site-request-forgery-token/index.md) | `data class CrossSiteRequestForgeryToken` |
| [InsecureCookieBasedOAuthPersistence](-insecure-cookie-based-o-auth-persistence/index.md) | `class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](-o-auth-persistence/index.md)<br>This is an example implementation which stores CSRF and AccessTokenEnvelope values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production! |
| [OAuthCallback](-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [OAuthPersistence](-o-auth-persistence/index.md) | `interface OAuthPersistence`<br>Provides persistence for OAuth lifecycle values: |
| [OAuthProvider](-o-auth-provider/index.md) | `class OAuthProvider`<br>Provides a configured set of objects for use with an OAuth2 provider. |
| [OAuthProviderConfig](-o-auth-provider-config/index.md) | `data class OAuthProviderConfig` |
| [OAuthRedirectionFilter](-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [ResponseType](-response-type/index.md) | `enum class ResponseType` |

### Type Aliases

| Name | Summary |
|---|---|
| [CsrfGenerator](-csrf-generator.md) | `typealias CsrfGenerator = () -> `[`CrossSiteRequestForgeryToken`](-cross-site-request-forgery-token/index.md) |
| [RedirectionUriBuilder](-redirection-uri-builder.md) | `typealias RedirectionUriBuilder = (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, state: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Uri`](../org.http4k.core/-uri/index.md) |

### Properties

| Name | Summary |
|---|---|
| [accessTokenResponseBody](access-token-response-body.md) | `val accessTokenResponseBody: `[`BiDiBodyLens`](../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`AccessTokenResponse`](-access-token-response/index.md)`>` |
| [defaultUriBuilder](default-uri-builder.md) | `val defaultUriBuilder: `[`RedirectionUriBuilder`](-redirection-uri-builder.md) |

### Functions

| Name | Summary |
|---|---|
| [uriBuilderWithRequestJwt](uri-builder-with-request-jwt.md) | `fun uriBuilderWithRequestJwt(requestJwts: `[`RequestJwts`](../org.http4k.security.openid/-request-jwts/index.md)`): (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Uri`](../org.http4k.core/-uri/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auth0](auth0.md) | `fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md)<br>Preconfigured OAuthProviders go here... |
| [dropbox](dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [gitHub](git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("user")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [google](google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [soundCloud](sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
