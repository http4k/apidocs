[http4k](../../index.md) / [org.http4k.security](../index.md) / [AccessTokenFetcher](./index.md)

# AccessTokenFetcher

`class AccessTokenFetcher`

### Types

| Name | Summary |
|---|---|
| [Forms](-forms/index.md) | `object Forms` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenFetcher(api: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`, accessTokenFetcherAuthenticator: `[`AccessTokenFetcherAuthenticator`](../-access-token-fetcher-authenticator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [fetch](fetch.md) | `fun fetch(theCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AccessTokenDetails`](../-access-token-details/index.md)`?` |
