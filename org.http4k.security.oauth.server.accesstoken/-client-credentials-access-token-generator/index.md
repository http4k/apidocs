[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [ClientCredentialsAccessTokenGenerator](./index.md)

# ClientCredentialsAccessTokenGenerator

`class ClientCredentialsAccessTokenGenerator : `[`AccessTokenGenerator`](../-access-token-generator/index.md)`<`[`ClientCredentialsRequest`](../-client-credentials-request/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/ClientCredentialsAccessTokenGenerator.kt#L16)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClientCredentialsAccessTokenGenerator(accessTokens: `[`AccessTokens`](../../org.http4k.security.oauth.server/-access-tokens/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [rfcGrantType](rfc-grant-type.md) | `val rfcGrantType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `fun generate(request: `[`ClientCredentialsRequest`](../-client-credentials-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |
| [resolveRequest](resolve-request.md) | `fun resolveRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Success<`[`ClientCredentialsRequest`](../-client-credentials-request/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
