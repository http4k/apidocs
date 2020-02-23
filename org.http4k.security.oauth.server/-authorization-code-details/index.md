[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodeDetails](./index.md)

# AuthorizationCodeDetails

`data class AuthorizationCodeDetails`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationCodeDetails(clientId: `[`ClientId`](../-client-id/index.md)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, expiresAt: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`, state: `[`State`](../../org.http4k.security/-state/index.md)`?, isOIDC: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)` = Code, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md) |
| [expiresAt](expires-at.md) | `val expiresAt: `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html) |
| [isOIDC](is-o-i-d-c.md) | `val isOIDC: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nonce](nonce.md) | `val nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [responseType](response-type.md) | `val responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md) |
| [state](state.md) | `val state: `[`State`](../../org.http4k.security/-state/index.md)`?` |
