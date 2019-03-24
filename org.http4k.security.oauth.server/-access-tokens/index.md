[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokens](./index.md)

# AccessTokens

`interface AccessTokens` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AccessTokens.kt#L8)

Provides a consistent way to generate access tokens

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `abstract fun create(authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`AccessTokenContainer`](../../org.http4k.security/-access-token-container/index.md)<br>Creates a new access token for a valid authorization code |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
