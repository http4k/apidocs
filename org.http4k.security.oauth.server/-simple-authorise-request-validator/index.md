[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [SimpleAuthoriseRequestValidator](./index.md)

# SimpleAuthoriseRequestValidator

`class SimpleAuthoriseRequestValidator : `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/SimpleAuthoriseRequestValidator.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SimpleAuthoriseRequestValidator(clientValidator: `[`ClientValidator`](../-client-validator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [isValidClientAndRedirectUriInCaseOfError](is-valid-client-and-redirect-uri-in-case-of-error.md) | `fun isValidClientAndRedirectUriInCaseOfError(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validate](validate.md) | `fun validate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authorizationRequest: `[`AuthRequest`](../-auth-request/index.md)`): Result<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OAuthError`](../-o-auth-error/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
