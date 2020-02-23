[http4k](../../index.md) / [org.http4k.security.oauth.server.request](../index.md) / [RequestObject](./index.md)

# RequestObject

`data class RequestObject`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RequestObject(client: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`? = null, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null, audience: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = emptyList(), issuer: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, scope: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = emptyList(), responseMode: `[`ResponseMode`](../../org.http4k.security/-response-mode/index.md)`? = null, responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)`? = null, state: `[`State`](../../org.http4k.security/-state/index.md)`? = null, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`? = null, magAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, expiry: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, claims: `[`Claims`](../-claims/index.md)` = Claims())` |

### Properties

| Name | Summary |
|---|---|
| [audience](audience.md) | `val audience: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [claims](claims.md) | `val claims: `[`Claims`](../-claims/index.md) |
| [client](client.md) | `val client: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`?` |
| [expiry](expiry.md) | `val expiry: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [issuer](issuer.md) | `val issuer: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [magAge](mag-age.md) | `val magAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [nonce](nonce.md) | `val nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [responseMode](response-mode.md) | `val responseMode: `[`ResponseMode`](../../org.http4k.security/-response-mode/index.md)`?` |
| [responseType](response-type.md) | `val responseType: `[`ResponseType`](../../org.http4k.security/-response-type/index.md)`?` |
| [scope](scope.md) | `val scope: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [state](state.md) | `val state: `[`State`](../../org.http4k.security/-state/index.md)`?` |
