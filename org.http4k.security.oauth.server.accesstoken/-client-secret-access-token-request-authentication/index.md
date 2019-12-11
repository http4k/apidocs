[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [ClientSecretAccessTokenRequestAuthentication](./index.md)

# ClientSecretAccessTokenRequestAuthentication

`class ClientSecretAccessTokenRequestAuthentication : `[`AccessTokenRequestAuthentication`](../-access-token-request-authentication/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AccessTokenRequestAuthentication.kt#L17)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClientSecretAccessTokenRequestAuthentication(clientValidator: `[`ClientValidator`](../../org.http4k.security.oauth.server/-client-validator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [validateCredentials](validate-credentials.md) | `fun validateCredentials(request: `[`Request`](../../org.http4k.core/-request/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`Triple`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-triple/index.html)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`>, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
