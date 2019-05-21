[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestFromQueryParameters](./index.md)

# AuthRequestFromQueryParameters

`object AuthRequestFromQueryParameters : `[`AuthRequestExtractor`](../-auth-request-extractor/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequestExtractor.kt#L13)

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | `fun extract(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AuthRequest`](../-auth-request/index.md)`, `[`InvalidAuthorizationRequest`](../-invalid-authorization-request/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
