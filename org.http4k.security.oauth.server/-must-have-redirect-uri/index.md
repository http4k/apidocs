[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [MustHaveRedirectUri](./index.md)

# MustHaveRedirectUri

`class MustHaveRedirectUri : `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthoriseRequestValidator.kt#L16)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MustHaveRedirectUri(delegate: `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [validate](validate.md) | `fun validate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authorizationRequest: `[`AuthRequest`](../-auth-request/index.md)`): Result<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`OAuthError`](../-o-auth-error/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
