[http4k](../../index.md) / [org.http4k.security](../index.md) / [AccessTokenFetcher](./index.md)

# AccessTokenFetcher

`class AccessTokenFetcher` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/AccessTokenFetcher.kt#L14)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenFetcher(api: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [fetch](fetch.md) | `fun fetch(code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AccessTokenDetails`](../-access-token-details/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
