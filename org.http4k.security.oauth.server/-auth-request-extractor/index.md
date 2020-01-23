[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestExtractor](./index.md)

# AuthRequestExtractor

`interface AuthRequestExtractor` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequestExtractor.kt#L9)

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `abstract fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AuthRequest`](../-auth-request/index.md)`, `[`InvalidAuthorizationRequest`](../-invalid-authorization-request/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthRequestFromQueryParameters](../-auth-request-from-query-parameters/index.md) | `object AuthRequestFromQueryParameters : `[`AuthRequestExtractor`](./index.md) |
| [AuthRequestWithRequestAuthRequestExtractor](../-auth-request-with-request-auth-request-extractor/index.md) | `class AuthRequestWithRequestAuthRequestExtractor : `[`AuthRequestExtractor`](./index.md) |
