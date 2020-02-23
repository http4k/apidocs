[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AccessTokenRequestAuthentication](./index.md)

# AccessTokenRequestAuthentication

`interface AccessTokenRequestAuthentication`

### Functions

| Name | Summary |
|---|---|
| [validateCredentials](validate-credentials.md) | `abstract fun validateCredentials(request: `[`Request`](../../org.http4k.core/-request/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`Triple`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-triple/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`>, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [ClientSecretAccessTokenRequestAuthentication](../-client-secret-access-token-request-authentication/index.md) | `class ClientSecretAccessTokenRequestAuthentication : `[`AccessTokenRequestAuthentication`](./index.md) |
