[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestExtractor](./index.md)

# AuthRequestExtractor

`interface AuthRequestExtractor`

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `abstract fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AuthRequest`](../-auth-request/index.md)`, `[`InvalidAuthorizationRequest`](../-invalid-authorization-request/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [AuthRequestFromQueryParameters](../-auth-request-from-query-parameters/index.md) | `object AuthRequestFromQueryParameters : `[`AuthRequestExtractor`](./index.md) |
| [AuthRequestWithRequestAuthRequestExtractor](../-auth-request-with-request-auth-request-extractor/index.md) | `class AuthRequestWithRequestAuthRequestExtractor : `[`AuthRequestExtractor`](./index.md) |
