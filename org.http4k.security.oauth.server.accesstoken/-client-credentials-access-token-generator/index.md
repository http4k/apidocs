[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [ClientCredentialsAccessTokenGenerator](./index.md)

# ClientCredentialsAccessTokenGenerator

`class ClientCredentialsAccessTokenGenerator : `[`AccessTokenGenerator`](../-access-token-generator/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/ClientCredentialsAccessTokenGenerator.kt#L15)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClientCredentialsAccessTokenGenerator(accessTokens: `[`AccessTokens`](../../org.http4k.security.oauth.server/-access-tokens/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>`<br>`fun generate(request: `[`ClientCredentialsRequest`](../-client-credentials-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
