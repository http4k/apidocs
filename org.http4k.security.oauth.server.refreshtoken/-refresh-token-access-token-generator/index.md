[http4k](../../index.md) / [org.http4k.security.oauth.server.refreshtoken](../index.md) / [RefreshTokenAccessTokenGenerator](./index.md)

# RefreshTokenAccessTokenGenerator

`class RefreshTokenAccessTokenGenerator : `[`AccessTokenGenerator`](../../org.http4k.security.oauth.server.accesstoken/-access-token-generator/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/refreshtoken/RefreshTokenAccessTokenGenerator.kt#L14)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RefreshTokenAccessTokenGenerator(refreshTokens: `[`RefreshTokens`](../-refresh-tokens/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
