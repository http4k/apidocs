[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodeDetails](./index.md)

# AuthorizationCodeDetails

`data class AuthorizationCodeDetails` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthorizationCodes.kt#L29)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationCodeDetails(clientId: `[`ClientId`](../-client-id/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, expiresAt: Instant)` |

### Properties

| Name | Summary |
|---|---|
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md) |
| [expiresAt](expires-at.md) | `val expiresAt: Instant` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
