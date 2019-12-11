[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AuthorizationCodeAccessTokenRequest](./index.md)

# AuthorizationCodeAccessTokenRequest

`data class AuthorizationCodeAccessTokenRequest` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AuthorizationCodeAccessTokenGenerator.kt#L65)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationCodeAccessTokenRequest(clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, authorizationCode: `[`AuthorizationCode`](../../org.http4k.security.oauth.server/-authorization-code/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [authorizationCode](authorization-code.md) | `val authorizationCode: `[`AuthorizationCode`](../../org.http4k.security.oauth.server/-authorization-code/index.md) |
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md) |
| [clientSecret](client-secret.md) | `val clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
