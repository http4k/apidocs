[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [IdTokens](./index.md)

# IdTokens

`interface IdTokens` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/IdTokens.kt#L9)

### Functions

| Name | Summary |
|---|---|
| [createForAccessToken](create-for-access-token.md) | `abstract fun createForAccessToken(authorizationCodeDetails: `[`AuthorizationCodeDetails`](../-authorization-code-details/index.md)`, code: `[`AuthorizationCode`](../-authorization-code/index.md)`, accessToken: `[`AccessToken`](../../org.http4k.security/-access-token/index.md)`): `[`IdToken`](../../org.http4k.security.openid/-id-token/index.md) |
| [createForAuthorization](create-for-authorization.md) | `abstract fun createForAuthorization(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?, code: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`IdToken`](../../org.http4k.security.openid/-id-token/index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [Unsupported](-unsupported.md) | `val Unsupported: `[`IdTokens`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
