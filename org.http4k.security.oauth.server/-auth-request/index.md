[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequest](./index.md)

# AuthRequest

`data class AuthRequest` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequest.kt#L5)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthRequest(client: `[`ClientId`](../-client-id/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, state: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [client](client.md) | `val client: `[`ClientId`](../-client-id/index.md) |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [state](state.md) | `val state: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
