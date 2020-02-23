[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AuthRequestTracking](./index.md)

# AuthRequestTracking

`interface AuthRequestTracking`

Provides a mechanism to track OAuth authorization parameters to be used later
(i.e. can be used later to generate code and/or tokens)

### Functions

| Name | Summary |
|---|---|
| [resolveAuthRequest](resolve-auth-request.md) | Resolves a particular AuthRequest related to the particular request`abstract fun resolveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?` |
| [trackAuthRequest](track-auth-request.md) | Assign a reference of AuthRequest to the response`abstract fun trackAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [InsecureCookieBasedAuthRequestTracking](../-insecure-cookie-based-auth-request-tracking/index.md) | `class InsecureCookieBasedAuthRequestTracking : `[`AuthRequestTracking`](./index.md) |
