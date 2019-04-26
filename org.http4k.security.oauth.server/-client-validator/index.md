[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](./index.md)

# ClientValidator

`interface ClientValidator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L8)

Provides a consistent way to retrieve clients attempting to use an authorization code flow

### Functions

| Name | Summary |
|---|---|
| [validateClientId](validate-client-id.md) | `abstract fun validateClientId(clientId: `[`ClientId`](../-client-id/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>check that client_id is a valid, registered app</li></ul> |
| [validateCredentials](validate-credentials.md) | `abstract fun validateCredentials(clientId: `[`ClientId`](../-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Validate that credentials provided by the client match its registration records |
| [validateRedirection](validate-redirection.md) | `abstract fun validateRedirection(clientId: `[`ClientId`](../-client-id/index.md)`, redirectionUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<ul><li>redirection URI is one of the allowed ones for that client</li></ul> |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
