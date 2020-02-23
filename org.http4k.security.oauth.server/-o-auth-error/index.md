[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [OAuthError](./index.md)

# OAuthError

`abstract class OAuthError`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthError(rfcError: `[`RfcError`](../-rfc-error/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rfcError](rfc-error.md) | `val rfcError: `[`RfcError`](../-rfc-error/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AccessTokenError](../-access-token-error.md) | `sealed class AccessTokenError : `[`OAuthError`](./index.md) |
| [AuthorizationError](../-authorization-error.md) | `sealed class AuthorizationError : `[`OAuthError`](./index.md) |
