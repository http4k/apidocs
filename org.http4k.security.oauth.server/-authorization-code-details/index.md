[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodeDetails](./index.md)

# AuthorizationCodeDetails

`data class AuthorizationCodeDetails` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthorizationCodes.kt#L28)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationCodeDetails(clientId: `[`ClientId`](../-client-id/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, expiresAt: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`, isOIDC: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)` = Code)` |

### Properties

| Name | Summary |
|---|---|
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md) |
| [expiresAt](expires-at.md) | `val expiresAt: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html) |
| [isOIDC](is-o-i-d-c.md) | `val isOIDC: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [responseType](response-type.md) | `val responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
