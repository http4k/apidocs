[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokenRequest](./index.md)

# AccessTokenRequest

`data class AccessTokenRequest` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/GenerateAccessToken.kt#L80)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenRequest(clientId: `[`ClientId`](../-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [authorizationCode](authorization-code.md) | `val authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md) |
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md) |
| [clientSecret](client-secret.md) | `val clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |
