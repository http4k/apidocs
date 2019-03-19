[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestPersistence](./index.md)

# AuthRequestPersistence

`interface AuthRequestPersistence` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequestPersistence.kt#L10)

Provides a mechanism to store OAuth authorization parameters to be used later
(i.e. can be used later to generate code and/or tokens)

### Functions

| Name | Summary |
|---|---|
| [retrieveAuthRequest](retrieve-auth-request.md) | `abstract fun retrieveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?`<br>Retrieves a particular AuthRequest related to the particular request |
| [storeAuthRequest](store-auth-request.md) | `abstract fun storeAuthRequest(authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a reference of AuthRequest to the response |

### Inheritors

| Name | Summary |
|---|---|
| [InsecureCookieBasedAuthRequestPersistence](../-insecure-cookie-based-auth-request-persistence/index.md) | `class InsecureCookieBasedAuthRequestPersistence : `[`AuthRequestPersistence`](./index.md) |
