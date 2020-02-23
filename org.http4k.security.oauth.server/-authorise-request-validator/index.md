[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthoriseRequestValidator](./index.md)

# AuthoriseRequestValidator

`interface AuthoriseRequestValidator`

### Functions

| Name | Summary |
|---|---|
| [isValidClientAndRedirectUriInCaseOfError](is-valid-client-and-redirect-uri-in-case-of-error.md) | `abstract fun isValidClientAndRedirectUriInCaseOfError(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validate](validate.md) | `abstract fun validate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authorizationRequest: `[`AuthRequest`](../-auth-request/index.md)`): Result<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OAuthError`](../-o-auth-error/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [MustHaveRedirectUri](../-must-have-redirect-uri/index.md) | `class MustHaveRedirectUri : `[`AuthoriseRequestValidator`](./index.md) |
| [SimpleAuthoriseRequestValidator](../-simple-authorise-request-validator/index.md) | `class SimpleAuthoriseRequestValidator : `[`AuthoriseRequestValidator`](./index.md) |
