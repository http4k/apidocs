[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](index.md) / [validateRequestJwt](./validate-request-jwt.md)

# validateRequestJwt

`abstract fun validateRequestJwt(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, requestJwt: `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L29)
* request jwt are allowed for that client
