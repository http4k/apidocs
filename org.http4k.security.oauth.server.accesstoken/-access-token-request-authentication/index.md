[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AccessTokenRequestAuthentication](./index.md)

# AccessTokenRequestAuthentication

`interface AccessTokenRequestAuthentication` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AccessTokenRequestAuthentication.kt#L13)

### Functions

| Name | Summary |
|---|---|
| [validateCredentials](validate-credentials.md) | `abstract fun validateCredentials(request: `[`Request`](../../org.http4k.core/-request/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ClientSecretAccessTokenRequestAuthentication](../-client-secret-access-token-request-authentication/index.md) | `class ClientSecretAccessTokenRequestAuthentication : `[`AccessTokenRequestAuthentication`](./index.md) |
