[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokens](./index.md)

# AccessTokens

`interface AccessTokens` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AccessTokens.kt#L9)

Provides a consistent way to generate access tokens.

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `abstract fun create(authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AuthorizationCodeAlreadyUsed`](../-authorization-code-already-used.md)`>`<br>Creates a new access token for a valid authorization code.`abstract fun create(clientId: `[`ClientId`](../-client-id/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AccessTokenError`](../-access-token-error.md)`>`<br>creates a new access token for a given client. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
