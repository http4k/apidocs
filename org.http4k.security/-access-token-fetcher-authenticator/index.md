[http4k](../../index.md) / [org.http4k.security](../index.md) / [AccessTokenFetcherAuthenticator](./index.md)

# AccessTokenFetcherAuthenticator

`interface AccessTokenFetcherAuthenticator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/AccessTokenFetcherAuthenticator.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [authenticate](authenticate.md) | `abstract fun authenticate(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ClientSecretAccessTokenFetcherAuthenticator](../-client-secret-access-token-fetcher-authenticator/index.md) | `class ClientSecretAccessTokenFetcherAuthenticator : `[`AccessTokenFetcherAuthenticator`](./index.md) |
