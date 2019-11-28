[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](./index.md)

# ClientValidator

`interface ClientValidator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L10)

Provides a consistent way to retrieve clients attempting to use an authorization code flow

### Functions

| Name | Summary |
|---|---|
| [validateClientId](validate-client-id.md) | `abstract fun validateClientId(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>check that client_id is a valid, registered app</li></ul> |
| [validateCredentials](validate-credentials.md) | `abstract fun validateCredentials(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Validate that credentials provided by the client match its registration records |
| [validateRedirection](validate-redirection.md) | `abstract fun validateRedirection(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, redirectionUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>redirection URI is one of the allowed ones for that client</li></ul> |
| [validateRequestJwt](validate-request-jwt.md) | `abstract fun validateRequestJwt(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, requestJwt: `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>request jwt are allowed for that client</li></ul> |
| [validateScopes](validate-scopes.md) | `abstract fun validateScopes(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>scopes are allowed for that client</li></ul> |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
