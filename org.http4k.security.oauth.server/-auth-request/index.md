[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequest](./index.md)

# AuthRequest

`data class AuthRequest`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthRequest(client: `[`ClientId`](../-client-id/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`?, state: `[`State`](../../org.http4k.security/-state/index.md)`?, responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)` = Code, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`? = null, responseMode: `[`ResponseMode`](../../org.http4k.security/-response-mode/index.md)`? = null, request: `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`? = null, requestObject: `[`RequestObject`](../../org.http4k.security.oauth.server.request/-request-object/index.md)`? = null, additionalProperties: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [additionalProperties](additional-properties.md) | `val additionalProperties: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>` |
| [client](client.md) | `val client: `[`ClientId`](../-client-id/index.md) |
| [nonce](nonce.md) | `val nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [request](request.md) | `val request: `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`?` |
| [requestObject](request-object.md) | `val requestObject: `[`RequestObject`](../../org.http4k.security.oauth.server.request/-request-object/index.md)`?` |
| [responseMode](response-mode.md) | `val responseMode: `[`ResponseMode`](../../org.http4k.security/-response-mode/index.md)`?` |
| [responseType](response-type.md) | `val responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [state](state.md) | `val state: `[`State`](../../org.http4k.security/-state/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [isOIDC](is-o-i-d-c.md) | `fun isOIDC(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [OIDC_SCOPE](-o-i-d-c_-s-c-o-p-e.md) | `const val OIDC_SCOPE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
