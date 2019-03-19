[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [InsecureCookieBasedAuthRequestPersistence](./index.md)

# InsecureCookieBasedAuthRequestPersistence

`class InsecureCookieBasedAuthRequestPersistence : `[`AuthRequestPersistence`](../-auth-request-persistence/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/InsecureCookieBasedAuthRequestPersistence.kt#L11)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsecureCookieBasedAuthRequestPersistence()` |

### Functions

| Name | Summary |
|---|---|
| [retrieveAuthRequest](retrieve-auth-request.md) | `fun retrieveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?`<br>Retrieves a particular AuthRequest related to the particular request |
| [storeAuthRequest](store-auth-request.md) | `fun storeAuthRequest(authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a reference of AuthRequest to the response |
