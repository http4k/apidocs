[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthoriseRequestErrorRender](./index.md)

# AuthoriseRequestErrorRender

`class AuthoriseRequestErrorRender` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthoriseRequestErrorRender.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthoriseRequestErrorRender(authoriseRequestValidator: `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md)`, fallBack: `[`JsonResponseErrorRenderer`](../-json-response-error-renderer/index.md)`, documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)` |

### Functions

| Name | Summary |
|---|---|
| [errorFor](error-for.md) | `fun errorFor(request: `[`Request`](../../org.http4k.core/-request/index.md)`, error: `[`OAuthError`](../-o-auth-error/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
