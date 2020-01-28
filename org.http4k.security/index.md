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
| [InsecureCookieBasedOAuthPersistence](-insecure-cookie-based-o-auth-persistence/index.md) | `class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](-o-auth-persistence/index.md)<br>This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production! |
| [OAuthCallback](-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [OAuthPersistence](-o-auth-persistence/index.md) | `interface OAuthPersistence`<br>Provides persistence for OAuth lifecycle values: |
| [OAuthProvider](-o-auth-provider/index.md) | `class OAuthProvider`<br>Provides a configured set of objects for use with an OAuth2 provider. |
| [OAuthProviderConfig](-o-auth-provider-config/index.md) | `data class OAuthProviderConfig` |
| [OAuthRedirectionFilter](-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [ResponseMode](-response-mode/index.md) | `enum class ResponseMode` |
| [ResponseType](-response-type/index.md) | `enum class ResponseType` |
| [State](-state/index.md) | `data class State` |

### Type Aliases

| Name | Summary |
|---|---|
| [AccessTokenContainer](-access-token-container.md) | `typealias ~~AccessTokenContainer~~ = `[`AccessToken`](-access-token/index.md) |
| [CsrfGenerator](-csrf-generator.md) | `typealias CsrfGenerator = () -> `[`CrossSiteRequestForgeryToken`](-cross-site-request-forgery-token/index.md) |
| [RedirectionUriBuilder](-redirection-uri-builder.md) | `typealias RedirectionUriBuilder = (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, state: `[`State`](-state/index.md)`, nonce: `[`Nonce`](../org.http4k.security.openid/-nonce/index.md)`?) -> `[`Uri`](../org.http4k.core/-uri/index.md) |

### Properties

| Name | Summary |
|---|---|
| [accessTokenResponseBody](access-token-response-body.md) | `val accessTokenResponseBody: `[`BiDiBodyLens`](../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`AccessTokenResponse`](-access-token-response/index.md)`>` |
| [defaultUriBuilder](default-uri-builder.md) | `val defaultUriBuilder: `[`RedirectionUriBuilder`](-redirection-uri-builder.md) |

### Functions

| Name | Summary |
|---|---|
| [fragmentParameter](fragment-parameter.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](../org.http4k.core/-uri/index.md)`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Retrieves the first fragment parameter value with this name.`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](../org.http4k.core/-request/index.md)<br>(Copy &amp;) Adds a query value with this name. |
| [fragmentParameters](fragment-parameters.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.fragmentParameters(): `[`Parameters`](../org.http4k.core/-parameters.md)`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameters(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>`<br>Retrieves all fragment parameters with this name. |
| [removeFragmentParameter](remove-fragment-parameter.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.removeFragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](../org.http4k.core/-uri/index.md) |
| [uriBuilderWithRequestJwt](uri-builder-with-request-jwt.md) | `fun uriBuilderWithRequestJwt(requestJwts: `[`RequestJwts`](../org.http4k.security.openid/-request-jwts/index.md)`): (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, `[`State`](-state/index.md)`, `[`Nonce`](../org.http4k.security.openid/-nonce/index.md)`?) -> `[`Uri`](../org.http4k.core/-uri/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auth0](auth0.md) | `fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md)<br>Preconfigured OAuthProviders go here... |
| [dropbox](dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [gitHub](git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("user")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [google](google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [soundCloud](sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
