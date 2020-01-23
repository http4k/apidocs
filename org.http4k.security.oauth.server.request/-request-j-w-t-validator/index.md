[http4k](../../index.md) / [org.http4k.security.oauth.server.request](../index.md) / [RequestJWTValidator](./index.md)

# RequestJWTValidator

`interface RequestJWTValidator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/request/RequestJWTValidator.kt#L8)

### Functions

| Name | Summary |
|---|---|
| [validate](validate.md) | `abstract fun validate(clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, requestJwtContainer: `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`): `[`InvalidAuthorizationRequest`](../../org.http4k.security.oauth.server/-invalid-authorization-request/index.md)`?` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [Unsupported](-unsupported.md) | `val Unsupported: `[`RequestJWTValidator`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
