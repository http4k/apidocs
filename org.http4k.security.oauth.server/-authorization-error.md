[http4k](../index.md) / [org.http4k.security.oauth.server](index.md) / [AuthorizationError](./-authorization-error.md)

# AuthorizationError

`sealed class AuthorizationError : `[`OAuthError`](-o-auth-error/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/OAuthError.kt#L47)

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
| [InvalidAuthorizationRequest](-invalid-authorization-request/index.md) | `data class InvalidAuthorizationRequest : `[`AuthorizationError`](./-authorization-error.md) |
| [InvalidClientId](-invalid-client-id.md) | `object InvalidClientId : `[`AuthorizationError`](./-authorization-error.md) |
| [InvalidRedirectUri](-invalid-redirect-uri.md) | `object InvalidRedirectUri : `[`AuthorizationError`](./-authorization-error.md) |
| [InvalidScopes](-invalid-scopes.md) | `object InvalidScopes : `[`AuthorizationError`](./-authorization-error.md) |
| [UnsupportedResponseType](-unsupported-response-type/index.md) | `data class UnsupportedResponseType : `[`AuthorizationError`](./-authorization-error.md) |
| [UserRejectedRequest](-user-rejected-request.md) | `object UserRejectedRequest : `[`AuthorizationError`](./-authorization-error.md) |
