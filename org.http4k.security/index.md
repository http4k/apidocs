[http4k](../index.md) / [org.http4k.security](./index.md)

## Package org.http4k.security

Code relevant to interfacing with security mechanisms such as OAuth servers.

### Types

| Name | Summary |
|---|---|
| [AccessToken](-access-token/index.md) | `data class AccessToken` |
| [AccessTokenContainer](-access-token-container.md) | `typealias ~~AccessTokenContainer~~ = `[`AccessToken`](-access-token/index.md) |
| [AccessTokenDetails](-access-token-details/index.md) | `data class AccessTokenDetails` |
| [AccessTokenFetcher](-access-token-fetcher/index.md) | `class AccessTokenFetcher` |
| [AccessTokenFetcherAuthenticator](-access-token-fetcher-authenticator/index.md) | `interface AccessTokenFetcherAuthenticator` |
| [AccessTokenResponse](-access-token-response/index.md) | `data class AccessTokenResponse` |
| [ClientSecretAccessTokenFetcherAuthenticator](-client-secret-access-token-fetcher-authenticator/index.md) | `class ClientSecretAccessTokenFetcherAuthenticator : `[`AccessTokenFetcherAuthenticator`](-access-token-fetcher-authenticator/index.md) |
| [CrossSiteRequestForgeryToken](-cross-site-request-forgery-token/index.md) | `data class CrossSiteRequestForgeryToken` |
| [CsrfGenerator](-csrf-generator.md) | `typealias CsrfGenerator = () -> `[`CrossSiteRequestForgeryToken`](-cross-site-request-forgery-token/index.md) |
| [InsecureCookieBasedOAuthPersistence](-insecure-cookie-based-o-auth-persistence/index.md) | This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production!`class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](-o-auth-persistence/index.md) |
| [OAuthCallback](-o-auth-callback/index.md) | `class OAuthCallback : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [OAuthPersistence](-o-auth-persistence/index.md) | Provides persistence for OAuth lifecycle values:`interface OAuthPersistence` |
| [OAuthProvider](-o-auth-provider/index.md) | Provides a configured set of objects for use with an OAuth2 provider.`class OAuthProvider` |
| [OAuthProviderConfig](-o-auth-provider-config/index.md) | `data class OAuthProviderConfig` |
| [OAuthRedirectionFilter](-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](../org.http4k.core/-filter.md) |
| [RedirectionUriBuilder](-redirection-uri-builder.md) | `typealias RedirectionUriBuilder = (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, state: `[`State`](-state/index.md)`, nonce: `[`Nonce`](../org.http4k.security.openid/-nonce/index.md)`?) -> `[`Uri`](../org.http4k.core/-uri/index.md) |
| [ResponseMode](-response-mode/index.md) | `enum class ResponseMode` |
| [ResponseType](-response-type/index.md) | `enum class ResponseType` |
| [State](-state/index.md) | `data class State` |

### Properties

| Name | Summary |
|---|---|
| [accessTokenResponseBody](access-token-response-body.md) | `val accessTokenResponseBody: `[`BiDiBodyLens`](../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`AccessTokenResponse`](-access-token-response/index.md)`>` |
| [defaultUriBuilder](default-uri-builder.md) | `val defaultUriBuilder: `[`RedirectionUriBuilder`](-redirection-uri-builder.md) |

### Functions

| Name | Summary |
|---|---|
| [&lt;no name provided&gt;](-no name provided-.md) | `fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [fragmentParameter](fragment-parameter.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](../org.http4k.core/-uri/index.md)<br>Retrieves the first fragment parameter value with this name.`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>(Copy &amp;) Adds a query value with this name.`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](../org.http4k.core/-request/index.md) |
| [fragmentParameters](fragment-parameters.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.fragmentParameters(): `[`Parameters`](../org.http4k.core/-parameters.md)<br>Retrieves all fragment parameters with this name.`fun `[`Request`](../org.http4k.core/-request/index.md)`.fragmentParameters(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [removeFragmentParameter](remove-fragment-parameter.md) | `fun `[`Uri`](../org.http4k.core/-uri/index.md)`.removeFragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](../org.http4k.core/-uri/index.md) |
| [uriBuilderWithRequestJwt](uri-builder-with-request-jwt.md) | `fun uriBuilderWithRequestJwt(requestJwts: `[`RequestJwts`](../org.http4k.security.openid/-request-jwts/index.md)`): (`[`Uri`](../org.http4k.core/-uri/index.md)`, `[`AuthRequest`](../org.http4k.security.oauth.server/-auth-request/index.md)`, `[`State`](-state/index.md)`, `[`Nonce`](../org.http4k.security.openid/-nonce/index.md)`?) -> `[`Uri`](../org.http4k.core/-uri/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auth0](auth0.md) | Preconfigured OAuthProviders go here...`fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [dropbox](dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [facebook](facebook.md) | `fun OAuthProvider.Companion.facebook(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("email")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [gitHub](git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf()): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [google](google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](-o-auth-provider/index.md) |
| [soundCloud](sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](-o-auth-persistence/index.md)`): `[`OAuthProvider`](-o-auth-provider/index.md) |
