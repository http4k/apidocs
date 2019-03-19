[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](index.md) / [validateRedirection](./validate-redirection.md)

# validateRedirection

`abstract fun validateRedirection(clientId: `[`ClientId`](../-client-id/index.md)`, redirectionUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L14)

Client validation must include:

* check that client_id is a valid, registered app
* redirection URI is one of the allowed ones for that app
