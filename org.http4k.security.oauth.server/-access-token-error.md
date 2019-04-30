[http4k](../index.md) / [org.http4k.security.oauth.server](index.md) / [AccessTokenError](./-access-token-error.md)

# AccessTokenError

`sealed class AccessTokenError : `[`OAuthError`](-o-auth-error/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/OAuthError.kt#L27)

### Inherited Properties

| Name | Summary |
|---|---|
| [description](-o-auth-error/description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [rfcError](-o-auth-error/rfc-error.md) | `val rfcError: `[`RfcError`](-rfc-error/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationCodeAlreadyUsed](-authorization-code-already-used.md) | `object AuthorizationCodeAlreadyUsed : `[`AccessTokenError`](./-access-token-error.md) |
| [AuthorizationCodeExpired](-authorization-code-expired.md) | `object AuthorizationCodeExpired : `[`AccessTokenError`](./-access-token-error.md) |
| [ClientIdMismatch](-client-id-mismatch.md) | `object ClientIdMismatch : `[`AccessTokenError`](./-access-token-error.md) |
| [InvalidClientCredentials](-invalid-client-credentials.md) | `object InvalidClientCredentials : `[`AccessTokenError`](./-access-token-error.md) |
| [RedirectUriMismatch](-redirect-uri-mismatch.md) | `object RedirectUriMismatch : `[`AccessTokenError`](./-access-token-error.md) |
| [UnsupportedGrantType](-unsupported-grant-type/index.md) | `data class UnsupportedGrantType : `[`AccessTokenError`](./-access-token-error.md) |
