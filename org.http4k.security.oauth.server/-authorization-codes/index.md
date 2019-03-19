[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthorizationCodes](./index.md)

# AuthorizationCodes

`interface AuthorizationCodes` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthorizationCodes.kt#L9)

Provides a consistent way to manage authorization codes

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `abstract fun create(authRequest: `[`AuthRequest`](../-auth-request/index.md)`): `[`AuthorizationCode`](../-authorization-code/index.md)<br>Create new authorization code to be given to client after the user successfully authorize access The generated authorization code needs to be associated with the clientId and redirectUri for later verification. It should also be associated with a given expire date (recommended to be shorter than 10 minutes) |
| [destroy](destroy.md) | `abstract fun destroy(authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Destroys an authorization token after it's been used to generate an access token |
| [detailsFor](details-for.md) | `abstract fun detailsFor(code: `[`AuthorizationCode`](../-authorization-code/index.md)`): `[`AuthorizationCodeDetails`](../-authorization-code-details/index.md)<br>Retrieve the details of an authorization code |
