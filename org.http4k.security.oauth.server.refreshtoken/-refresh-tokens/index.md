[http4k](../../index.md) / [org.http4k.security.oauth.server.refreshtoken](../index.md) / [RefreshTokens](./index.md)

# RefreshTokens

`interface RefreshTokens` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/refreshtoken/RefreshTokens.kt#L10)

### Functions

| Name | Summary |
|---|---|
| [refreshAccessToken](refresh-access-token.md) | `abstract fun refreshAccessToken(refreshToken: `[`RefreshToken`](../-refresh-token/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [unsupported](unsupported.md) | `val unsupported: `[`RefreshTokens`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
