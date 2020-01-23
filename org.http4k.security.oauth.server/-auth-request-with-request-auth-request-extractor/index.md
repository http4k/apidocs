[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestWithRequestAuthRequestExtractor](./index.md)

# AuthRequestWithRequestAuthRequestExtractor

`class AuthRequestWithRequestAuthRequestExtractor : `[`AuthRequestExtractor`](../-auth-request-extractor/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequestWithRequestAuthRequestExtractor.kt#L15)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthRequestWithRequestAuthRequestExtractor(requestJWTValidator: `[`RequestJWTValidator`](../../org.http4k.security.oauth.server.request/-request-j-w-t-validator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AuthRequest`](../-auth-request/index.md)`, `[`InvalidAuthorizationRequest`](../-invalid-authorization-request/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
