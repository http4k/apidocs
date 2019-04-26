[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokenError](./index.md)

# AccessTokenError

`sealed class AccessTokenError` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/GenerateAccessToken.kt#L84)

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rfcError](rfc-error.md) | `val rfcError: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationCodeAlreadyUsed](../-authorization-code-already-used.md) | `object AuthorizationCodeAlreadyUsed : `[`AccessTokenError`](./index.md) |
