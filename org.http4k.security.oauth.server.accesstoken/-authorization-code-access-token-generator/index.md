[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AuthorizationCodeAccessTokenGenerator](./index.md)

# AuthorizationCodeAccessTokenGenerator

`class AuthorizationCodeAccessTokenGenerator : `[`AccessTokenGenerator`](../-access-token-generator/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AuthorizationCodeAccessTokenGenerator.kt#L16)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationCodeAccessTokenGenerator(authorizationCodes: `[`AuthorizationCodes`](../../org.http4k.security.oauth.server/-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../../org.http4k.security.oauth.server/-access-tokens/index.md)`, clock: Clock, idTokens: `[`IdTokens`](../../org.http4k.security.oauth.server/-id-tokens/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>`<br>`fun generate(request: `[`AuthorizationCodeAccessTokenRequest`](../-authorization-code-access-token-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Success<`[`AuthorizationCodeAccessTokenRequest`](../-authorization-code-access-token-request/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
