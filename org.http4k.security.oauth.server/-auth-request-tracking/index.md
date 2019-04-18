[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestTracking](./index.md)

# AuthRequestTracking

`interface AuthRequestTracking` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AuthRequestTracking.kt#L10)

Provides a mechanism to track OAuth authorization parameters to be used later
(i.e. can be used later to generate code and/or tokens)

### Functions

| Name | Summary |
|---|---|
| [resolveAuthRequest](resolve-auth-request.md) | `abstract fun resolveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?`<br>Resolves a particular AuthRequest related to the particular request |
| [trackAuthRequest](track-auth-request.md) | `abstract fun trackAuthRequest(authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a reference of AuthRequest to the response |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [InsecureCookieBasedAuthRequestTracking](../-insecure-cookie-based-auth-request-tracking/index.md) | `class InsecureCookieBasedAuthRequestTracking : `[`AuthRequestTracking`](./index.md) |
