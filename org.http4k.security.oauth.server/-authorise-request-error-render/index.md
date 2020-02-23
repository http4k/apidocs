[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthoriseRequestErrorRender](./index.md)

# AuthoriseRequestErrorRender

`class AuthoriseRequestErrorRender`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthoriseRequestErrorRender(authoriseRequestValidator: `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md)`, requestJWTValidator: `[`RequestJWTValidator`](../../org.http4k.security.oauth.server.request/-request-j-w-t-validator/index.md)`, fallBack: `[`JsonResponseErrorRenderer`](../-json-response-error-renderer/index.md)`, documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)` |

### Functions

| Name | Summary |
|---|---|
| [errorFor](error-for.md) | `fun errorFor(request: `[`Request`](../../org.http4k.core/-request/index.md)`, error: `[`OAuthError`](../-o-auth-error/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
