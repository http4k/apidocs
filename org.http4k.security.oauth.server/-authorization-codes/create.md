[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodes](index.md) / [create](./create.md)

# create

`abstract fun create(authRequest: `[`AuthRequest`](../-auth-request/index.md)`): `[`AuthorizationCode`](../-authorization-code/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthorizationCodes.kt#L15)

Create new authorization code to be given to client after the user successfully authorize access
The generated authorization code needs to be associated with the clientId and redirectUri for later verification.
It should also be associated with a given expire date (recommended to be shorter than 10 minutes)

