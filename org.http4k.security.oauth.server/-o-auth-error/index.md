[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [OAuthError](./index.md)

# OAuthError

`abstract class OAuthError` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/OAuthError.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthError(rfcError: `[`RfcError`](../-rfc-error/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rfcError](rfc-error.md) | `val rfcError: `[`RfcError`](../-rfc-error/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [AccessTokenError](../-access-token-error.md) | `sealed class AccessTokenError : `[`OAuthError`](./index.md) |
| [AuthorizationError](../-authorization-error.md) | `sealed class AuthorizationError : `[`OAuthError`](./index.md) |
