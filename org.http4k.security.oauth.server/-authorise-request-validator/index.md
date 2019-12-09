[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthoriseRequestValidator](./index.md)

# AuthoriseRequestValidator

`interface AuthoriseRequestValidator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthoriseRequestValidator.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [validate](validate.md) | `abstract fun validate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authorizationRequest: `[`AuthRequest`](../-auth-request/index.md)`): Result<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OAuthError`](../-o-auth-error/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [SimpleAuthoriseRequestValidator](../-simple-authorise-request-validator/index.md) | `class SimpleAuthoriseRequestValidator : `[`AuthoriseRequestValidator`](./index.md) |
