[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthProvider](./index.md)

# OAuthProvider

`class OAuthProvider`

Provides a configured set of objects for use with an OAuth2 provider.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Provides a configured set of objects for use with an OAuth2 provider.`OAuthProvider(providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`, client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, modifyAuthState: (`[`Uri`](../../org.http4k.core/-uri/index.md)`) -> `[`Uri`](../../org.http4k.core/-uri/index.md)` = { it }, generateCrsf: `[`CsrfGenerator`](../-csrf-generator.md)` = SECURE_CSRF, nonceGenerator: `[`NonceGenerator`](../../org.http4k.security.openid/-nonce-generator.md)` = SECURE_NONCE, responseType: `[`ResponseType`](../-response-type/index.md)` = ResponseType.Code, idTokenConsumer: `[`IdTokenConsumer`](../../org.http4k.security.openid/-id-token-consumer/index.md)` = IdTokenConsumer.NoOp, accessTokenFetcherAuthenticator: `[`AccessTokenFetcherAuthenticator`](../-access-token-fetcher-authenticator/index.md)` = ClientSecretAccessTokenFetcherAuthenticator(providerConfig))` |

### Properties

| Name | Summary |
|---|---|
| [api](api.md) | `val api: `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [authFilter](auth-filter.md) | `val authFilter: `[`OAuthRedirectionFilter`](../-o-auth-redirection-filter/index.md) |
| [callback](callback.md) | `val callback: `[`OAuthCallback`](../-o-auth-callback/index.md) |
| [callbackEndpoint](callback-endpoint.md) | `val callbackEndpoint: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [providerConfig](provider-config.md) | `val providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [authFilter](auth-filter.md) | `fun authFilter(requestJwts: `[`RequestJwts`](../../org.http4k.security.openid/-request-jwts/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [auth0](../auth0.md) | Preconfigured OAuthProviders go here...`fun OAuthProvider.Companion.auth0(auth0Uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md) |
| [dropbox](../dropbox.md) | `fun OAuthProvider.Companion.dropbox(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md) |
| [facebook](../facebook.md) | `fun OAuthProvider.Companion.facebook(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("email")): `[`OAuthProvider`](./index.md) |
| [gitHub](../git-hub.md) | `fun OAuthProvider.Companion.gitHub(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("user")): `[`OAuthProvider`](./index.md) |
| [google](../google.md) | `fun OAuthProvider.Companion.google(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = listOf("openid")): `[`OAuthProvider`](./index.md) |
| [soundCloud](../sound-cloud.md) | `fun OAuthProvider.Companion.soundCloud(client: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`): `[`OAuthProvider`](./index.md) |
