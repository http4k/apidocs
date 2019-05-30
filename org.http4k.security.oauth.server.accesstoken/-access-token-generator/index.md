[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AccessTokenGenerator](./index.md)

# AccessTokenGenerator

`interface AccessTokenGenerator<T : `[`AccessTokenRequest`](../-access-token-request.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AccessTokenGenerator.kt#L8)

### Properties

| Name | Summary |
|---|---|
| [rfcGrantType](rfc-grant-type.md) | `abstract val rfcGrantType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `abstract fun generate(request: `[`T`](index.md#T)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |
| [resolveRequest](resolve-request.md) | `abstract fun resolveRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`T`](index.md#T)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationCodeAccessTokenGenerator](../-authorization-code-access-token-generator/index.md) | `class AuthorizationCodeAccessTokenGenerator : `[`AccessTokenGenerator`](./index.md)`<`[`AuthorizationCodeAccessTokenRequest`](../-authorization-code-access-token-request/index.md)`>` |
| [ClientCredentialsAccessTokenGenerator](../-client-credentials-access-token-generator/index.md) | `class ClientCredentialsAccessTokenGenerator : `[`AccessTokenGenerator`](./index.md)`<`[`ClientCredentialsRequest`](../-client-credentials-request/index.md)`>` |
