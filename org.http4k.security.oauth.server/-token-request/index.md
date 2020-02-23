[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [TokenRequest](./index.md)

# TokenRequest

`data class TokenRequest`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TokenRequest(grantType: `[`GrantType`](../../org.http4k.security.oauth.server.accesstoken/-grant-type/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`?, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`?, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, clientAssertionType: `[`Uri`](../../org.http4k.core/-uri/index.md)`?, clientAssertion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, refreshToken: `[`RefreshToken`](../../org.http4k.security.oauth.server.refreshtoken/-refresh-token/index.md)`?)` |

### Properties

| Name | Summary |
|---|---|
| [clientAssertion](client-assertion.md) | `val clientAssertion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [clientAssertionType](client-assertion-type.md) | `val clientAssertionType: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md)`?` |
| [clientSecret](client-secret.md) | `val clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [code](code.md) | `val code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [grantType](grant-type.md) | `val grantType: `[`GrantType`](../../org.http4k.security.oauth.server.accesstoken/-grant-type/index.md) |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [refreshToken](refresh-token.md) | `val refreshToken: `[`RefreshToken`](../../org.http4k.security.oauth.server.refreshtoken/-refresh-token/index.md)`?` |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
