[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](index.md) / [validateClientId](./validate-client-id.md)

# validateClientId

`abstract fun validateClientId(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L13)
* check that client_id is a valid, registered app
